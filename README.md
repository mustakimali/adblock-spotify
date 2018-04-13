# macOS Systemwide Adblock
Including spotify audio ads. Uses [MattiSG's adblock](https://github.com/MattiSG/adblock)

# Install

One command to install systemwide adblock with spotify adblock
   ```bash
   git clone https://github.com/mustakimali/adblock-spotify.git && cd adblock-spotify && sudo chmod 700 adblock-spotify && sudo ./adblock-spotify
   ```
   This will install [brew](https://brew.sh/) package manager (if you don't have it), clone this repo, install latest general adblock and spotify adblock. All in one command.
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
This will update the host file to block newer ad servers.
```bash
sudo adblock off && sudo ./adblock-spotify
```