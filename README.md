# How to connect Macbook and Switches

    1) Open terminal to list devices
        ls /dev/cu.usbserial-*

    2) Connect to the switch 
       
       For switches HPE use baud rate 9600

        screen /dev/xx.usbserial-xxxxxxx 9600 -L

            Ex.: screen /dev/cu.usbserial-110 9600 -L
            

        For switches 3COM use baud rate 19200 bps:

        screen /dev/xx.usbserial-xxxxxxx 19200 -L

            Ex.: screen /dev/cu.usbserial-110 19200 -L