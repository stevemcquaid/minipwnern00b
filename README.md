# minipwnern00b
Setup scripts for minipwner. Automate all the things!

## Playbook 1 - Partion USB Drive
Setup two partitions on the USB drive. Detect user's OS and issue correct command (Linux, [Mac]). Interactive prompt for variables.

## Playbook 2 - Install OpenWRT
- Download Firmware
- curl Necessary endpoints to hack the GUI. (submit forms and navigate menus)

## Playbook 3 - Configure
#### Step 1 - Connect device to internet
Interactive prompt to accomplish this. So many edge cases to lookout for.

#### Step 2 - Telnet to device
- Interactive prompt to allow user to set root password.
- Setup pubkey auth if applicable.

#### Step 3 - Test Connectivity to internet
ping a server.

#### Step 4 - Install Packages
opkg install all the things

#### Step 5 - Wait for USB & reboot
Detect usb and reboot immediately.

#### Step 6 - Modify fstab 
Reconnect & Modify fstab according to template.

#### Step 7 - Pivot root
Run the commands & recover if there are common issues

#### Step 8 - Modify fstab to boot from USB
Modify fstab according to template & reboot

#### Step 9 - Verify correctness
df -h | grep 'verify all the things'

#### Step 10 - Success & much win

#### Step 13 - Upload MiniPwner Overlay tar 
scp to /tmp

#### Step 14 - Untar & move.

#### Step 15 - Run setup script
sh setup.sh

#### Step 16 - WISP & Reboot
Detect when switch is in WISP position & reboot.


## Playbook 4 - A La Carte Attacks 
- Setup Minimodes
- Allow other modules to be added individually via running a specific playbook.
- Allow config with Pineapple with user input vars (ansible for wifi pineapple?)
- Anything else we can think of.
