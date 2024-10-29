# Hyprland Config

## About the repository
This repository contains the configurations from my Arch Linux environment, which uses *Hyprland* as the main window manager.

While this repository ideally should include all relevant configuration and settings files, it may not contain every file due to the nature of the associated contents. If any files are missing, I will provide the reason, which may simply be that I forgot to include them.

Although the main idea was for me to set up everything on my system, I have also used external resources (e.g., Waybar), and in such cases, I will add the respective credits to the original authors.

It’s important to note that, apart from the Hyprland installation, almost all the packages were installed using the default terminal (Kitty).

## What will you find[^1]
1) Hyprland.
2) ZSH .

## 1) Hyprland 
### Main config
The *Hyprland* ``config_files`` directory that I included contain scripts I created for various purposes. The ```config_files``` directory includes the main script (automatically generated by *Hyprland*) and *Hyprpaper*. The ```hyprland.config``` file sets up basic configurations, such as display settings, shell preferences, and key bindings, while ```hyprpaper.config``` enables the *Hyprpaper* extension, allowing you to add custom wallpapers.

### The *waybar*
"Waybar" is the status bar on the main desktop that displays useful information about the system, such as hardware usage, date, workspaces, and more. While I refer to it as "*waybar*", it must be said that there are other customizable bars available. However, I chose this one, which must be [installed](https://github.com/Alexays/Waybar) like the other hypr extensions, though it will be in a different directory depending on your system (see the official Waybar page). To edit *waybar*, you should have basic knowledge of ```JavaScript``` and ```CSS```[^3]. In this repository, the ```waybar_config``` directory includes a custom version of an [existing](https://github.com/mxkrsv/dotfiles-old/tree/master/.config/waybar) *waybar* configuration (meaning I made some changes to it). I'm not an expert in ```JavaScript``` and ```CSS```, so I opted to use another *waybar* that must be installed according to the instructions in the repository. The *waybar* I included, along with the respective script, is still a work in progress.

## 2) ZSH
ZSH is a Unix shell known for its customization. Because of this, I decided to incorporate it alongside Kitty, the default terminal.

Customization is done in the ```.zshrc``` file. Like other services (e.g., Neovim), ZSH requires a plugin manager; in this case, the chosen one is *zinit*. Additionally, a font package (ideally Nerd Fonts) is needed, and I prefer *JetBrains Mono*. The contents of ```.zshrc``` should be copied to your personal file (which should be created automatically when installing ZSH) and should be ready to go after you save it.

## To-do
* Hyprland: add basic programs[^5].
* Hyprland: customize shell.
* Hyprland: add global dark theme.
* Waybar: add location temperature.
* Waybar: finish my custom status bar.

## Screenshots
Main Desktop ($1920 \times 1080$):
![Desktop, not my laptop](https://github.com/JorgeCSH/I-use-Arch-btw/blob/main/screenshots/main_desktop.png)

General Desktop (left display: $1366 \times 768$, right display: $1920 \times 1080$):
![Generic battle station](https://github.com/JorgeCSH/I-use-Arch-btw/blob/main/screenshots/full_desktop.png)

Using my Battlestation[^4]:
![In use battle station](https://github.com/JorgeCSH/I-use-Arch-btw/blob/main/screenshots/custom_desktop.png)

## Final Words
This project is still a work in progress. I am new to the *Hyprland* world and need to polish my skills. Currently, I don’t have a lot of time to work on this, but I will be incorporating new features to make it more usable. If you like this (still developing...and pootly developed for now) custom desktop, feel free to try it and share any suggestions or comments :D, everything is welcome.

Also, the screenshots show a Neovim customization. It doesn't come with the repository, but you can find it in another one I created a while ago, if you're interested.

## References


[^1]: with this I mean my configurations.
[^2]: that must be installed separately. 
[^3]: or similar.
[^4]: I spend too much time alone.
[^5]: average linux experience.
