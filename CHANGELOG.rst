=========
Changelog
=========

Darkslide v1.2.1 (2015-05-21)
=============================

- Couple minor improvements to Abyss theme.

Darkslide v1.2.0 (2015-05-19)
=============================

- Modifier keys flag was not cleared propertly (kb shortcuts were not working anymore after
  alt-tab etc); now it's cleared on visibility changes and focus loss.
- Changed expanded mode to automatically hide the context.
- Fixed window resize flickering (for every resize event the expaded flag was toggled).
- Disabled context hiding in presenter view.
- Other small styling improvements.
- Added "abyss" theme.

Landslide v1.1.3
================

-  Identify each slide by a numbered class (#171) (dkg)
-  Fix theme image embedding regex to grab all images (#170)
-  Fix blockquote font size for rst (#161)
-  Fix display of RST image target links (#87)
-  Fix relative path generation (#147)
-  Add command line option for print version (#135)
-  Add use of '---' as a slide separator to textile files (#163)
-  README improvements (#88 and #101)
-  Improve image path regex and replacement (#177)

Landslide v1.1.2
================

-  Add support for Python 3
-  Allow support for copy\_theme argument in CFG files (#139) (syscomet)
-  Improve MathJax rendering for Markdown files
-  Support math output (#144) (davidedelvento)
-  Allow presenter notes in slides with no heading in RST files (#141)
   (regebro)
-  And more...

Landslide v1.1.1
================

Fixes
-----

-  Don't accidentally require watchdog (#134)

Landslide v1.1.0
================

Major Enhancements
------------------

-  Add CHANGELOG
-  Add "ribbon" theme from "shower" presentation tool (#129) (durden)
-  Add ``-w`` flag for watching/auto-regenerating slideshow (#71, #120)
   (jondkoon)

Minor Enhancements
------------------

-  Supress ReST rendering errors
-  CSS pre enhancements (#91) (roktas)
-  Add an example using presenter notes (#106) (netantho)
-  Run macros on headers also, to embed images (#74) (godfat)
-  Allow PHP code snippets to not require <?php (#127) (akrabat)
-  Allow for line numbers and emphasis with reStructuredText (#97)
   (copelco)
-  Add an option to strip presenter notes from output (#107) (aaugustin)

Fixes
-----

-  Firefox offset bug on next slide (#73)
-  Fix base64 encoding issue (#109) (ackdesha)
-  Fix to embed images defined in CSS (#126) (akrabat)
-  Minor documentation fixes (#119, #131) (durden, spin6lock)
-  Use configured encoding when reading all embedded files (#125)
   (iguananaut)
-  Allow pygments lexer names that include special characters (#123)
   (shreyankg)