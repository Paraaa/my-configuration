# my-configuration
This is my configuration for my windows terminal. The 
configuration is based on [SavvyNik](https://www.youtube.com/watch?v=IdKEA_N_awM) video on the windows 
terminal. Also I use [Oh My Posh](https://ohmyposh.dev/).

![Terminal Image](Terminal.png)

___



# Installation
- Install [Nerd Font](https://www.nerdfonts.com/font-downloads)
- Install [Oh My Posh](https://ohmyposh.dev/)
- Install Nerd Font via: `oh-my-posh font install`
- [Dracula theme](https://draculatheme.com/windows-terminal)

```
"schemes": [
    {
        "name": "Dracula",
        "cursorColor": "#F8F8F2",
        "selectionBackground": "#44475A",
        "background": "#282A36",
        "foreground": "#F8F8F2",
        "black": "#21222C",
        "blue": "#BD93F9",
        "cyan": "#8BE9FD",
        "green": "#50FA7B",
        "purple": "#FF79C6",
        "red": "#FF5555",
        "white": "#F8F8F2",
        "yellow": "#F1FA8C",
        "brightBlack": "#6272A4",
        "brightBlue": "#D6ACFF",
        "brightCyan": "#A4FFFF",
        "brightGreen": "#69FF94",
        "brightPurple": "#FF92DF",
        "brightRed": "#FF6E6E",
        "brightWhite": "#FFFFFF",
        "brightYellow": "#FFFFA5"
    }
]
```

Other changes:
```
"defaults": {
    "colorScheme": "Dracula",
    "tabColor": "#282A36",
    "useAcrylic": true,
    "opacity": 0,
    "fontSize": 10
}

[...]
"font":{
    "face": "CaskaydiaCove NF"
},
[...]

"tabTitle": "Terminal"
```
