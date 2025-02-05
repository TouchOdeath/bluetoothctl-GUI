# About:
This provides a GUI where you can choose which Bluetooth devices you want to connect to using bluetoothctl.

Bluetooth in Linux can sometimes be finicky, this can make it work like its suppose to.  This is for people who have a hard time with getting your bluetooth devices connected.  You have to do a lot manual labor to get things to work.  A lot of times in Linux, you can get your devices connected by simply restarting bluetooth, send a connect command to the devices and bam your ready to go.

Note:  If you have a mouse, sometimes you have to press 'Left-Click' to initiate a connection.

# Usage:

1.  Requires bluetoothctl and zenity (type 'bluetoothctl' or 'zenity' in terminal to see if they are installed).  If not install manually:
 
    apt install zenity
    
    apt install bluez
  
3.  Download BTConnect.sh
4.  If you have an equalizer, uncomment and edit '<equalizername\>' and '<equalizerexec\>' below:

 #Restart Equalizer-------------------------------------
 
  #pkill <equalizername\>
  
  #nohup <equalizerexec\> > /dev/null 2>&1 & disown

 #Restart Equalizer-------------------------------------

 
4.  Download BluetoothConnect.desktop and edit 'Exec=' and 'Icon='
5.  chmod +x desktop && chmod +x BTConnect.sh
6.  Done.
