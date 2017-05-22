# Hints and tricks when moving from Windows to Mac

I'm working on a Mac with a swiss german keyboard if you have another keyboard, some of the shortcuts might be different.
![external keyboard layout](https://raw.githubusercontent.com/gwildu/windows-2-mac/master/assets/keyboard_external.jpg "external keyboard layout")
![internal keyboard layout](https://raw.githubusercontent.com/gwildu/windows-2-mac/master/assets/keyboard_internal.jpg "internal keyboard layout")

# Keyboard shortcuts

| Windows | Mac | Description |
| --- | --- | --- |
|  | shift + cmd + t | Reopen a tab in a browser |
|  | shift + alt + 7 | backslash \ |
|  | alt + n | Tilde character ~ |
|  | cmd + <-- | delete file from macbook keyboard |


# command line

| command | description |
| --- | --- |
| `lsof -i :<port-number>` | get Process ID that is occupying a specific port |
| `kill -9 <pid>` | kill the process that has a specific Process ID |

# environment variables

If you're using the preinstalled terminal application, your env variables should go into:

`~/.bash_profile`

If using zshell they go into:

`~/.zshrc`

in one of those file just add an export line for each your env variables, e.g.,

```
export GOPATH=~/my-go-path-directory
export PATH=${GOPATH}/bin
```

