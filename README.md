# Packet-Transmission-LimeMiniSDR
The following repository houses the code for data packet transmission via the LimeMiniSDR Radio Dongle


Hardware Required : Lime Mini / Lime Software Defined Radio
  link : https://limemicro.com/products/boards/limesdr/
  
Software Required : GNU Radio [Windows / Linux]
  link : https://www.gnuradio.org/
  
Packages Required : https://wiki.myriadrf.org/Installing_Lime_Suite_on_Windows
                    https://wiki.myriadrf.org/Installing_Lime_Suite_on_Linux


The flowgraph transmits a text file byte to byte over the input frequency in the Source and Sink block
The Lime Sdr is configured be a transreceiving module that receives the packets through the receiving channel which has been transmitted the transmitting channel on the same dongle.
