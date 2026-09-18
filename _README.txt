APP Volunteer Support — Walking Maps
Alberta Prosperity Project
Copyright 2026 Enigmatic Productions

WHAT THIS IS
A simple browser tool for volunteers. You pick a Calgary riding,
click a poll, and print a letter-size walking map.

WHAT MUST BE IN THE SAME FOLDER
  overlay.html
  app_logo.png
  CR_ridings.geojson
  CR_polls.geojson
  start_walking_maps.bat
  start_walking_maps.ps1
  start_walking_maps.command
  start_walking_maps.sh
  README.txt

The street map needs an internet connection (OpenStreetMap).
Keep the small "OpenStreetMap" credit on the map. Do not remove it.

--------------------------------
WINDOWS
1. Unzip the folder. Do not scatter the files.
2. Double-click start_walking_maps.bat
3. If Windows asks about PowerShell, choose Run.
4. Your browser should open the app.
5. Leave the black window open while you work.
6. Close that window when you are finished.

You do not need Python. You do need a current browser
(Chrome or Edge).

If the page opens but the ridings do not appear, use
"Replace ridings file" and "Replace polls file" once.
After that, this computer remembers the files.

--------------------------------
MAC
1. Unzip the folder.
2. Right-click start_walking_maps.command
3. Choose Open. If macOS blocks it, go to
   System Settings > Privacy & Security > Open Anyway.
4. Leave the Terminal window open while you work.

If the starter cannot run a local page server, it will
open the HTML file instead. Then use
"Replace ridings file" and "Replace polls file" once.

--------------------------------
LINUX
1. Unzip the folder.
2. Open a terminal in that folder.
3. Run:  chmod +x start_walking_maps.sh
4. Run:  ./start_walking_maps.sh
5. Leave the terminal open while you work.

The Linux starter uses Python only if it is already
installed. If it is not, open overlay.html in Firefox
or Chrome and load the two GeoJSON files once.

--------------------------------
HOW TO USE THE APP
1. Wait a few seconds for the splash screen.
2. The first view shows only ridings.
3. Click one riding (or tick it in the list).
4. Click a poll on the map.
5. Choose Create walking map.
6. Use Print. Paper = Letter. Match portrait or landscape
   to the on-screen sheet. Scale = 100%.
   Turn off headers and footers if you see them.

--------------------------------
LOGO
The logo is now stored inside overlay.html, so the splash
and header should show it even if app_logo.png is missing.

If you still do not see it:
- Keep overlay.html and app_logo.png in the same folder.
- Use the starter (.bat / .command / .sh) instead of
  dragging the HTML file from a different folder.
- Refresh the page (Ctrl+R or Cmd+R).
- Try Chrome or Edge.

--------------------------------
BRANDING AND SHARING
You may brand and share this folder with volunteers.
Do not remove the OpenStreetMap credit.
The riding and poll shapes come from your GeoJSON export.
Each computer keeps its own copy. This is not a live
shared database.
