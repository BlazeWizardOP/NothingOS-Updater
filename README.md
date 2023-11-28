# NothingOS Firmware Project

<!-- ############################# -->
<!-- Start Segment 01 Of README.MD -->
<!-- ############################# -->

<!-- Preview NothingOS Updater Project Logo -->
<img align="right" width="30%" src="https://github.com/BlazeWizardOP/NothingOS-Updater/assets/134801431/3d007587-00cb-4d96-973f-de90ba205547">

### Important Notice:
- Our Project Is Open-Sourced, Possible Due To All Testers & Contributers. Thanks For Making This Project Possible!
- Please Read All Project Changelogs & Features Before Flashing Our Stuff!
- Join Our Support Groups For Better Experience, Proper Flashing Guides & Faster Updates
- Our Updates System Is Limited For Certain Device(s) Only, We Will Be Needing Audience & Developers Support To Provide Support For Other Devices Too!

### Project Contributer(s):
- [BlazeWizardOP](https://t.me/blazewizardop)
- [PhatWalrus](https://t.me/PhatWalrus)
- [HellBoy017](https://t.me/HellBoy017)
- [Spike0en](https://t.me/Spike0en)
- [Ali Shahawez](https://t.me/techticks)
- Pong Development Group

### Our Group Link(s):
- [NothingOS Updater Channel](https://t.me/NothingOSUpdater)
- [Nothing Phone (2) Updates](https://t.me/NothingPhone2updates)
- [Nothing Phone (2) Global Support](https://t.me/NothingPhone2)
- [NothingOS Phone (2) India Support](https://t.me/NothingPhone2_IN)

### Current Supported Device(s):
- Nothing Phone (2) | PONG

<!-- ############################# -->
<!-- Start Segment 02 Of README.MD -->
<!-- ############################# -->

## NothingOS Updater Features:
- We Have Made Flashing Better & More Easier To Access Onto.
- Provided Unified Flashing Packages On All Variants Global | India | EEA
- Simultaneous Features Been Developed To Make Recovery Flashing More Easier
```
  [1] RapidFlasher™:
      Flashing Should Complete Within 2 Minutes Now!
  [2] PartitionFlasher™:
      Now Users Can Modify The Images They Want To Flash By Modifying Flashing Binary! More Information In Project Documentation Segment
      (Feature Recommended To Used By Advanced Users Only!) 
  [3] SlotFlasher™:
      Now Users Can Directly Modify To Which Slot They Want To Flash Package On!
  [4] SlotNotifier™:
      (EXAMPLE:)
      (user slot active: _a) (flashing to slot _b)
      This Feature Will Notify User Automatically After Flash Is Complete To Switch To Slot They Flashed OTA On!
  [5] DeviceDetector™:
      The Flash Will Only Proceed If The Device Has Been Detected As Pong / PongIND / Pong EEA Variants.
  [6] AdvancedLogger™:
      Flashing Logs Will Be Saved In Internal Storage Automatically Once The Flash Ends With/out Error.
      Head to: /InternalStorage/NothingOSUpdater.log
      Logs will automatically detect if the flash was not successfull with appropriate reason(s).
      Logs will automatically detect NothingOS Version being flashed.
      Logs will automatically detect is user advanced or normal.
      Logs will automatically detect the partitions opted for flashing
      Logs will automatically note down partitions been flashed to device
      Logs will automatically detect flashing and active slots.
- Made Binaries More Compact And Better.
- Improved Filing Structures.
```
- Simultaneous Features Been Developed To Make Fastboot Flashing More Easier
```
[1] Modified @HellBoy017's Fastboot Flasher Script.
[2] Fixed ImagesDirectory Detection For Flashing
[3] Removed support of .log file, as it was crashing flashing script
[4] Added Our Own Goodies...
```

<!-- ############################# -->
<!-- Start Segment 03 Of README.MD -->
<!-- ############################# -->

## NothingOS Updater Documentation:

### Package Schema:
- [AIO] {All-In-One | Package That Contains Fastboot & Recovery Flashing Support Both!}
- [R] {Recovery | Package That Contains Only Support Of Recovery Flashing Support!}
- [F] {Fastboot | Package That Contains Only Support Of Fastboot Flashing Support!} 

### Changelogs:
- All The Changelogs Can Be Found On Our Releases Page.
- Changelogs Are Divided Properly For Fastboot & Recovery.

### How To Use NothingOS Updater Flashing Features:
- These Features Are Effective Only If You Flash Via Recovery!
- These Features Are Only Insisted To Use For Advanced Users!
- Head To package.zip/META_INF/com/google/android/update-binary File, Scroll Down You Will Find Proper Guide How To Modify Flashing Slots & Flashing Images.

### How To Use Our Package:
- You Can Follow Below Tutorial Or See This [Youtube Tutorial](https://www.youtube.com) For Better Visual Guides!

### Guide For Recovery Flashing:
- Download Our Package, We Recommend To Download [AIO] Package.
- Just Flash The Recovery Package. If There Is Any Need To Switch Slot You Will Be Notified While Flashing.
- Change Your Current Active Slot Via Toggling In Recovery.
- Reboot & Enjoy! Dive Into NothingOS :)

### Guide For Fastboot Flashing:
- Download Our Package, We Recommend To Download [AIO] Package.
- Unzip The Package.
- Head To Folder NothingOS --> NothingOSUpdater_Fastboot
- Run The Batch (.bat) File Present In This Folder As Administrator Via Windows Powershell.
- Plug In Your Device With Laptop/Desktop In Fastboot Mode.
- Once Flash Is Done Device Will Reboot Automatically! :)

### Thanks For Trying Our Stuff!!
