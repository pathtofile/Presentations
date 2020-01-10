# Pip install Exfil - Data Exfiltration and C2 using public package repositories

## Overview
Presentation given at CSides October 2018 on using public repos for C2

Developers regularly use public repositories to install 3rd party libraries, from OS-specific repos like the Arch User Repository to language-specific repos like Python's PyPi, to public sourcecode repos like Github. The majority of requests to these systems are under SSL, to known, trusted, public servers, and request would not look out of place coming from a company build server or a developer's workstation.
This talk will present a novel example of using Python's official PyPi repo to create a command-and-control and data exfiltration channel. It will then cover analysis of other common public repositories; detailing protections they have in place to prevent similar malicious usage.

