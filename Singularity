Bootstrap:docker
From:ubuntu:bionic

%post
    apt-get update -qq
    apt-get install wget software-properties-common apt-transport-https -y 
    apt-get install libosmesa6 -y
    apt-get install libglu1-mesa -y
    apt-get install dvipng -y
    apt-get install less -y
    apt-get install ipython3 -y
    apt-get install ipython3-qtconsole -y
    apt-get install python3-matplotlib -y
    apt-get install python3-h5py -y
    apt-get install python3-numpy -y
    apt-get install python3-mpi4py -y
    apt-get install python3-scipy -y
    apt-get install python3-pandas -y
    apt-get install python3-seaborn -y
    apt-get install python3-pip -y
    apt-get install texlive-latex-base -y
    apt-get install texlive-latex-extra -y
    apt-get install htop -y
    apt-get install git -y
    apt-get install mercurial -y
    apt-get install firefox -y
    apt-get install x2goserver -y


# vmtouch requires root.
#    add-apt-repository ppa:likemartinma/devel
#    apt-get update
#    apt-get install vmtouch -y
    apt-get install vim -y

# these might not work in latest version
#    pip3 install plotly
#    pip3 install latexcodec

    # build the font cache
    python3 -c "import matplotlib.pyplot"
    
    git clone https://colinmcnally@bitbucket.org/colinmcnally/pyevtk
    cd pyevtk
    python3 setup.py install

%runscript

    exec echo "runscript is empty "
