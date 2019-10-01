# Take Your Token CLI
This script implements a Command-Line Interface (CLI) for [Take Your Token](https://takeyourtoken.necst.it/), a [NECSTLab](https://necst.it/)'s internal project used to keep track of how much fuel you used (coffee, beers, energy drinks, etc.).

It's a CLI script that nobody asked, to increase users' hipster ego and permits them to never ever leave their terminal habitat.

## Disclaimer
**Caffeine || Alcohol power users' tip**: Let's say for example you want to buy a coffee every 3 hours and a beer at 7PM, you can automate `tyt buy coffee` and `tyt buy beer` commands to be fired as your wishes with `cron` scheduler.

Another example is to run a `tyt buy coffee` as soon your machine starts up. This can be done within every OS launching the command as a *startup application*.

## Dependencies
Python, either`python2` or `python3`. If never installed before go with `python3`:
- Debian based distro's install: `sudo apt install python3`
- Arch based distro's install: `sudo pacman -S python3`
- MacOS X users: `brew install python3`
 
You, of course, also need a valid and activated profile on <https://takeyourtoken.necst.it/>.
 
## Usage
You can see how to `buy` things, `add` tokens or show your token amount by running `tyt help`, it's pretty self explicative.
