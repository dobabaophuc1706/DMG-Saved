[DMG Saved](https://github.com/dobabaophuc1706/DMG-Saved)
=============
<p align="center"> 
 <img src="https://raw.githubusercontent.com/dobabaophuc1706/dobabaophuc1706/main/README/Avt.png" alt="Avt" width="Avt" height="200"/> 
  <p/> 

<h3 align="left">DMG files for my used</h3>

<h3 align="left">Support</h3>
- MacOS 10.15 -> MacOS 14

> [!CAUTION]
> Disable SIP or Gatekeeper if they don't work!

<h3 align="left">How to disable Gatekeeper</h3>

- Open **Terminal**

- Type
```
sudo spctl --master-disable
```

<h3 align="left">How to disable System Integrity Protection (SIP)</h3>

- Install Recovery mode

Mac Intel
> **Reboot** then hold **Command + R**

Mac Silicon
> **Shut down** then hold power button

> Hold and wait for **Startup Options** screen

> Choose **Option**, hit **Enter**

> Login to your Mac

- Access **Utilities** -> **Terminal**

- Type this command then hit **Y** 
```
csrutil disable
```

- Type
```
reboot
```
<h3 align="left">How to enable System Integrity Protection (SIP)</h3>

- Type this command then hit **Y** 
```
csrutil enable
```
