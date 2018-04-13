# macOS Systemwide Adblock
Including spotify audio ads. Uses [MattiSG's adblock](https://github.com/MattiSG/adblock)

# Install

* Clone this repo, enable adblock
   ```bash
   # clone this repo
   git clone https://github.com/mustakimali/adblock-spotify.git
   # navigate to folder
   cd adblock-spotify
   # make executable
   sudo chmod 700 adblock-spotify
   # install adblock
   sudo ./adblock-spotify
   ```
   This will install [brew](https://brew.sh/) packagee manager (if you don't have it)
# Uninstall

Remember you have installed a system-wide adblock and sometime you might need to disable it. To do so,
```
sudo adblock off
```
To turn it back on
```bash
sudo ./adblock-spotify
```

# Update
```bash
sudo adblock off && sudo ./adblock-spotify
```