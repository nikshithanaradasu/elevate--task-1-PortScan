# 🔍 Elevate Labs – Task 1: Scan Local Network for Open Ports

## 🎯 Objective
To discover open ports on devices in my local network using Nmap and understand service exposure and potential risks.

## 🛠 Tools Used
- **Nmap** for port scanning
- (Optional) **Wireshark** for packet analysis

## 📝 Steps Performed
1. Installed Nmap on macOS using Homebrew.
2. Found my local IP (`192.168.254.175`) using `ifconfig`.
3. Determined the subnet as `192.168.254.0/24`.
4. Tried TCP SYN scan using `sudo nmap -sS 192.168.254.0/24` (didn't work due to permissions).
5. Successfully performed TCP Connect scan using: nmap -sT 192.168.254.0/24
6. Saved results to `scan_results.txt`.
7. Took screenshots and saved in `screenshots/`.

## 🧠 Key Learnings
- Discovered which ports/services are open (e.g., port 5000 and 7000).
- Understood how to identify services and potential risks.

## 📁 Files
- `scan_results.txt` – Nmap scan output.
- `screenshots/` – Terminal screenshots.
