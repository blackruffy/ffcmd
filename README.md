# ffcmd
Command line tool for Firefox.

# Setup

* Download zip file from this page.
* Unpack zip file 
* Drag addon/ffcmd.xpi and drop it to your firefox.
* Set PATH environment variable to bin/ffcmd

# Usage

## Tabs

List tabs.

`$ ffcmd tab list`

Show url of active tab.

`$ ffcmd tab current`

Open new tab.

`$ ffcmd tab open [url]`

Select tab.

`$ ffcmd tab select [index]`

Set url of active tab.

`$ ffcmd tab set-url [url]`

Close active tab

`$ ffcmd tab close`

Show state of active tab.

`$ ffcmd tab ready-state`


