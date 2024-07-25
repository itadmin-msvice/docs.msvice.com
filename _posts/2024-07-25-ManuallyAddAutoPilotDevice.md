---
title: "Manually add device to Windows Autopilot service while OOBE"
date: 2024-07-25
layout: post
---


## While OOBE 

To collect Autopilot information in OOBE, you can:
- Run the Get-WindowsAutoPilotInfo Script to collect device hardware - https://learn.microsoft.com/en-us/autopilot/add-devices#directly-upload-the-hardware-hash-to-an-mdm-service
- Press Ctrl + Shift + D in Windows 11 OOBE to open Autopilot diagnostics and view configuration and deployment information

## In Intune

https://learn.microsoft.com/en-us/autopilot/tutorial/self-deploying/self-deploying-workflow
1.: Set up Windows automatic Intune enrollment
1.: Register devices as Autopilot devices
1.: Create a device group - no dynamic group, added GO 3 as member
1.: Configure and assign Autopilot Enrollment Status Page (ESP)
1.: Create and assign Autopilot profile
1.: Deploy the device
