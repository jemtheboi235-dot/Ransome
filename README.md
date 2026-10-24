A-90 Ransom: Desktop Horror Minigame
A fast-paced, DOORS-inspired desktop horror experience built entirely in Python.

A-90 has locked down your desktop! To survive, you must hunt for hidden coin codes scattered across a local folder and pay off the ransom before the two-minute timer runs out. But stay alert: moving your mouse during an active A-90 ambush will trigger a severe penalty and cost you valuable time!

Safety Notice: This is entirely an entertainment project. It only interacts with a temporary folder (DOORS_Hunt) generated on your Desktop, does not encrypt your personal data, and is completely harmless to your system. Press ESC at any time to instantly quit.

How It Works
The Lockdown: Upon launching, a ransom interface activates a strict 120-second countdown demanding a 500-coin payment.

The Hunt: A folder named DOORS_Hunt spawns on your Desktop, filled with dummy text files (coin_stash_*.txt).

Real Coins: Opening the right files reveals a valid code worth +100 Coins.

Duds: Expired files that waste your time.

The Penalties:

Submitting an incorrect code deducts 10 seconds from your clock.

Moving your mouse during an A-90 attack catches you off guard.

The Goal: Locate 5 valid codes, type them into the on-screen prompt, and hit the 500-coin threshold before time expires.

How to Run & Play
Prerequisites
Python 3.x installed on your machine.

Standard Tkinter support (included by default with most Python installations across Windows, macOS, and Linux).

Installation & Execution
Option 1: Clone the Repository

Bash
git clone https://github.com/jemtheboi235-dot/Ransome/releases/tag/Ransom
cd a90-ransom-game
python a90_hunt.py
Option 2: Direct Download

Download a90_hunt.py directly from the repository.

Open your terminal or command prompt.

Navigate to your download folder and run:

Bash
python a90_hunt.py
Controls & Features
Mouse & Keyboard: Use them to navigate the DOORS_Hunt directory, open files, copy codes, and input them into the dialogue box.

ESC Key: Instantly terminates the application and cleans up workspace assets.

Self-Contained Assets: Utilizes embedded base64 data to handle audio and graphics natively without needing external asset folders.

Disclaimer
This script is an independent fan creation inspired by the entity A-90 from the Roblox experience DOORS by LSPLASH. It is completely safe to execute.
