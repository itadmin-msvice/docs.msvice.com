---
title: "Manually add device to Windows Autopilot service while OOBE"
date: 2024-07-25
layout: post
---


## While OOBE 

To collect Autopilot information in OOBE, you can:
- Run the Get-WindowsAutoPilotInfo Script to collect device hardware - https://learn.microsoft.com/en-us/autopilot/add-devices#directly-upload-the-hardware-hash-to-an-mdm-service
- Press Ctrl + Shift + D in Windows 11 OOBE to open Autopilot diagnostics and view configuration and deployment information

# In Intune

Step 1: Set up Windows automatic Intune enrollment
Step 2: Register devices as Autopilot devices
Step 3: Create a device group
Step 4: Configure and assign Autopilot Enrollment Status Page (ESP)
Step 5: Create and assign Autopilot profile
Step 6: Deploy the device
