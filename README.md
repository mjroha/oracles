# Oracles

**by Jens Alfke**

This is just a simple web-app that randomly chooses and displays messages, intended to serve as inspiration for roleplaying games or fiction. See it in action:

* **[In A Wicked Age][SITE_IAWA]**
* **[Itras By][SITE_ITRAS]**
* **[The Decktet][SITE_DECKTET]**

There are a lot of these online oracles/generators already (check out [Chaotic Shiny][SHINY] and [Abulafia][ABULAFIA]), and there's nothing especially novel about this one; it's just that the existing ones display very bare-bones HTML, but I wanted one that's as lovely as the works that inspired it.

## Features

* It's pretty! I've tried to follow the designs of the books (q.v.) without aping them exactly. I used free fonts from [Google Web Fonts][GWF] and backgrounds from [Eos][EOS].
* It looks pretty good on an iPhone, using the special `viewport` meta tag. (I'm not sure how it looks on Android or other mobile devices; let me know if it can be improved.)
* On iOS it's optimized for being saved to the home screen. It's got a custom icon and it opens up full-screen. (It doesn't yet run offline, though.)
* It's 100% client-side code, so you can run it on any web server or even on your local disk, without needing PHP or anything else.

## Source Books

### In A Wicked Age

Vincent Baker's **_[In A Wicked Age][IAWA]_** is a dark fantasy sword-and-sorcery roleplaying game focused on storytelling. An integral part of the game is its four "Oracles": before each session the group draws four cards from one of these and uses the characters, locations and situations they describe.

(There are already [two][ORACLE1] [different][ORACLE2] functional but bare-vones web implementations of these oracles.)

**Oracle text is copyright &copy; 2007 Vincent Baker.**

### Itras By

**_[Itras By][ITRASBY]_** is a surreal role-playing game by Ole Peder Giæver and Martin Bull Gudmundsen, which takes place in the vaguely-1920s, vaguely-Nordic setting of the eponymous city. The game doesn't use dice; instead, decisions are resolved by drawing cards.

**Resolution card text is copyright &copy; 2008-2012 Ole Peder Giæver and Martin Bull Gudmundsen (English translation by Ole Peder Giæver, Jimi Thaule, Martin Bull Gudmundsen, Magnus Jakobsson.)**

### The Decktet

**_[The Decktet][DECKTET]_** is a deck of cards invented by P.D. Magnus. It is unique in that most of the cards have multiple suits; this allows for many novel mechanisms in card games. Moreover, each card has a unique picture and name, with a suggested Tarot-like interpretation. While no one to my knowledge actually _believes_ in the divinatory power of the Decktet, the pictures and interpretations are certainly evocative.

**The Decktet design and card images are copyright &copy;2010-2012 P.D. Magnus. Some rights reserved. A version of the deck and a bunch of supporting prose is offered as open content under a Creative Commons Attribution NonCommercial ShareAlike 3.0 License.**

## Credits

* **Text is copyrighted as listed above.**
* Macondo Swash Caps font is by John Vargas Beltrán. (SIL Open Font License)
* Goudy Bookletter 1911 font is by Barry Schwartz, based on the original design by Frederick Goudy.  (SIL Open Font License)
* Berkshire Swash font by Brian J. Bonislawsky, Astigmatic One Eye Typographic Institute.  (SIL Open Font License)
* Fortune Letters and Refreshing Beverages fonts by P.D. Magnus, "free for use in any project, commercial or non-commercial".
* Background textures are by Eos Design. (No license specified; free for personal/nonprofit use)
* Code and markup are by me, [Jens][SNEJ]. (License is ... um, let's say Apache 2.)

[SITE_IAWA]: http://mooseyard.com/oracles/
[SITE_ITRAS]: http://mooseyard.com/oracles/itrasby/
[SITE_DECKTET]: http://mooseyard.com/oracles/decktet/
[SHINY]: http://chaoticshiny.com
[ABULAFIA]: http://www.random-generator.com
[IAWA]: http://www.lumpley.com/wicked.html
[ORACLE1]: http://www.lumpley.com/oracle/4oracles.php
[ORACLE2]: http://www.random-generator.com/index.php?title=In_a_Wicked_Age
[GWF]: http://www.google.com/webfonts
[EOS]: http://www.eosdev.com/ForYouFromEos.htm
[SNEJ]: http://github.com/snej
[ITRASBY]: http://www.vagrantworkshop.com/index.php?categoryid=8&p2_articleid=42
[DECKTET]: http://decktet.com
