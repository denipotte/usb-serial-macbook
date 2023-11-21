# How to connect Macbook and Switches

    1) Open terminal to list devices
        ls /dev/cu.usbserial-*

    2) Connect to the switch
        screen /dev/xx.usbserial-xxxxxxx 9600 -L

            Ex.: screen /dev/cu.usbserial-110 -L
            
