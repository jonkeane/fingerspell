fingerspell
================================

fingerspell.sty provides two commands: \fs{} and \fslist{}

\fs{}
-------------------------
Use \fs{foo} to typset the word foo in small caps with dashes between each letter: F-O-O


\fslist{}
-------------------------
Use \fslist{b,a,r} to typset the letters b, a, and r as individual letters with dashes on either side, in small caps, with commas, and and at the end. It even deals with the harvard comma appropriately.

TODO
-------------------------
* Change \fslist{} to not need commas.
* Is mbox the best way to protect line breaks?

