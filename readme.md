# Transferring Xaero's Minimap Data Between Installations

This guide explains how to transfer Xaero's minimap and world map data from one Minecraft installation to another. Follow these steps to ensure your map data is preserved and usable in the new instance.

---

## Prerequisites

- Access to both the old and new Minecraft installations.
- File explorer or equivalent tool to manage files and folders.
- Basic understanding of navigating and modifying file directories.

---

## Step-by-Step Guide

### 1. Locate the Xaero Data Folder

1. Open the file directory of the **old modpack installation**. (You can right-click in CurseForge to open the folder for the instance.)
2. Navigate to the Moonstruck's Rebirth - A Better Cozy Experience folder or the directory where Xaero's data is stored.

![Xaero Data Folder Location](https://imgur.com/a/1aRXk1n)

### 2. Copy the Xaero Folder

1. Select the entire Xaero folder.
2. Copy the folder to your clipboard (e.g., right-click > Copy or Ctrl + C).

### 3. Replace the Xaero Folder in the New Installation

1. Open the file directory of the **new Minecraft installation**.
2. Check if there is an existing Xaero folder in the new installation:
   - If it exists, **delete it** to avoid conflicts.
   - Paste the copied folder from the old installation into this location (e.g., right-click > Paste or Ctrl + V).

### 4. Adjust for Server IP Changes (if necessary)

- If the **server IP address** has changed between installations, the map data may not appear in the new instance. To resolve this:
  1. Open the Xaero folder.
  2. Locate the subfolder named after the old server's IP address. (Both in minimap and world map)
  3. Rename the folder to match the new server's IP address.
  
  Example: `Multiplayer_server1.com` will become `Multiplayer_server2.org`.

### 5. Verify the Transfer

1. Launch Minecraft with the new installation.
2. Join the world or server to ensure the waypoints and map data are present.
3. If the data is missing, double-check the folder names and ensure they match the new server's IP or directory structure.

---

## Additional Notes

- Always back up your files before making changes to prevent accidental data loss.
- Screenshots can help verify folder structures and file paths for troubleshooting.
