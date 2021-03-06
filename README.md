Use of DANE to improve security for identity federations
========================================================
This Github project is one of two repositories used for our Bachelor Thesis work.
This repository (BachelorThesis) has our report in LaTeX as well as some installation and configuration instructions for the different software we have used. The other github project (shibIdPextension) has our DANE implementation for the Shibboleth Identity Provider.

### Our thesis and installation/configuration instructions
* https://github.com/sopber-8/BachelorThesis
* https://github.com/christofferholmstedt/BachelorThesis

To get our report in a readable PDF we have used "pdflatex" on Ubuntu 11.10 and 12.04. It should be enough to download and install package "texlive".
Be aware this "texlive" package is big so it might take some time to install. (Test installation on clean 12.04 virtual machine the 24th of may 2012 required download 240MB of archives and it would take 414MB extra disk space after installation.)

    # Instructions for Ubuntu 11.10 and Ubuntu 12.04 LTS

    # Clone this repository
    git clone git://github.com/christofferholmstedt/BachelorThesis.git

    # Install LaTeX and "pdflatex"
    sudo apt-get update
    sudo apt-get install texlive

    # Change directory to our "thesis"-directory
    cd /path/to/project/directory/thesis

    # Generate our report
    pdflatex thesis.tex
    bibtex thesis.aux
    pdflatex thesis.tex
    pdflatex thesis.tex

(These steps were tested on a virtual machine of Ubuntu 12.04 LTS the 24th of May 2012)

### Our DANE implementation
The DANE implementation in the Shibboleth Identity Provider is as of the 21th of May 2012 still work in progress. For the latest details about the implementation please visit the project.

* https://github.com/sopber-8/shibIdPextension
* https://github.com/christofferholmstedt/shibIdPextension

### Best regards
Sophia Bergendahl and Christoffer Holmstedt, May 2012

