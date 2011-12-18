fingerspell
================================

There are numerous ways of glossing ASL lexical items. In an effort to keep these glosses integrated in running text I have adopted clear and elegant typographic conventions of Cormier et al. (2008). Not only is this consistent with separating ASL forms from the text as well as reliably marking the difference between ASL native signs (smallcaps) and fingerspelled forms (smallcaps, with hyphens) but it also is easier to read than many other systems. Following from this, single finger spelled letters can be flanked by hyphens on either side.

fingerspell.sty provides two commands: \fs{} and \fslist{}

\fs{}
-------------------------
Use \fs{foo} to typset the word foo in small caps with dashes between each letter: F-O-O


\fslist[and]{}
-------------------------
Use \fslist{b,a,r} to typset the letters b, a, and r as individual letters with dashes on either side, in small caps, with commas, and and at the end. It even deals with the final serial comma appropriately. Additionally there is an optional argument that changes the conjunction used; the default is and.

TODO
-------------------------
* Change \fslist{} to not need commas.
* Is mbox the best way to protect line breaks?

