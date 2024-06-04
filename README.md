# bookworm_setup
### Step-by-Step Instructions:

#### 1. Download and Install Raspberry Pi Imager
1. **Download** the Raspberry Pi Imager from the [official Raspberry Pi website](https://www.raspberrypi.com/software/).
2. **Install** the software on your computer by following the installation instructions for your operating system (Windows, macOS, or Linux).

#### 2. Prepare the MicroSD Card
1. Insert the microSD card into your computer’s SD card reader.
2. **Backup** any important data on the microSD card, as the flashing process will erase all data on the card.

#### 3. Launch Raspberry Pi Imager
1. Open the Raspberry Pi Imager software on your computer.

#### 4. Select the Raspberry Pi device
1. Click on the **"CHOOSE DEVICE"** button.
2. Scroll down and select the device which you are going to boot with the microSD.

#### 5. Select the Operating System (OS) Image
1. Click on the **"CHOOSE OS"** button.
2. Scroll down and select **"Use custom"**.
3. Navigate to the location where you have the `.img.xz` file stored, select it, and click **"Open"**.

#### 6. Choose the SD Card
1. Click on the **"CHOOSE STORAGE"** button.
2. Select the microSD card from the list of available drives.

#### 7. Write the Image
1. Click on the **"WRITE"** button.
2. A confirmation dialog will appear, warning you that all data on the microSD card will be erased. Confirm by clicking **"YES"**.
3. The imager will now write the `.img.xz` file to the microSD card. This process can take several minutes.

#### 8. Eject the MicroSD Card
1. Once the writing process is complete, you will see a message saying "Write Successful".
2. Click **"CONTINUE"** to finalize.
3. Safely eject the microSD card from your computer.

#### 9. Boot the Raspberry Pi with the microSD and run setup.sh
1. Once the raspberry pi gets booted, open terminal and then move to the "/bin/" directory using "cd /bin/".
2. Then type "./setup.sh" or "bash setup.sh" in the terminal.
3. Fill all the informtation and configuration it asks for and voila, your bookworm is setup.

