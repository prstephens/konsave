# Konsave (Save Plasma Customization)
A CLI program that will let you save and apply your KDE Plasma customizations with just one command! Also, it has a "K" in the name :D  

---

![SS_2021-03-01_13-32-09](https://user-images.githubusercontent.com/39525869/109468428-90516780-7a92-11eb-904d-77d5d87faf36.png)


---
## Dependencies
There are no dependencies! Just make sure your python version is above `3.8`.

## Installation
- Clone This repo  
`git clone https://github.com/Prayag2/konsave ~/Downloads/konsave`
- Make it executable  
`cd ~/Downloads/konsave`
`chmod +x ./install.sh`
- Install  
`./install.sh`

## Usage
### Get Help
`konsave -h`
### Save current configuration as a profile
`konsave -s <profile name>`
### List all profiles
`konsave -l`
### Remove a profile
`konsave -r <profile id>`
### Apply a profile
`konsave -a <profile id>`  
You may need to log out and log in to see all the changes.  
## Contribution
You can contribute by reporting issues or fixing bugs!

## License
This project uses GNU General Public License 3.0
