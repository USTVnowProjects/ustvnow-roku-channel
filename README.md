# ustvnow-roku-channel
Roku channel providing placeshifting TV for US military and US citizens abroad

## Introduction
This is an installer for the USTVnow Roku channel.

## Prerequisites

### Your Roku IP address
You will need to know the IP address of your Roku device.
  - If you have a Roku TV, go to Settings > System > About. 
  - For all other Roku devices, go to Settings > About from your Roku device
  - Write down the number next to “IP Address”
  
### Enabling Developer mode  
  - This application requires that developer mode is enabled. Use your roku remote and follow the sequence:
    - HOME  three times
    - UP    two   times
    - RIGHT once
    - LEFT  once
    - RIGHT once
    - LEFT  once
    - RIGHT once
  - Select a simple PIN like 1234 when prompted

## Running the application
This application runs from a command or terminal prompt on your Windows PC or Mac.
  - For a Mac you will need to download and run `rokuloader-darwin-amd64`
  - For a Windows PC you will need to download and run `rokuloader-windows-amd64.exe`
  - Once downloaded, you will run the application from the directory it resides:
    - Use the `IP Address` and `PIN` you have written down for the `target` and `password`
    - Example: `C:\tmp>rokuloader-windows-amd64.exe -password 1234 -target 192.168.1.22` 
  - If successful, return to your Roku device and open the `USTVnow (dev)` channel

```
Usage of rokuloader:
  -password string
        Roku Developer PIN
  -target string
        Name or IP of device target (default "192.168.1.100")
```

## Project Status
This is a community project. Let us know if you think you can help!
