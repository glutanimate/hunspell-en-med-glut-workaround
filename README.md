## README for hunspell-en-med-glut-workaround


###Overview

    Description:        en_US English hunspell dictionary modified to include hunspell-en-med-glut
    Terms:              150728
    Author:             Glutanimate (https://github.com/Glutanimate)
    Original Authors:   Hunspell Project,
                        R. Robinson <info@e-medtools.com>, 
                        Rajasekharan N. <https://plus.google.com/u/0/+Rajasekharan-N/>
    Sources:            - hunspell-en-us (20070829)
                        - hunspell-en-med-glut (20140410)
    License:            GNU GPL v3 (see LICENSE for more information)


###Description

This project hosts hunspell dictionary files based on hunspell-en-us and hunspell-en-med-glut. It is a temporary workaround to the various issues surrounding the use of add-on hunspell dictionaries with LibreOffice and OpenOffice (1).


###Installation

    git clone https://github.com/Glutanimate/hunspell-en-med-glut-workaround.git
    cd hunspell-en-med-glut-workaround
    sudo cp en_US.dic '/usr/share/hunspell/en_US.dic'
    sudo cp en_US.aff '/usr/share/hunspell/en_US.aff'

###Restoring the original dictionaries

**Ubuntu/Debian**

    sudo apt-get install --reinstall hunspell-en-us

###Warranty

This software comes with no warranty of any kind. Some misspelled words might be included.

###Sources

(1): https://bugs.launchpad.net/ubuntu/+source/language-support-extra-de/+bug/363619, https://bugs.launchpad.net/ubuntu/+source/openoffice.org/+bug/329968 and https://bugs.launchpad.net/medicalterms/+bug/401423
