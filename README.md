# bluetoothctl-GUI
Bluetooth in Linux can sometimes be finicky, this can make it work like its suppose to

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
