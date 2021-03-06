BR4 - Brazilian Portuguese Mbrola Diphone Database 
release 1.0

--------------------------------------------------------------
Table of Contents
--------------------------------------------------------------

1.0 A brief description of the BR4 database
2.0 Distribution
3.0 Installation, and tests
4.0 Acknowledgments

--------------------------------------------------------------
1.0 A brief description of BR4
--------------------------------------------------------------
BR4 is a Brazilian Portuguese diphone database provided in the
context of the MBROLA project
(see http://tcts.fpms.ac.be/synthesis).

It provides a Portuguese female voice to be used with the MBROLA program.
The corpus was taken from Carioca Speech from Rio de Janeiro, recorded
by a brazilian TV reporter, Liane Borges, in 16000 KHz.

This database has been created as an initiative of Serpro - Serviço
Federal de Processamento de Dados, to be used as a good free voice
syntesis alternative for accessibility systems in Brasil.  It's
commonly used together with the Serpro LianeTTS brazilian portuguese
TTS translator, also distributed as free software.

Input files use the following diphone representations.

PHONEME 	EXAMPLE		TRANSCRIPTION

_		(silence)
a		pata		p a t a
@		ação		a s @ w
b		bata		b a t a
d		dado		d a d w
e		pedir		p e d i r2
ee		café		k a f ee
en		pente		p en t y
f		faca		f a k a
g		gato		g a t w
h		habib		h a b i b y
i		fita		f i t a
in		pinto		p in t w
j		jaca		j a k a
k		capa		k a p a
l		lata		l a t a
lh		alho		a lh w
m		mato		m a t w
m2		falam		f a l a m2
n		nada		n a d a
nh		pinha		p i nh a
o		bobi		b o b w
on		ponte		p on t y
oo		loja		l oo j a
p		pato		p a t w
r		cara		k a r a
r2		arte		a r2 t y
rr		farra		f a rr a
s		salada		s a l a d a
s2		casca		k a s2 k a
t		tato		t a t w
u		tubo		t u b w
un		fundo		f un d w
v		vaca		v a k a
w		mito		m i t w
x		xarope		x a r oo p y
y		fale		f a l y
z		zoar		z o a r2


--------------------------------------------------------------
2.0 Distribution
--------------------------------------------------------------

This distribution of mbrola contains the following files : 

   br4      : the database itself
   br4.txt  : This file
   license.txt : must read before using the database
   
   TEST/*   : some samples, generated in PHO format

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

Copy br4.zip into the mbrola directory and unzip it : 

   unzip br4.zip
   (don't forget to delete the .zip file when this is done)

Try 

   [path to mbroli.exe] br4 TEST/test.pho

to play a sample to have a better idea of the quality of speech
you can synthesize with the MBROLA technique.  We suggest you to
play with the rate=0.8 which produces a similar speech relative
to a real person in Rio de Janeiro - Brazil.

On Unix systems you can pipe the audio ouput to the sound player like
	mbrola br4 test.pho - | splayer -srate 16000 -l16
or similarly in Linux with other players (like bplay, aplay, paplay, etc).

Also refer to the readme.txt file provided with the mbrola 
software for using it, specially to change voice parameters.

--------------------------------------------------------------
4.0 Acknowledgements
--------------------------------------------------------------

We would like to thank Professor Nicholas D'Alessandro for his
attention in preparing the database.

--------------------------------------------------------------

Serpro - Serviço Federal de Processamento de Dados

Dilson José dos Santos
Coordenador Estratégico de Responsabilidade Social e Cidadania. 

Claudio Maia Dallalana
Accessibility Projects Manager
claudio-maia.dallalana@serpro.gov.br

Prof. Dr. José Antonio Borges
Technical Consultant on Speech Synthesis

Speaker:  Liane Paixão Borges

The Serpro Liane-TTS Compiler
		Prof. José Antonio Borges
		Prof. Antonio Anibal Teles
(Núcleo de Computação Eletrônica - Federal University of Rio de Janeiro)

For technical questions concerning the br4 database or the Liane TTS
Compiler, please send an e-mail to antonio2@nce.ufrj.br

e-mail: mbrola@tcts.fpms.ac.be, for general information, 
questions on the installation of software and databases.
