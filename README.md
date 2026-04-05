# Daybreak

<p align="center">
  <img src="https://raw.githubusercontent.com/sthetix/Daybreak/master/images/preview.jpg" alt="Daybreak Preview">
</p>


This is a modded version of the Daybreak firmware modding tool, originally based on the Atmosphere-NX repository. This project simplifies the original Daybreak by removing unnecessary prompts.

## Simplified Workflow (5 Steps)

This version features a streamlined update process with fewer prompts for a safer user experience:

1. **Install** - Start the update installation process
2. **Select firmware directory** - Choose the firmware folder to use
3. **Update info** - View update information
4. **Ready to begin update installation** - Confirm to proceed
5. **Installing update** - The update is being applied

## Key Modifications

- Simplified 5-step workflow (2 prompts removed for safer user experience)
- Removed "reset to factory settings" option - preserves console condition
- Removed FAT32/FAT32+ExFAT selection - automatically uses FAT32+ExFAT for better compatibility with larger files

## Building

Ensure you have the DevKit Pro development environment set up with libnx and associated libraries.

To build, run:

```
make release
```

## Usage

Extract the resulting zip file on your Nintendo Switch's SD card root and launch it through the hbmenu.

## Credits

- Original Daybreak by Atmosphere-NX team
- nx-hbloader and associated projects

## License

This project follows the licensing terms of the original Daybreak project from Atmosphere-NX. Please refer to the project's license file for more information.