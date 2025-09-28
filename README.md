# Cracker
Cracker - Windows Password Cracking Utility
Cracker - Windows Password Cracking Utility
Cracker is a Windows password reset and user management toolkit designed for system administrators and forensic professionals who need to regain access to locked Windows systems. This utility leverages the Windows Recovery Environment (WinRE) or external boot media to safely and temporarily replace system accessibility executables, allowing privileged command prompt access at the login screen. It also provides a powerful local user management tool for account recovery and maintenance.

Features
Bypass Windows Login: Temporarily replaces utilman.exe with cmd.exe, enabling a command prompt from the login screen via the accessibility button.
User Management: Includes userexploit.bat, a comprehensive batch script for listing users, resetting passwords (typed or random), creating/deleting accounts, enabling/disabling users, and managing group memberships.
Safe Revert: Easily restore original system files (utilman.exe, sethc.exe) and remove all traces of the tool with a single command.
No Permanent Changes: All modifications are fully reversible, ensuring system integrity after use.
Requirements
Boot from WinRE or External Media: The tool must be run from Windows Recovery Environment or a bootable USB/DVD (e.g., Hiren’s Boot CD WinPE).
Secure Boot Disabled: Secure Boot must be turned off in BIOS/UEFI to allow unsigned scripts and system file modifications.
BitLocker Off: BitLocker encryption must be disabled or suspended, as encrypted drives cannot be modified.
USB Drive Placement: Place the entire Cracker folder in the root of your USB drive (e.g., E:\Cracker).
Usage
Boot the target system into WinRE or from your prepared USB.
Open a command prompt and run start launch.bat from the USB.
Use the interactive menu: type apply to enable the tool, or revert to restore the system.
At the login screen, use the accessibility button to open a command prompt and run userexploit.bat for user management.
Disclaimer
This tool is for authorized administrative or forensic use only. Unauthorized use may be illegal and could result in data loss or system instability. The creator is not responsible for any misuse or damage.
