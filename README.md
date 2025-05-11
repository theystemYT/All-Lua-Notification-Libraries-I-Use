# Notification Librarys I Use:

# Nameless Admin Notification Library
Code for loading the library:
```lua
local Notification = loadstring(game:HttpGet("https://raw.githubusercontent.com/FilteringEnabled/FE/main/notificationtest"))();
local Notify = Notification.Notify;
```
How to make a notification with Nameless Admin Notification Library:
```lua
Notify({
		 Description = "Notification Content";
		 Title = "Notification Title";
		 Duration = 5;
		 
});
```
Completed code for people that can't do so:
```lua
local Notification = loadstring(game:HttpGet("https://raw.githubusercontent.com/FilteringEnabled/FE/main/notificationtest"))();
local Notify = Notification.Notify;

Notify({
		 Description = "Notification Content";
		 Title = "Notification Title";
		 Duration = 5;
		 
});
```
# Hoho Hub Notification Library
Code for loading the library:
```lua
local notify = loadstring(game:HttpGet("https://raw.githubusercontent.com/acsu123/HOHO_H/main/Notification.lua"))()
```
How to make a notification with Hoho Hub Notification Library:
```lua
notify.New("Notification Content", 30) 
```
Completed code for people can't do so:
```lua
local notify = loadstring(game:HttpGet("https://raw.githubusercontent.com/acsu123/HOHO_H/main/Notification.lua"))()

notify.New("Notification Content", 30)
```
# (New Library!) Notification Library (by IceMinisterq on GitHub)
Code for loading the library:
```lua
local NotificationLibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMinisterq/Notification-Library/Main/Library.lua"))()
```
How to make a notification with Notification Library:
```lua
--[[
Themes:
Success
Warning
Error
Info
]]
NotificationLibrary:SendNotification
> [!NOTE]
> I was going to include Rayfield's Notification Library, but I was kinda lazy. Also, more librarys are coming soon!
