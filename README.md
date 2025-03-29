disclaimer: I made this code with AI(I had a lot of compiling issues, that I couldnt resolve, so I used AI (: )

This replaces the normal FM menu, aka you wont be able to use those feutures like: Hijack TA 

Replace the fm.cpp, fm.h in src/core/modules/fm
Replace the FMMenu.cpp, FMMenu.h in /src/core/menu_items
Add Tea5767.h to src/core/modules/fm

Steps to build it and flash it:

Install VS Code
Clone bruce firmware from official github page
Open project in VS Code
Install PlatformIO extension inside VS Code
Open PlatformIO home, select import project if it doesn't show up in project (middle of the screen)
If you alredy replaced the files, then: Select Build in the top right of the screen
If it says Succeed, then Select Upload(top right of the screen)


known issues:
Doesn't display battery percentage correctly: If the tea5767 modules is connected, it always displays 100% for some reason
