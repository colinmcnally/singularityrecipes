Bootstrap:docker
From:ubuntu:latest

%post
    apt-get update -qq
    apt-get install wget software-properties-common apt-transport-https -y 
    apt-get install less -y
    apt-get install ipython3 -y
    apt-get install ipython3-qtconsole -y
    apt-get install python3-matplotlib -y
    apt-get install python3-h5py -y
    apt-get install python3-numpy -y
    apt-get install python3-scipy -y
    apt-get install texlive-latex-base -y
    apt-get install texlive-latex-extra -y
    apt-get install dvipng -y

    # build the font cache
    python3 -c "import matplotlib"

%runscript

    exec echo "runscript is empty"
