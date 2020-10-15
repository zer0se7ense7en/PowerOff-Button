# PowerOff-Button
A Button to shutdown the Raspberry Pi smoothly

##################################################

Hardware Setup:

  Connect a momentary Button to GPIO 21 and GND

##################################################

Software Setup:

  type 'sudo nano /etc/rc.local'
  add 'python /home/pi/PowerOff-Button/shutdown.py &' before exit 0

  save 'shutdown.py' in your home directory
  make it executable by typing 'chmod +x shutdown.py'

  reboot
