scoutify
========

A hub for all of the different scoutify components.

Configuration/Installation
--------------------------

While a system is being worked out to generate a .zip file of only the necessary files (i.e. compiled binaries, a node-webkit installation), the simplest means to get this to work is to clone the repository yourself (follow the directions below) and compile it for yourself.

    # To download the scoutify compilation.
    git clone git://github.com/team461WBI/scoutify.git
    cd scoutify
    git submodule init
    git submodule update

    # To build scoutify-merger
    cd scoutify-merger
    make    
    cd ..

Yeah.
If you have any suggestions as to how we could improve this or build for Windows (We're using Linux systems primarily), fork and pull-request or just issue.
