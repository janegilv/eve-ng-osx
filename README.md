Downloaded from: https://www.802101.com/unetlab-and-wireshark-for-osx-update/

Modified to only use one terminal window, and hide contents afterwards.

Uses terminal profile called close-on-exit. This must be created manually. Make this profile close on exit.

#### Preparing iterm2 for opening telnet link
* Install telnet with homebrew
* Create new profile called telnet
* Select Command -> Command
* (Must symlink before next step, can change this to homebrew original?)
* Enter "/usr/local/bin/telnet $$HOST$$ $$PORT$$"
* URL Schemes: Schemes handled: select telnet here

#### Making changes to the applescript
This is somehow weird. To make changes:
* Download or unzip file. DO NOT RUN IT YET.
* Open file in apple script editor
* Make your changes. Save, compile, save again
 * Save first might not be necessary
* Run script
* To make new changes. Delete/reset the file and start this process from beginning.
* In Big Sur the applescript file must be added to accessibility in "System Preferences - Security & Privacy - Privacy - Accessibility". This is in order to create tabs in terminal using keyboard command +t.
