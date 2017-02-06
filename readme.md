

Chrome canary for linux

**This scripts auto update chromium for linux to the last version**

*How to use*

 * Clone this repo and open in terminal it's directory
 * Run `chmod +x update_chrome` and `chmod +x chrome`
 * Run `./update_chrome` it will download the last version of chromium to `~/Downloads/programs/linux-chrome.zip` and extract files
 * Then run `./chrome`

 That's it.

 *If you want it to work like a global command*

 * Run `cp chrome /usr/bin` and `cp update_chrome /usr/bin`

 That's it. Now you can start it by just running command `chrome`. Also, when you need the very last version run `update_chrome`

 *If you want absolutely auto update set "update_chrome" to a crontab job*
