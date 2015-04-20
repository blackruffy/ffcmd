# ffcmd
Command line tool for Firefox.

# Setup

* Download zip file from this page.
* Unpack zip file 
* Drag addon/ffcmd.xpi and drop it to your firefox.
* Set PATH environment variable to bin/ffcmd

# Usage

Show list of tabs.

`$ ffcmd tab list`

Show url of active tab.

`$ ffcmd tab current`

Open new tab.

`$ ffcmd tab open [URL]`

Select tab.

`$ ffcmd tab select [index]`

Set url of active tab.

`$ ffcmd tab set-url [URL]`

Close active tab

`$ ffcmd tab close`

Show state of active tab.

`$ ffcmd tab ready-state`

Show list of windows.

`$ ffcmd window list`

Show active window.

`$ ffcmd window current`

Open new window.

`$ ffcmd window open [URL]`

Select window.

`$ ffcmd window select [index]`

Close active window

`$ ffcmd window close`

Evaluate JavaScript in the active tab.

`$ ffcmd js [source code]`

`$ ffcmd js --file [file]`

