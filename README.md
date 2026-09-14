# Workspaces with window icons

An [Omarchy](https://omarchy.org/) shell bar widget — a fork of the built-in
`deda.workspaces-icons` widget that also shows the icon of each opened application window
next to its workspace number. Click an icon to switch to that window's
workspace.

![Preview](preview.png)

## Install

```bash
omarchy plugin add https://github.com/sebastix/omarchy-workspaces-icons.git --enable
omarchy plugin disable omarchy.workspaces
```

## Manual install

```bash
git clone https://github.com/sebastix/omarchy-workspaces-icons.git ~/.config/omarchy/plugins/sebastix.workspaces-icons
omarchy plugin enable sebastix.workspaces-icons
omarchy plugin disable omarchy.workspaces
```

## Update

```bash
omarchy plugin update sebastix.workspaces-icons
```

## Remove

```bash
omarchy plugin remove sebastix.workspaces-icons
```

## License

[MIT](LICENSE)
