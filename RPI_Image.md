### Installation instructions Raspberry Pi

#### Requirements

- A microSD card (32 GB or larger recommended)
- A microSD card reader (if your computer does not have a built-in SD card slot)
- The Raspberry Pi disk image file
- USBImager software (recommended from https://bztsrc.gitlab.io/usbimager/)

#### Step-by-Step Instructions

1. **Download USBImager:**
   - Visit the official USBImager webpage at https://bztsrc.gitlab.io/usbimager/
   - Download the version of USBImager compatible with your operating system (Windows, macOS, or Linux).

2. **Install USBImager:**
   - USBImager is typically provided as a portable application, meaning no installation is necessary. Simply extract the downloaded archive and run the executable.

3. **Prepare Your microSD Card:**
   - Insert the microSD card into your computer using a card reader.
   - Make sure to back up any important data on the microSD card, as this process will erase all existing data on the card.

4. **Launch USBImager:**
   - Open the USBImager application you downloaded and extracted.

5. **Select the Raspberry Pi Image File:**
   - Click on the "Browse" button to open a file dialog.
   - Navigate to the location of your Raspberry Pi image file and select it.

6. **Select the Destination Drive:**
   - Be very careful at this step to select your microSD card from the list of available drives.
   - Double-check to ensure you've selected the correct drive, as choosing the wrong one could erase data on another device.

7. **Write the Image:**
   - Click the "Write" button to start writing the Raspberry Pi image to the microSD card.
   - Wait for the process to complete. This may take several minutes, depending on the size of the image and the speed of your microSD card.

8. **Safely Eject the microSD Card:**
   - Once the writing process is complete, close USBImager.
   - Eject the microSD card safely from your computer.

9. **Insert the microSD Card into Your Raspberry Pi:**
   - Remove the microSD card from the card reader and insert it into the microSD card slot on your Raspberry Pi.

10. **Power On Your Raspberry Pi:**
    - Connect the power supply to your Raspberry Pi.
    - Your Raspberry Pi should boot from the microSD card you just prepared.

#### Troubleshooting

- **Raspberry Pi Does Not Boot:**
  - Ensure the microSD card is properly inserted.
  - Verify that the Raspberry Pi image file was correctly written to the microSD card.
  - Check if your Raspberry Pi model requires a specific version of the image file.

- **Slow Performance:**
  - Consider using a microSD card with a faster read/write speed.
  - Ensure the Raspberry Pi power supply meets the recommended specifications.
