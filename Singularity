Bootstrap: docker
From: debian:buster

%labels
    AUTHOR icaoberg
    EMAIL icaoberg@alumni.cmu.edu
    WEBSITE http://www.andrew.cmu.edu/~icaoberg
    VERSION 1.10

%post
    apt-get update
    apt-get install -y --no-install-recommends apt-utils bzip2 build-essential libncurses5-dev libncursesw5-dev zlib1g-dev libbz2-dev liblzma-dev
    apt-get update --fix-missing

####################################################################################
%appinstall samtools
    apt-get install -y wget
    wget https://github.com/samtools/samtools/releases/download/1.10/samtools-1.10.tar.bz2
    tar -xjvf samtools-1.10.tar.bz2
    mv samtools-1.10 /opt
    cd /opt/samtools-1.10
    ./configure
    make
    ln -s /opt/samtools-1.10/samtools /usr/local/bin/samtools
    
%apphelp samtools
    samtools --help

%apprun samtools
    samtools "$@"
