# abc

Branch|[![Travis CI logo](TravisCI.png)](https://travis-ci.org)
---|---
master|[![Build Status](https://travis-ci.org/richelbilderbeek/abc.svg?branch=master)](https://travis-ci.org/richelbilderbeek/abc)

This is my ABC notation page, mostly for my own reference really...

## From an abc text file to something else

What|Command|Output filenname
---|---|---
Convert ABC to midi | `abc2midi filename.abc` | `filename1.mid`
Convert ABC to postscript | `abcm2ps filename.abc` | `Out.ps`
Play the Midi file | `playsound filename1.mid` | (none)
Transpose ABC file  | `abc2abc filename.abc -t 1 > filename2.abc`  | filename2.abc

## My first song

```
X:1
T:Richel's first song
C:Richel Bilderbeek
L:1/4
Q:1/4=180
M:4/4
K:C
V:V1 clef=treble
V:V2 clef=bass
[V:V1] cABc | cABc | cABc ||
[V:V2] D,E,F,D, | D,E,F,D, | D,E,F,D, ||
```

## My ABC notation files

 * [Ah! Les crocodiles (French nursery rhyme)](AhLesCrocodiles.abc)
 * [Al Heb Je Blauw Haar](AlHebJeBlauwHaar.abc)
 * [Come Home Darling](ComeHomeDarling.abc)
 * [De ...](DeLul.abc)
 * ["Friday"](Friday.abc)
 * [Grote Gele Sinaasappel](GroteGeleSinaasappel.abc)
 * [Het Koffielied](HetKoffielied.abc)
 * [Het Leven Is Naar](HetLevenIsNaar.abc)
 * [Het Mentorkindjeslied](HetMentorkindjeslied.abc)
 * [Het N..kmenslied](HetNeukmenslied.abc)
 * [Maanliedje](Maanliedje.abc)
 * [O Mooie Geluidsvrouw](OMooieGeluidsvrouw.abc)
 * [Wooloo Mooloo](WoolooMooloo.abc)

## External links

 * [abcnotation.com](http://www.abcnotation.com)
 * [ABC notation basics](http://www.abcnotation.com/blog/2010/01/31/how-to-understand-abc-the-basics)
 * [ABC notation FAQ](http://trillian.mit.edu/~jc/music/abc/ABC-FAQ.html)
 * [ABC tune finder](http://trillian.mit.edu/~jc/cgi/abc/tunefind)
