Modified Notification Cards
Original Creator on V3rmillion here: https://v3rmillion.net/showthread.php?tid=1165214
Turned it to dark mode because
Personally I like it more.

Example Script:
local Notification = loadstring(game:HttpGet("https://raw.githubusercontent.com/deterlua/scripts/mainscript/test", true))()

local a = Notification.new("error", "Death Counter", "AverageSYXUser.") -- Args(<string> Type, <string> Heading, <string> Body, <boolean?> AutoRemoveNotif, <number?> AutoRemoveTime, <function?> OnCloseFunction)
local b = Notification.new("success", "Success Heading", "Success body message.") -- Args(<string> Type, <string> Heading, <string> Body, <boolean?> AutoRemoveNotif, <number?> AutoRemoveTime, <function?> OnCloseFunction)
local c = Notification.new("info", "Information Heading", "Information body message.") -- Args(<string> Type, <string> Heading, <string> Body, <boolean?> AutoRemoveNotif, <number?> AutoRemoveTime, <function?> OnCloseFunction)
local d = Notification.new("warning", "Warning Heading", "Warning body message.") -- Args(<string> Type, <string> Heading, <string> Body, <boolean?> AutoRemoveNotif, <number?> AutoRemoveTime, <function?> OnCloseFunction)
local e = Notification.new("message", "Message Heading", "Message body message.") -- Args(<string> Type, <string> Heading, <string> Body, <boolean?> AutoRemoveNotif, <number?> AutoRemoveTime, <function?> OnCloseFunction)
a:deleteTimeout(10)
b:deleteTimeout(10)
c:deleteTimeout(10)
d:deleteTimeout(10)
e:deleteTimeout(10)
