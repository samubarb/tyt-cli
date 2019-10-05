# Take Your Token CLI
This script implements a Command-Line Interface (CLI) for [Take Your Token](https://takeyourtoken.necst.it/), a [NECSTLab](https://necst.it/)'s internal project used to keep track of how much fuel you used (coffee, beers, energy drinks, etc.).

It's a CLI script that nobody asked, to increase users' hipster ego and permits them to never ever leave their terminal habitat.

## Disclaimer
**Caffeine || Alcohol power users' tip**: Let's say for example you want to buy a coffee every 3 hours and a beer at 7PM, you can automate `tyt buy coffee` and `tyt buy beer` commands to be fired as your wishes with `cron` scheduler.

Another example is to run a `tyt buy coffee` as soon your machine starts up. This can be done within every OS launching the command as a *startup application*.

## Dependencies
Python 3.6 or above is required an also the python module `requests` that you can easily find on `pip3` package manager.

- Ubuntu and Debian-based distro: `sudo apt install python3 python3-pip`
- Mac OSX users: `brew install python3`
- Arch based distros: `sudo pacman -S python python-pip`

And finally install `requests` through `pip`. `pip3 install --user requests` (only `pip` for Arch).
- Ubuntu and Debian-based distro: `pip3 install --user requests`
- Mac OSX users: `pip3 install requests` (without `--user` flag due to a bug in `brew`. It may require `sudo`)
- Arch based distros: `pip install --user requests`

You, of course, also need a valid and activated profile on <https://takeyourtoken.necst.it/>.
 
## Usage
You can see how to `buy` things, `add` tokens or show your token amount by running `tyt help`, it's pretty self explicative.

I also suggest to add an alias to your shell config to be able to call `tyt` from everywhere on your system.
You can add the line `alias tyt="~/PATH-TO-TYT-FOLDER/tyt"` to `~/.bashrc` or `~/.zshrc`, depending on wich shell you are using.
If you cloned this repo in your home, you can pretty safely go with `alias tyt="~/tyt-cli/tyt"`.
