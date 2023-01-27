# Generate-GSM-wave-RF-Transmit
This repository is only hints for the installation
first you just need to use in the Ubuntu,and android

<b> Ubuntu  :</b> 
we use version 18

<b>run this command below to make update and installation</b>

sudo apt-get update && \\
sudo apt-get install -y \\
    cmake \\
    autoconf \\
    libtool \\
    pkg-config \\
    build-essential \\
    python-docutils \\
    libcppunit-dev \\
    swig \\
    doxygen \\
    liblog4cpp5-dev \\
    python-scipy \\
    python-gtk2 \\
    gnuradio-dev \\
    gr-osmosdr \\
    libosmocore-dev


<b> for Android </b>

1. you need to install the RTL SDR driver: <br>
https://play.google.com/store/apps/details?id=marto.rtl_tcp_andro&hl=en&gl=US

2. you need to install RTL SDR driver <br>
you need to install: https://play.google.com/store/apps/details?id=com.mantz_it.rfanalyzer&hl=en&gl=US&pli=1

How to use for Android: <br>
1. plug the SDR with OTG adaptor depend to your android mobile is Type C or Micro USB <br>
2. run the sdr driver (or sometimes run automatically)
3. run the RF analyzer, then set the frequency that you want to analyze


