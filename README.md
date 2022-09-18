
# Path of Exile macOS logout macro

Since AutoHotkey macros are not working on macOS (and I'm dedicated SSFHC player) I've decided to make one on my own.

App may be used to terminate almost any process - when downloaded it's just set to terminate Path of Exile (since it starts in random ports on macOS Steam Client), but You may easly set it up for any other proces.

## Installation

1. Download app killer script file and oopen it using using script editor tool on Your system.

2. In last line of script set
```bash
  osuserpassword
```  
to Your system password.

3. Go to File -> Export and save script as application with 
```bash
  Run-only
```  
setting on.

4. Now there are few ways to make the macro work for You:

- using Your gaming keyboard/mouse set a key to run the app when keybind is used.
- using any app with options to making keybinds like Raycast to create keybind that runs it.

- set a keybind using macOS Automator tool. You need to create an Automator quick action that will run the app on set key. 

Remember that You will probably have to change Your settings to give Automator/Raycast permissions needed to close Path of Exile.

System Preferences > Security > Privacy > Accessibility
## FAQ

#### Is using logout macro against Path of Exile TOS?

TOS allows macros that are activated by user (not automated) and are not performing more than one action per activation. "Logging out" is a single action and is not violating this rules.

Even well-known streamers like Zizaran are using it.
#### Do I need to provide my user password in script?

It's needed because otherwise system will ask for password before terminating POE process, and You probably want it to be instant! :)

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/fbrv01/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/filip-bucholc/)
