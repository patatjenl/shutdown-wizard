# Shutdown Wizard

Shutdown or hibernate your machine in a certain amount of time.

Currently, only Windows is supported.


## How it works

It's a two-step process. In the first step, you choose to either shutdown or hibernate your machine by pressing either the `S` or `H` key. Step two is the time to wait, in hours.

Once countdown has started, it'll display the time left and the action.


## Installing

First, clone the repository to a folder on your machine.
```
https://github.com/patatjenl/shutdown-wizard.git
```

Secondly, create the launcher.
- Right-click the file, choose `Create shortcut`

Optional: If your account isn't an administrator:
- Right-click the shortcut, choose `Properties`
- Click the `Advanced...` button
- Check the `Run as administrator` checkbox
- Click the `Ok` button for both opened screens

Optional: Choose a cool icon
- Right-click the shortcut, choose `Properties`
- Click the `Change Icon...` button
- Select the icon of your choice
- Click the `Ok` button for both opened screens

Optional: Add to Windows 10 Start Menu
- Press `Start + R` on your keyboard
- Type: `%appdata%\Microsoft\Windows\Start Menu\Programs`
- Paste the shortcut you've created in the previous steps in there
- Optionally set as tile by opening the start menu, then finding the shortcut on the left list. Right-click and choose `Pin to Start`.


## Future

- I'd like to support Linux and MacOS as well.
- Being able to select more hour options (not just 1-9)
- Having a shortcut out of the box
- Make it look good
