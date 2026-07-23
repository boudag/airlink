:signal_strength: Airlink (Auto-Crack Edition)
A terminal-based UX designed for cracking detected Wi-Fi broadcasts.

Originally created by Svarii / VauL7 Zer0. This is a modified fork featuring automated cracking and an auto-installer.

:sparkles: Features
Auto-Crack All (F3): Automatically grab all broadcasts in range, sort them by signal strength (descending), and crack every network that isn't already saved in your database.

Automated Setup: Includes a one-click, self-destructing installer to handle compiling and file management.

Zero Typing: Navigate menus seamlessly using arrow keys and function keys.

Password Vault: Store and manage cracked Wi-Fi passwords locally.

Custom Themes: Personalize your terminal appearance.

Network Insights & WHOIS: Display router details, contact/domain info, and WHOIS data for connected networks.

Live Telemetry: Real-time status monitors for cryptoLib, active connections, re-scan timers, and interface states.

Quick Access: Open configuration files instantly with hotkeys.

Size Defaulted: Configured to fit inside the default terminal window scale.

:link: Links & Resources
Original GitHub Repository: VauL7Zer0/airlink

Original Installation Video: YouTube Tutorial

📥 Recommended Upload Method
Manually copy-pasting code into Grey Hack can be a massive hassle. It is highly recommended to use the Greybel VS Code Extension to push these files directly into the game.

Download Greybel for VS Code.

Follow the extension instructions to connect to your Grey Hack session.

Upload the files directly to your in-game computer in seconds.

🔨 Installation Guide (Automated)
This fork replaces the manual installation process with airlink_builder.src. Because Airlink creates folders in /root and moves files to /, you must run the installation as the root user.

Step 1: Upload Files
Ensure the opt folder and airlink_builder.src are downloaded to the same directory on your in-game computer.

Step 2: Build & Run Installer
Compile the builder and run it:

Plaintext
build airlink_builder.src /root
/root/airlink_builder
The script handles everything automatically. It will:

Move the opt directory to /

Compile /opt/airlink/bin/airlink.src

Create a symlink in /bin so you can launch the tool from anywhere

Create the required /root/Airlink/Database directories

Delete its own source and binary files to keep your drive clean.

Once finished, simply type airlink in your terminal to launch the program!

Directory Structure Reference (Created by Installer):

Plaintext
/opt/airlink/
├── bin/airlink            # Main executable
├── lib/libAirlink.so      # Shared library dependency
└── etc/airlink.conf       # Configuration file

/root/Airlink/
└── Database/              # Saved network database
Built With
GreyScript Prime
AirLink uses the GreyScript Prime library for extended scripting utilities, helper functions, and improved workflow capabilities within Grey Hack.
GitHub: https://github.com/Svarii/greyscript-prime

## Screenshots
<img width="672" height="427" alt="Screenshot 2026-07-20 020623" src="https://github.com/user-attachments/assets/1d09a7f9-5f52-4608-ab29-13e37bb92201" />
<img width="676" height="427" alt="Screenshot 2026-07-20 020612" src="https://github.com/user-attachments/assets/d9831672-343f-4e3d-a9d1-ab64bbab3e06" />
<img width="678" height="430" alt="Screenshot 2026-07-20 020600" src="https://github.com/user-attachments/assets/dcd9dccd-33fd-465d-a60d-8802e142803a" />
<img width="677" height="437" alt="Screenshot 2026-07-20 020540" src="https://github.com/user-attachments/assets/f86f3a2c-4df8-47c2-ab61-1d7eb1f4ab46" />



