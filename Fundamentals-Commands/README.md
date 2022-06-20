# Fundamentals of SSH
> Discover Raspberry IP Address under LAN
- [Angry IP Scanner] (https://github.com/angryip/ipscan/releases/download/3.8.2/ipscan-3.8.2-setup.exe)

> Install Nmap - Discover Raspy IP Address on LAN/WLAN
```
sudo apt update
```
```
sudo apt install -y nmap
```

> Discover IPAddress & MacAddress
```
ifconfig 
```

> Discover IPAddress
```
hostname -I
```

> SSH Connection
```
ssh <raspberryhostmane>@<raspberryipaddress>
default hostname: pi | password: raspberry
```
> SSH Re-Build Key
```
ssh-keygen -R "hostname/ipaddress"
```

# Fundamentals of SUDO
> Aggiornamento lista pacchetti
```
sudo update
```
> Aggiornamento pacchetti installati 
```
sudo upgrade
```

> Installare Pacchetti
```
sudo apt-get install <nomepacchetto>
```

> Rimuovere Pacchetti
```
sudo apt-get remove <nomepacchetto>
```

# Fundamentals of NPM
> Rimuovere Pacchetti
```
sudo npm install <nomepacchetto>
```
# Fundamentals of GIT
> Git add
```
git add -A
```
> Git commit 
```
git commit -m "Testo Commit
```
> Git commit
```
git push origin <nomebranch>
```
> Git Fetch/Checkout
```
git fetch && git checkout <nomebranch>
```