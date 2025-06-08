> [!NOTE]
> If (New Library) is added in a notification library name, that means it was just added here. More librarys are coming soon!
# All Lua Notification Libraries I Use

# Nameless Admin Notification Library
Code for loading the library:
```lua
local Notification = loadstring(game:HttpGet("https://raw.githubusercontent.com/FilteringEnabled/FE/main/notificationtest"))();
local Notify = Notification.Notify;
```
How to make a notification with Nameless Admin Notification Library:
```lua
Notify({
		 Description = "Example Description";
		 Title = "Example Title";
		 Duration = Duration;
		 
});
```
# Hoho Hub Notification Library
Code for loading the library:
```lua
local notify = loadstring(game:HttpGet("https://raw.githubusercontent.com/acsu123/HOHO_H/main/Notification.lua"))()
```
How to make a notification with Hoho Hub Notification Library:
```lua
notify.New("Example Content", Duration) 
```
# (New Library) Notification Library (by IceMinisterq on GitHub)
Code for loading the library:
```lua
local NotificationLibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMinisterq/Notification-Library/Main/Library.lua"))()
```
How to make a notification with 
Notification Library:
```lua
NotificationLibrary:SendNotification("Theme", "Example Message", Duration)
```
Themes:
Success
Warning
Error
Info
