# Take Your Token CLI
This script implements a Command-Line Interface (CLI) for [Take Your Token](https://takeyourtoken.necst.it/), a [NECSTLab](https://necst.it/)'s internal project used to keep track of how much fuel you used (coffee, beers, energy drinks, etc.).

It's a CLI script that nobody asked, to increase users' hipster ego and permits them to never ever leave their terminal habitat.

## Disclaimer
**Caffeine OR Alcohol power users' tip**: Let's say for example you want to buy a coffee every 3 hours and a beer at 7PM, you can automate `tyt buy coffee` and `tyt buy beer` commands to be fired as your wishes with `cron` scheduler.

Another example is to run a `tyt buy coffee` as soon your machine starts up. This can be done within every OS launching the command as a *startup application*.

## Dependencies
A few, probably already available on your machine. In this case they are `curl`, `grep` and `cut` (this last command is contained in `coreutils` package).
- Debian based distro's install: `sudo apt install curl grep coreutils`
- Arch based distro's install: `sudo pacman -S curl grep coreutils`
- MacOS X users: `brew install curl grep coreutils`
 
 You, of course, also need a valid and activated profile on <https://takeyourtoken.necst.it/>.
 
 ## Usage
 You can see how to `buy` things, `add` tokens or show your token amount by running `tyt help`, it's pretty self explicative.
