# my-ghostty-config
This is a simple repo about my ghostty configuration. Designed for curious people who just jumped into ghostty terminal want to customise around their own ghostty configuration file.

## neofetch on ghostty with customised synthwave theme
![Screenshot_20250307_130356](https://github.com/user-attachments/assets/acdcf86a-74d8-4361-82ad-ecc6fba5bb6a)

Transparency has been enabled in the config files, as you can see.
And a few other tweaks.

`shell-integration-features = no-cursor,sudo,no-title` Would display your user only.
If you please to remove that and have nothing, you can always change it to an empty string.
You can do that like this:
- `title = " "`

That will simply open a terminal with nothing in its title bar.

---

If you want nothing in it, just a floating terminal with no titlebar.
- `window-decoration = none`

check the **ghostty** documentation for further information: https://ghostty.org/docs

----

To apply the changes, you'd have to save the changes, exit the terminal & open it again.

---

If you're using `KDE`, you'd have the default KDE terminal emulator in the shortcut `Ctrl + Alt + T`
however, to change it, just search for **ghostty** in your desktop then:
- right click it.
- click on edit application.
- switch to the `advanced` tab.
- on "Current shortcut key:" click, and press `Ctrl + Alt + T`.

That is the default shortcut to open the terminal emulator, it will overwrite the default, of course. 
Nevertheless, you can absolutely choose any other shortcut more convinient for you.
I chose to overwrite the default, since I got used to it.
