# Movie-Title-Loop
from random import *

preamble = ['The Last', 'Super', 'The Great', 'Death of', 'The Ressurrection of ', 'Return of','The Dark','']
character = ['Makhi:','Link:','Christall:','Ryuk:','Emma:','Phil:','Brock:','Brimstone:','Ghostrider:','Sydney:','Marshall:','Kate:']
tagline = ['Savage Wilds', 'Limbo','Dying World','Fiery Hell',' A New Day','Tragedy','World Tour','SPACE','World in the Sky','The Last Defender','Homecoming','Ultimatum','House of Xenon','Wrath of the Specter']

numPreamble = len(preamble) - 1
numCharacter = len(character) - 1
numTagline = len(tagline) - 1
movieLoop=0

while movieLoop < 15:
    print preamble[randint(0,numPreamble)] , character[randint(0,numCharacter)] , tagline[randint(0,numTagline)]
    movieLoop= movieLoop + 1
