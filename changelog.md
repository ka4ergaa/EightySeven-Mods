## 2.0.12 (28.12.22)

- Improved back button: now the "Back" button opens not just the modifications form, but opens the previous form (even if it is a modification page) with saving scrolling progress
- More translation

## 2.0.11 (26.12.22)

- Now the state of the MySQL server is obtained from the site
- Changed MySQL server

## 2.0.10 (25.12.22)

- Changed the way to check the first run, to display the first run window

## 2.0.9 (25.12.22)

- Fixed a bug when scrolling everything went back to the top
- Removed the "Switch to English" button, because the language is set automatically
- Start window on first launch

## 2.0.8 (22.12.22)

- Fixed a bug when when entering the graphics section, the selected shader was set to Sildurs Vibrant, and not SEUS Renewed
- Ability to disable connection to MySQL (only for developers)
- Issuing an error connecting to the server, when crashing due to the database
- Display news in selected language (enabled on restart)
- More render logs

## 2.0.7 (17.12.22)

- Disabled display of the welcome window on first launch
- Fixed a bug when the application could not connect to the server
- Now BUG HUNTER version is issued through the database, not Discord
- The "Retry" button on the window with an error connecting to the server
- Fixed a bug when the application crashed when trying to copy an error
- Restarting the application after logging out of the account (previously it was just closing)
- Fixed a bug when when resetting the application, it was completely deleted
- An item in the settings that allows you to disable Core checks for mod compatibility
- Warning that the application will be restarted/closed when logging out of the account, changing the root folder of the game, deleting all mods and resetting the application
- Added translation for build information (name and version)

## 2.0.6 (10.12.22)

- Getting file data of Updater from url

## 2.0.5 (09.12.22)

- Updated File Updater
- Updated installer file

## 2.0.4 (03.12.22)

- Fixed a bug when a line was accidentally skipped in the logs
- Fixed a bug where another line was not created in the Updater
- Now when updating, a copy of the program will not be created on the C drive (this was not used in any way)

## 2.0.3 (03.12.22)

- Fixed a bug when, for any news other than the first one, switch the category, the first one started to be displayed, and not the one needed

## 2.0.2 (02.12.22)

- Removed forgotten MessageBox from optimization section
- Fixed bugs when download percentages could not be set

## 2.0.1 (01.12.22)

- Fixed a bug where after 10 minutes of being in the application, it could not reconnect to Discord

## 2.0.0 (01.12.22)

- Fix rendering error when exiting a section while it is running
- Removed the display of the section in Rich Presence
- Improved crash reporting system
- Creation of a crash report on a crash, anywhere
- Progress bar when loading a mod in the taskbar
- Error when connecting to the server in the taskbar (glows red)
- Fix bug when trying to delete a non-existent value in the registry
- Now the date of registration is recorded in Moscow time, and not in local
- Select a category on the main
- Removed small pictures in Rich Presence
- Displaying download percentages on the mod install button
- Updated mod loading picture
- Asynchronous loading of mod pictures
- Reduced delay between switching news (from 30 to 15 sec.)
- Increased the Y coordinate of the buttons and text on the mod page
- Fix bug when installing Fabric in Core
- Mod compatibility check
- Language setting, at the first start, will automatically be in Russian, if the system language is set to the CIS countries (more than the number of them)
- Assembly section
- Selecting the path to the game folder through the file dialog
- The function in the settings for auto-selecting the version when installing the mod
- Fix bugs when installing mods
- Recording the time of the last entry into the program
- Window that opens on first login
- Changed image of EightySeven Core
- Fixed bug when Fabric API was not downloaded
- Storing user information in a database
- Authorization via Discord
- Improved the right panel in the optimization section
- Choice of versions for mods
- Changing the window for selecting presets and versions of mods (window shape, custom close button removed)
- Changed graphics section
- Creating desktop shortcut in Settings

## 1.4.3 (21.09.22)

- Catching errors and writing them to the logs

## 1.4.2 (18.09.22)

- Fixed a bug when the program tried to delete itself

## 1.4.1 (18.09.22)

- Fixed a bug where it was possible to resize the deprecation window
- Changed the size of the deprecation window

## 1.4.0 (18.09.22)

- Possibility of deprecation of versions
- Application installer
- After installation or update, a shortcut is created on the desktop
- The application is automatically added to all Windows applications, which allows you to quickly find it in the search
- The executable file has been moved to the root folder
- Installation via the auto-installer has become mandatory
- Removed text "Choose a shader" in the graphics section
- Added "Open Gallery" button, which opens a site with shader screenshots

## 1.3.3 (16.09.22)

- Added check for network connection

## 1.3.2 (13.09.22)

- Improved mod scrolling system
- Added category "Other"

## 1.3.1 (11.09.22)

- Hidden scrollbar in mods section
- Update check frequency changed to 10 minutes
- Increased spacing between mods in the mods section
- Fixed a bug with a thin strip at the bottom under the modifications of the optimization section

## 1.3.0 (11.09.22)

- Added a button to download the update, it will appear if an update appears on the site within 20 minutes
- Fixed a bug when the "Apply" and "Reset" buttons could change their position
- Growth display has been changed back to "FPS" for better accuracy

## 1.2.11 (10.09.22)

- Added FPS suffix in optimization section

## 1.2.10 (10.09.22)

- Fixed a bug where FPS was still displayed instead of percentages
- Fixed a bug where FPS in the optimization section dropped twice

## 1.2.9 (10.09.22)

- Added localization of optimization mod names
- Changed the way the effect of modifications is displayed, instead of FPS ??? percentages

## 1.2.8 (10.09.22)

- Fixed a bug when installing EightySeven Core, when progress stopped in place
