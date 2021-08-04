# pip install exfil: Data exfiltration and C2 using Python PyPI
Presentation given at the `CSides Monthly` Security meetup in October 2018.

## Abstract
Developers regularly use public repositories to install 3rd party libraries, from OS-specific repos like the Arch User Repository to language-specific repos like Python's PyPi, to public sourcecode repos like Github. The majority of requests to these systems are under SSL, to known, trusted, public servers, and request would not look out of place coming from a software build server or a developer's workstation.

This talk will present a novel example of using Python's official PyPi repo to create a command-and-control and data exfiltration channel. It will then cover analysis of other common public repositories; detailing protections in place to prevent similar malicious usage.

## Slides
[https://github.com/pathtofile/Presentations/blob/master/2018_csides/path_pip_install_exfil.pdf](https://github.com/pathtofile/Presentations/blob/master/2018_csides/path_pip_install_exfil.pdf)
