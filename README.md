# bluetoothctl-GUI
This provides a GUI where you can choose which Bluetooth devices you want to connect to using bluetoothctl.  Its a make-shift bluetooth manager.

Bluetooth in Linux can sometimes be finicky, this can make it work like its suppose to.  This is for people who have a hard time with getting your bluetooth devices connected.  You have to do a lot manual labor to get things to work.  A lot of times in Linux, you can get your devices connected by simply restarting bluetooth, send a connect command to the devices and bam your ready to go.

Note:  If you have a mouse, sometimes you have to press 'Left-Click' to initiate a connection.

# Usage:

1.  Download BTConnect.sh
2.  If you have an equalizer, uncomment and edit '<equalizername\>' and '<equalizerexec\>' below:

 #Restart Equalizer-------------------------------------
 
  #pkill <equalizername\>
  
  #nohup <equalizerexec\> > /dev/null 2>&1 & disown

 #Restart Equalizer-------------------------------------

 
3.  Download BluetoothConnect.desktop and edit 'Exec=' and 'Icon='
4.  chmod +x desktop && chmod +x BTConnect.sh
5.  Done.
