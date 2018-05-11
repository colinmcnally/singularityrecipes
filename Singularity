Bootstrap:docker
From:ubuntu:bionic

%post
    apt-get update -qq
    apt-get install wget software-properties-common apt-transport-https -y 
    apt-get install dvipng -y
    apt-get install less -y
    apt-get install ipython3 -y
    apt-get install ipython3-qtconsole -y
    apt-get install python3-matplotlib -y
    apt-get install python3-h5py -y
    apt-get install python3-numpy -y
    apt-get install python3-scipy -y
    apt-get install python3-pandas -y
    apt-get install python3-pip -y
    apt-get install texlive-latex-base -y
    apt-get install texlive-latex-extra -y
    apt-get install htop -y
    apt-get install git -y

# vmtouch requires root.
#    add-apt-repository ppa:likemartinma/devel
#    apt-get update
#    apt-get install vmtouch -y
    apt-get install vim -y

    pip install plotly

    # build the font cache
    python3 -c "import matplotlib.pyplot"

%runscript

    exec echo "runscript is empty "
