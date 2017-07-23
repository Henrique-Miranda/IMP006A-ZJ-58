# IMP006A Zj-58
IMP006A Zj-58 POS Bluetooth Printer Linux Driver

If you only whant use this printer with usb cable just install driver using: sudo chmod +x install58
And next: sudo ./install58

This is how to configure IMP006A or Zj-58 Bluetooth printer on linux by Bluetooth conection.

# 1 
  Install cups
# 2 
  Install bluez-cups(This allow cups to use bluetooth protocol)
# 3 
  Sync the bluetooth printer with your computer, use password 1234 or 0000
# 4
  Take a note on bluetooth adress of printer e.g: 0f:08:09:07:0b:08
# 5
  Open http://localhost:631/admin and go to add printer
# 6
  Put your root credentials
# 7
  Select LPD/LPR Host or Printer
# 8
  In URI put bluetooth://0f0809070b08 where "0f0809070b08" is your bluetooth printer adress
# 9
  Select POS58.ppd File and click ADD Printer


# Cups link:
  https://github.com/apple/cups/releases

# Bluez-cups links:
  https://packages.debian.org/sid/admin/bluez-cups
  
  https://www.archlinux.org/packages/extra/x86_64/bluez-cups/
