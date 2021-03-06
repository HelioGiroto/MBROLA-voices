BR3 Database
release 2.021

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 A brief description of the BR3 database
2.0 Distribution
3.0 Installation, and tests
4.0 Acknowledgments

--------------------------------------------------------------
1.0 A brief description of BR3
--------------------------------------------------------------
BR3 is a Brazilian Portuguese diphone database provided in the
context of the MBROLA project
(see http://tcts.fpms.ac.be/synthesis).

It provides a Portuguese male voice to be used with the MBROLA program.

Input files use the following diphone representations, that diverges
from SAMPA in some points:

PHONEME   	EXAMPLE		TRANSCRIPTION	SAMPA EQUIVALENT
b 		barco           "ba r2 ku		b
k		com		"k om			k
d		doce		"dose			d
g		grande		"gr am de		g
p		pai		"pai			p
t		taco		"tako			t

f		fácil		"fasiw			f
v		vinho		"vi nh o		v
j		jato		"jato			Z
s		sala		"sala			s
s2		casca		"ka s2 ka		---
x		chave		"xave			S
z		aza		"aza			z

m		mesmo		"me s2 mo		m
n		nunca		"n um ka		n
nh		galinha		ga"li nh a		J

l		lanche		"l am xe		l	
lh		alho		"a lh o			L
r		puro		"puro			r
r2		arpa		"a r2 pa		---
rr		torre		"to rr e		R

a		vale		"vale			a
@		tamanho		ta "m@ nh o		6	
am		campanha	k am "pa nh a		---
e		pêra		"pera			e
ee		quero		"k ee ro		E
em		quente		"k em te		e~
i		pico		"piko			i
im		brinco		"br im ko		i~
o		tolo		"tolo			o
oo		bola		"b oo la		---
om		ombro		"om bro			o~
u		duro		"duro			u
um		algum		aw"g um 		u~

y		mais		"may s2			y
w		mau		"maw			w

_		silence	


--------------------------------------------------------------
2.0 Distribution
--------------------------------------------------------------

This distribution of mbrola contains the following files : 

   BR3      : the database itself
   BR3.txt  : This file
   license.txt : must read before using the database
   
   TEST/<1-10>.pho: sample pho files

Additional languages and voices, as well as other example command
files, are or will be available in the context of the MBROLA 
project. Please consult the MBROLA project homepage :
   http://tcts.fpms.ac.be/synthesis

Registered users will automatically be notified of the availability 
of new databases. To freely register, simply send an email to 
mbrola-interest-request@tcts.fpms.ac.be with the word 'subscribe'
in the message title.

--------------------------------------------------------------
3.0 Installation and Tests
--------------------------------------------------------------

If you have not copied the MBROLA software yet, please consult
the MBROLA project homepage and get it.

Copy BR3.zip into the mbrola directory and unzip it : 

   unzip BR3.zip (or pkunzip on PC/DOS)
   (don't forget to delete the .zip file when this is done)

Try 

   mbrola BR3 TEST/1.pho 1.wav

to create a sound file. In this example the audio file follows 
the RIFF Wav format. But depending on the extension test.au, test.aif, 
or test.raw you can obtain other file formats. Listen to it with your 
favorite sound editor, and try other command files (*.pho) to have 
a better idea of the quality of speech you can synthesize with the 
MBROLA technique.

On Unix systems you can pipe the audio ouput to the sound player as
on a HP : mbrola br3 1.pho - | splayer -srate 22050 -l16

Also refer to the readme.txt file provided with the mbrola 
software for using it.

--------------------------------------------------------------
4.0 Acknowledgements
--------------------------------------------------------------

I would like to thank Vincent Pagel for his attention
and fast  work in preparing the database.

--------------------------------------------------------------
Denis R. Costa: Technology Director at MicroPower Software.

e-mail: dcosta@micropower.com.br, for questions concerning the 
database BR3.

e-mail: mbrola@tcts.fpms.ac.be, for general information, 
questions on the installation of software and databases.
