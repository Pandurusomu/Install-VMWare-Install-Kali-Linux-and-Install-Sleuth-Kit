# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
### Name: Panduru Somu
### Reg No: 212223240111
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## **Design Steps:**

### **Step 1: Install  VirtualBox**

### **Installation Steps:**
1. Download the **Windows hosts** `.exe` file from the official VirtualBox website.  
2. Run the installer and follow the on-screen instructions.  
3. Once installed, launch VirtualBox to verify the installation.


### **Step 2: Install Kali Linux on VirtualBox**
🔗 **Download Kali Linux VM**: [Click Here](https://www.kali.org/get-kali/#kali-virtual-machines)  

### **Installation Steps:**
1. Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).  
2. Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM. 
3. Go to Settings > Storage, click Empty under Controller: IDE. 
4. Select Graphical Install, follow the prompts to set language, location, username, and password.
5. Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.


### **Step 3: Install Sleuth Kit (CLI-based Forensic Tools)**
🔗 **Download Sleuth Kit**: [Click Here](https://sleuthkit.org/download.php)  

### **Installation Steps:**
1. Download the **Windows ZIP package** from the official website.  
2. Extract the ZIP folder and move it to a suitable directory (e.g., `C:\sleuthkit`).  
3. Add the **bin folder** to Windows PATH:
   - Open **Control Panel** → **System** → **Advanced System Settings**.  
   - Click **Environment Variables** → Edit **Path**.  
   - Add the Sleuth Kit `bin` folder path and save changes.  
4. Verify installation by running:
   ```sh
   fls -version
   
## PROGRAM:

## OUTPUT:

![WhatsApp Image 2025-08-14 at 14 19 12_a07da715](https://github.com/user-attachments/assets/29789678-a0a5-45a7-994f-ad5214e11fd1)

![WhatsApp Image 2025-08-14 at 14 34 04_13a62e6d](https://github.com/user-attachments/assets/a40d7ea7-343d-45d4-8717-7e1894a16a38)

![WhatsApp Image 2025-08-14 at 14 34 32_3fae2c6a](https://github.com/user-attachments/assets/44c7b2a7-3ef6-4f4c-b72d-749d2434e20e)

## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
