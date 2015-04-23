# ffcmd
The command line tool for Firefox.

# Setup

* Download the zip file from this page.
* Unpack the zip file.
* Drag and drop the addon/ffcmd.xpi file to your Firefox.
* Set the PATH environment variable to bin/ffcmd

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
`$ ffcmd js --file=[file] [source code]`  
`$ ffcmd js --type=[text or json] [source code]`  

Examples:  
`ffcmd js "return window.location.href;"`  
`ffcmd js "return findByXPath(document.body, '//span[@class=\"author\"]')[0].textContent"`

