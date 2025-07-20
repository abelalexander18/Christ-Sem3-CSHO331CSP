# Installing and Running Kali Linux 

---

## Part 1: Attempt to Install Kali Linux on Oracle VirtualBox

### Step 1: Download and Install Oracle VirtualBox
1. Go to the official website: https://www.virtualbox.org
2. Click **"Downloads"**.
3. Select **"macOS / Intel hosts"** (VirtualBox is not fully compatible with Apple Silicon/M1/M2).
4. Download and open the `.dmg` file.
5. Drag and drop VirtualBox into the Applications folder.
6. Launch VirtualBox.

### Step 2: Download Kali Linux ISO
1. Visit the official Kali Linux website: https://www.kali.org/get-kali/
2. Under "Kali Linux ISO Images", download the **Installer ISO** (64-bit).
   - Example: `kali-linux-2025.2-installer-amd64.iso`

### Step 3: Create a New Virtual Machine in VirtualBox
1. Open VirtualBox and click **"New"**.
2. Name your VM (e.g., `Kali-Linux`).
3. Set:
   - **Type**: Linux
   - **Version**: Debian (64-bit)
4. Click **Continue**.

### Step 4: Allocate Memory
- Assign at least **2048 MB (2 GB)** of RAM.
- Click **Continue**.

### Step 5: Create Virtual Hard Disk
- Choose **Create a virtual hard disk now**.
- Choose **VDI (VirtualBox Disk Image)**.
- Choose **Dynamically allocated**.
- Set size to **20 GB or more**.
- Click **Create**.

### Step 6: Attach Kali ISO to VM
1. Select the Kali VM and click **Settings**.
2. Go to **Storage** → Click on **Empty (under Controller: IDE)**.
3. Click the CD icon on the right → Choose a disk file.
4. Select the **Kali ISO** you downloaded.
5. Click **OK**.

### Step 7: Start the Virtual Machine
- Click **Start** on the main VirtualBox window.
- The Kali Linux installer should launch.

### Problem Encountered:
- On MacBooks with **Apple Silicon (M1/M2)**, the VM failed to start or froze on a blank screen.
- **Reason**: VirtualBox is not fully compatible with Apple Silicon architecture.

---

## Part 2: Successful Kali Linux Setup Using UTM (For MacBooks with M1/M2)

### What is UTM?
UTM is a free, open-source virtual machine tool for macOS that supports Apple Silicon chips natively.

### Step 1: Download and Install UTM
1. Visit: https://mac.getutm.app
2. Click **Download** → Download the latest `.dmg` file.
3. Open the file and drag **UTM** into the Applications folder.
4. Launch the UTM app.

### Step 2: Download Kali Linux ISO
(If not already done in Part 1)

1. Go to https://www.kali.org/get-kali/
2. Download the **Installer ISO (amd64)**.

### Step 3: Create a New Virtual Machine in UTM
1. Click **"Create a New Virtual Machine"**.
2. Choose **Virtualize** (since we're using an x86_64 ISO).
3. Select **Linux** as the operating system.
4. Click **Next**.

### Step 4: Boot ISO and Configure VM
1. On the **Boot ISO Image** screen, click **Browse** and select your Kali ISO file.
2. Click **Next**.

### Step 5: Configure Hardware
1. CPU: Choose at least **2 cores**.
2. Memory: Allocate at least **2048 MB (2 GB)** of RAM.
3. Click **Next**.

### Step 6: Set Storage
1. Choose **Create a new disk image**.
2. Set size to **20 GB or more**.
3. Click **Next**.

### Step 7: Name and Save VM
1. Name your VM (e.g., `Kali-UTM`).
2. Choose a save location or use default.
3. Click **Save**.

### Step 8: Start the Virtual Machine
1. Select your new VM in UTM.
2. Click **Play** (Start).
3. The Kali Linux installer should boot up.
---


