Sharpfin Radio Base

Patch: sharpfin-base
Version: 0.3
Date: 12th January 2008
Readme Version: $Id: readme.txt 250 2008-01-17 00:11:04Z  $

These files are the base installation required for the sharpfin radio

Now you need to re-configure your radio to use this machine as its DNS server.
Then perform an upgrade on the radio.

You will see the following on the Radio display:
Upgrading Radio         (The patchfile is being transferred to the radio)
Patching Starting	(Sharpfin patch script has just been launched)
Patching Sharpfin Base  (Sharpfin Base files are being installed)
Patching Telnet Server  (Telnet server configuration files are being installed)
Patching Web Server     (Web server configuration files are being installed)
Patching Web Files      (Web server files are being installed)
Patching Done Rebooting (Disk is write-protected again, and radio is rebooting)

Once the patching is complete, your radio will reboot.
You should then be able to connect to the radio using a web browser.
The Telnet server creates two accounts: admin (password admin) and user (password user).
It is recommended that you login as the user to explore the radio, as the admin account has the same rights as root.
