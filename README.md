For those still running these motherboards—especially paired with popular AM4 processors like the Ryzen 7 5800X3D—I am offering a custom modded BIOS that unlocks full control over the notoriously noisy chipset (PCH) fan.

Compatibility:⚠️ Only compatible with ASUS ROG Crosshair VIII Hero, Hero Wi-Fi, and Formula motherboards in combination with Ryzen 3000 / 5000 series CPUs

Mod Details: From HERO to ZERO (Noise)
This modification was carefully executed by extracting the relevant BIOS section, modifying fan parameters with a specialized BIOS editor, and re-inserting it back into the original vendor BIOS via HEX editor.

The modification exclusively targets the PCH chipset fan control. All other stock BIOS functions remain completely untouched.

⚠️ Disclaimer: Use at your own risk. I assume no liability for any hardware damage or issues resulting from flashing custom firmware.


How to Flash
This modded BIOS must be flashed using the rear panel USB BIOS Flashback button.

1. Rename the BIOS File
Before flashing, rename your downloaded .CAP file according to your exact motherboard model:

Crosshair VIII Hero: C8H.CAP

Crosshair VIII Hero Wi-Fi: C8HW.CAP

Crosshair VIII Formula: C8F.CAP

2. Flashing Procedure
Follow the official ASUS USB BIOS Flashback procedure.

💡 Pro-Tip / Troubleshooting:
Recommended steps: Power on the PC, immediately press the Clear CMOS button (the system will power down), then press and hold the BIOS Flashback button on the rear I/O.
If Flashback fails: Flash the official stock (unmodded) version 5503 BIOS via EZ Flash inside BIOS first. Afterwards, flash the modded BIOS via USB Flashback.

Accessing PCH Fan Controls
Once successfully flashed, navigate to:
Monitor ➔ Q-Fan Control (Note: Do not use the F6 hotkey menu, access it directly via the Monitor tab).
