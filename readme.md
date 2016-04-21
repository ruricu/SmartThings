# SmartThings

URI Button
Based wholly off of URI Switch by tguerena (https://github.com/tguerena/SmartThings), this URI Button provides a stateless alternative for when you don't have a different command for on or off.

Attached to a stateless Virtual Button, this kicks off a URL (External and/or Internal) when an On/Off/Push command is sent

External calls triggered with a command
-------------------------------------------------

External URI --- ie:  http://www.externalaccess.com/do_Action	

Internal calls triggered with a commands
-------------------------------------------------

Internal IP --- 192.168.1.1

Internal Port (if not 80)        

Internal Path (/blah?q=this) --- /api/HomeAutomation.X10/o1/Control.Off
