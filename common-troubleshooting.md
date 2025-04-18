# Common Troubleshooting

## 1. Computer Won't Start

**Problem**: The computer does not power on when pressing the power button.

**Solution**:
### Step 1: Check the Power Supply
- Ensure the power cable is securely plugged into both the computer and the power outlet.
- Try a different power outlet or power strip.

### Step 2: Inspect the Power Button
- Press the power button firmly.
- If the power button seems stuck, gently release or clean it.

### Step 3: Check for Lights or Sounds
- Look for any lights or sounds (fans, beeps) when you press the power button. If you hear beeps, consult the motherboard manual for diagnostic codes.

### Step 4: Test the Power Supply Unit (PSU)
- If there is no power at all, test the PSU with a PSU tester or swap it with a known working one.

### Step 5: Reset CMOS
- **Why**: A corrupted BIOS/UEFI or incorrect system settings might prevent the computer from starting. Resetting the CMOS can restore the default BIOS settings and help resolve the issue.
- **How to Reset CMOS**:
  - **Best Option: Removing the CMOS Battery**:
    1. Turn off the computer and unplug it from the power source.
    2. Open the case and remove the **CMOS battery** (a coin-cell battery on the motherboard).
    3. Wait for 5-10 minutes to allow the BIOS settings to reset.
    4. Reinsert the battery and close the case.

---

## 2. Internet Connectivity Issues

**Problem**: The computer or device cannot connect to the internet.

**Solution**:
### Step 1: Restart the Router
- Unplug the router’s power cable, wait 30 seconds, and plug it back in.
- Wait for the router to reboot and check if the connection is restored.

### Step 2: Check the Network Cable (for wired connections)
- Ensure that the Ethernet cable is securely plugged into both the computer and the router/modem.
- Try a different cable to see if the current one is faulty.

### Step 3: Reconnect to Wi-Fi (for wireless connections)
- Click on the Wi-Fi icon in the system tray or taskbar.
- Select your network and enter the correct password.

### Step 4: Run the Network Troubleshooter (Windows)
- Go to **Settings** > **Network & Internet** > **Status**.
- Click **Network Troubleshooter** and follow the prompts to diagnose and fix issues.

### Step 5: Reset Network Settings (if needed)
- Go to **Settings** > **Network & Internet** > **Status**.
- Click on **Network reset** and follow the instructions to reset the network adapters.

---

## 3. Slow Computer Performance

**Problem**: The computer is running slow and taking longer than usual to perform tasks.

**Solution**:
### Step 1: Close Unnecessary Programs
- Press **Ctrl+Shift+Esc** to open the Task Manager.
- End tasks for programs that are not in use, especially those using a lot of system resources.

### Step 2: Run Disk Cleanup
- Open **File Explorer**, right-click the **C: drive** > **Properties** > **Disk Cleanup**.
- Select the items you want to delete (e.g., temporary files, system files), and click **OK**.

### Step 3: Check for Malware or Viruses
- Run a full system scan using **Windows Defender** or any third-party antivirus software.

### Step 4: Disable Startup Programs
- Open **Task Manager** > **Startup** tab.
- Disable unnecessary programs that start automatically when the computer boots.

### Step 5: Defragment the Hard Drive (for HDDs)
- Open **Control Panel** > **System and Security** > **Defragment and Optimize Drives**.
- Select the hard drive and click **Optimize**.

---

## 4. Printer Not Printing

**Problem**: The printer is not responding or not printing documents.

**Solution**:
### Step 1: Check Printer Connections
- Ensure the printer is plugged into the power outlet and the computer.
- Check if the printer is connected via USB or Wi-Fi (depending on your setup).

### Step 2: Restart the Printer and Computer
- Turn off the printer, wait 10 seconds, and then turn it back on.
- Restart the computer to clear any errors.

### Step 3: Check Printer Queue
- Open **Control Panel** > **Devices and Printers**.
- Double-click on your printer and check if there are any documents stuck in the print queue. If so, cancel or clear them.

### Step 4: Update Printer Drivers
- Go to the **printer manufacturer’s website** and download the latest drivers.
- Install the updated drivers and restart your computer.

### Step 5: Run the Printer Troubleshooter
- Go to **Settings** > **Devices** > **Printers & Scanners**.
- Click on your printer and select **Manage** > **Run the troubleshooter**.

---

## 5. Blue Screen of Death (BSOD)

**Problem**: The computer displays a Blue Screen of Death (BSOD) error and crashes.

**Solution**:
### Step 1: Note the Error Code
- Write down or take a picture of the error code displayed on the BSOD screen (e.g., "0x0000007B" or "IRQL_NOT_LESS_OR_EQUAL").

### Step 2: Restart the Computer
- Reboot the computer and see if the issue persists.

### Step 3: Boot into Safe Mode
- Restart the computer and press **F8** during boot-up to enter **Safe Mode**.
- Try uninstalling any recently installed software or drivers that may be causing the issue.

### Step 4: Check for Hardware Issues
- Disconnect any recently added hardware (USB devices, peripherals) and reboot.
- Run memory diagnostics by typing `mdsched` in the Start menu and selecting **Windows Memory Diagnostic**.

### Step 5: Check for Driver Updates
- Go to **Device Manager** > Right-click on the device with the problem > **Update driver**.

### Step 6: Perform a System Restore
- If the issue started after a recent change, performing a **System Restore** can help revert your computer to a previous state when it was working fine.
- To perform a **System Restore**:
  1. Type **System Restore** in the Start menu and select **Create a restore point**.
  2. Click on **System Restore** and follow the on-screen instructions.
  3. Choose a restore point from before the issue occurred and complete the process.

---

## 6. Application Not Responding

**Problem**: An application freezes or becomes unresponsive.

**Solution**:
### Step 1: End the Task
- Open **Task Manager** (Ctrl+Shift+Esc).
- Select the unresponsive application and click **End Task**.

### Step 2: Restart the Application
- After ending the task, try reopening the application to see if it works.

### Step 3: Check for Updates
- Open the application and check if there are any updates available.
- Install any updates and restart the application.

### Step 4: Reinstall the Application
- Uninstall the application via **Control Panel** > **Programs** > **Uninstall a program**.
- Download the latest version and reinstall the application.

---

## Conclusion

For any unresolved issues, consider reaching out to the manufacturer's support or a technical expert for further assistance.
