https://www.makeuseof.com/windows-view-usb-history/

To see a user-friendly list of the USB storage devices, enter the command:### 
  -  Get-ItemProperty -Path HKLM:\SYSTEM\CurrentControlSet\Enum\USBSTOR\*\* | Select FriendlyName
  -  

