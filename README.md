# :signal_strength: Airlink
> A terminal-based UX designed for cracking detected Wi-Fi broadcasts.

*Note: This is a modified fork featuring an F3 auto-cracker and an automated setup script. Originally created by Svarii / VauL7 Zer0.*

### :sparkles: Features
* **Auto-Crack All (F3):** Automatically grab broadcasts in range, sort by signal strength, and crack networks not in your database.
* **Automated Setup:** Deploy the tool instantly with a self-destructing builder script that handles file moving, compiling, and symlinking.
* **Zero Typing:** Navigate menus seamlessly using arrow keys and function keys.
* **Password Vault:** Store and manage cracked Wi-Fi passwords locally.
* **Custom Themes:** Personalize your terminal appearance.
* **Network Insights & WHOIS:** Display router details, contact/domain info, and WHOIS data for connected networks.
* **Live Telemetry:** Real-time status monitors for cryptoLib, active connections, re-scan timers, and interface states.
* **Quick Access:** Open configuration files instantly with hotkeys.
* **Size Defaulted:** Configured to fit inside the default terminal window scale

### :link: Links & Resources
* **GitHub Repository:** [VauL7Zer0/airlink](https://github.com/VauL7Zer0/airlink)
* **Installation Video:** [YouTube Tutorial](https://youtu.be/5Ibom81Zdms)

## 📥 Recommended Upload Method
To avoid the hassle of copy-pasting code manually into Grey Hack, it is highly recommended to use the **Greybel VS Code Extension** to push files directly into the game:
1. Download [Greybel for VS Code](https://marketplace.visualstudio.com/items?itemName=ayecue.greybel-vs).
2. Connect to your Grey Hack session and upload your files instantly.

## 🔨: Installation Guide
### Step 1: Automated Builder (Recommended)
You must run the installation as root. Ensure `opt` and `airlink_builder.src` are in the same directory.
1. Build the installer: `build airlink_builder.src /root`
2. Run it: `/root/airlink_builder`
The script will automatically move directories, compile the source code, link the binary to `/bin`, create your Database folders, and delete itself when finished.

### Step 2: Directory Structure & Binaries (Manual Reference)
Set up your directory paths and place the compiled binaries in their respective locations:

/opt/airlink/

├── bin/airlink            # Main executable

├── lib/libAirlink.so      # Shared library dependency

└── etc/airlink.conf       # Configuration file

/home/{username}/Airlink/Theme/

├── hacker.ini             # Theme presets

├── rust.ini

└── anime.ini

## Built With
### GreyScript Prime
AirLink uses the GreyScript Prime library for extended scripting utilities, helper functions, and improved workflow capabilities within Grey Hack.
GitHub: https://github.com/Svarii/greyscript-prime

## Screenshots
<img width="672" height="427" alt="Screenshot 2026-07-20 020623" src="https://github.com/user-attachments/assets/1d09a7f9-5f52-4608-ab29-13e37bb92201" />
<img width="676" height="427" alt="Screenshot 2026-07-20 020612" src="https://github.com/user-attachments/assets/d9831672-343f-4e3d-a9d1-ab64bbab3e06" />
<img width="678" height="430" alt="Screenshot 2026-07-20 020600" src="https://github.com/user-attachments/assets/dcd9dccd-33fd-465d-a60d-8802e142803a" />
<img width="677" height="437" alt="Screenshot 2026-07-20 020540" src="https://github.com/user-attachments/assets/f86f3a2c-4df8-47c2-ab61-1d7eb1f4ab46" />
