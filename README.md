# fast-screenshot

[Spanish](./README_es.md)

## Instalation

Debian / Ubuntu:

- With x11-apps you can take the screenshot fastly in xwd format with the command with the same name.

- With netpbm you can convert it to another formats.

- With xclip you can copy it to clipboard.
 
```sh
sudo apt install x11-apps netpbm xclip
git clone https://github.com/aguadecoco1301/fast-screenshot
cd fast-screenshot
```
```
# With this, you can run it without inserting the route
sudo mv fast-screenshot /usr/bin/fast-screenshot
```

## Usage
It's easy. Execute the instruction and in the route on you specified the screenshot was saved. Default is your home folder.

You can exec it with the instruction --copy to copy the screenshot and not save it in a file.

You can add it into a keybind. For example, in i3, add this

```sh
bindsym Print exec --no-startup-id fast-screenshoot
bindsym Ctrl+Print exec --no-startup-id fast-screenshoot --copy
```

# Collaborate

If you want to collaborate, just send a pull request!
