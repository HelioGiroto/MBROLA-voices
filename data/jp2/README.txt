jjjjjjjjjjjjjjjj   ppppppppppppp       2222222222
jjjjjjjjjjjjjjjj   pppppppppppppp     222222222222
           jjjjj   pppp       ppp    222      2222
           jjjjj   pppp       ppp   222    22222
           jjjjj   ppppp      ppp        22222        
           jjjjj   ppppppppppppp        22222        
jjj        jjjjj   pppp pppppp         22222      
 jjj       jjjjj   pppp              2222222222222  
   jjjjjjjjjjj    ppppp             222222222222222
     

release 0.1 - February 2002
--------------------------------------------------------------
JP2 - A Japanese female voice for the MBROLA synthesizer

Created by: 
Tomohisa Tachiki
Institut für Phonetik
Johann Wolfgang Goethe-Universität Frankfurt am Main
--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 Description of the JP2 diphone database
2.0 Installation and tests
3.0 Acknowledgements

--------------------------------------------------------------
1.0 Description of the JP2 diphone database
--------------------------------------------------------------

JP2 is a diphone database for japanese, consisting of 890
diphones, female voice.

The following phoneme symbols are assumed in my diphone sets. It
slightly differ for the SAMPA alphabet.

SYMBOL PRONOUNCED LIKE IN
p       piano hampuku
t       tai mato
k       kubi hanko

b       bachi kibun
d       daikan handô
g       garakuta kago

f       fune saifu
s       sori esa
S       shakai kisi
C	hikari mahiru
h	hana kahogo

v	vaiorin (only for foreign words)
z       aza kaze
Z       aji kujaku
	
ts      tsukue atsui
tS      chikara ocha

dz      dzukô dzaru 
dZ      jishin jaguchi

m	maru mimi
n	neko kimono
n1	niku tani
G	manga hango
m:	shimbun (the moraic nasal / bilabial)
n:	hantai (the moraic nasal / alveolar)
n1:	hannin (the moraic nasal / alveolo-palatal)
G:	kango (the moraic nasal / velar)
N:	shinai (the moraic nasal / uvular)

r	haru rakuda

j	yoru koya
w	wani kawa

Q	makka (the first part of a geminate consonant)

a	aka asa
e	eki	namae
o	oto doko
u	uta kuda
i	ishi michi

u_0	kusuri (voiceless)
i_0	shiki (voiceless)

a:	râmen mâchi (long)
e:	keiken (= kêken) mêdê (long)
o:	kôkô môtâ (long)
u:	kûki sûgaku (long)
i:	oniisan (= onîsan) chîzu (long)		 	

--------------------------------------------------------------
2.0 Installation and Tests
--------------------------------------------------------------

If you have not copied the MBROLA software yet, please consult
the MBROLA project homepage and get it.

Copy jp2.zip into the mbrola directory and unzip it: 

   unzip jp2.zip (or pkunzip on PC/DOS)

Try 

   Mbrola jp2 TEST/oha.pho oha.wav 

to create  a sound file for the sentence 'ohayô gozaimasu. anshôbangô o dôzo'. In this example the audio file follows the RIFF Wav format. But depending on the extension oha.au, oha.aif, or  oha.raw you can obtain other file formats. Listen  to it with your favorite sound editor, and try the other command files (*.pho) to have a better idea of the quality of speech you can synthesize with the MBROLA technique. 

On Unix systems you can pipe the audio ouput to the sound player as on a HP: mbrola jp2 oha.pho - | splayer -srate 16000 -l16

Also refer to the readme.txt file provided with the mbrola software for using it.  

--------------------------------------------------------------
3.0 Acknowledgments
--------------------------------------------------------------
I would like to thank Akiko Nakajima and Dr Fred Englert for their efforts and help in desingning of this database.

--------------------------------------------------------------

Tomohisa Tachiki

e-mail: tachiki@gmx.de
        
--------------------------------------------------------------

