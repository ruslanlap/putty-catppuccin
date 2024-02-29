# putty-catppuccin-theme

Here is a README file with instructions on how to use the Windows registry file to modify PuTTY color settings:

## Screenshots

![App Screenshot](https://github.com/ruslanlap/putty-catppuccin/blob/master/screenshoot.png)


# How to Modify PuTTY Color Settings to Cattpucin style

This README provides instructions on how to use the included Windows registry (.reg) file to modify the color schemes in PuTTY.

## Prerequisites

- PuTTY installed on your Windows machine
- The Catp.reg registry file included in this repo



## Installation

Install 

```bash
  cd C:\Users\$user\Downloads
```
```bash
  curl.exe -o Catp.reg https://github.com/ruslanlap/putty-catppuccin/blob/master/catp.reg
```

## Instructions

1. Download Catp.reg or copy it from this repo

    
2. Double click on Catp.reg to open the Windows Registry Editor
3. Click Yes to merge the registry file into the Windows Registry
4. Open PuTTY and go to Window > Saved Seesion
5. Select the "Catp" scheme from the Saved sessions dropdown 
6. Click Openy to apply the color scheme


## Other PuTTY Recommendations

```bash
Window > Apprearance
 Font: Consolas, bold, 12-point
 Font quality:
  ( ) Antialiased     ( ) Non-Antialiased
  (O) ClearType       ( ) Default
Window > Colours
 [X] Allow terminal to specify ANSI colours
 [X] Allow terminal to use xterm 256-colour mode
 Indicate bolded text by changing:
  ( ) The font   ( ) The colour   (O) Both
 [ ] Attempt to use logical palettes
 [ ] Use system colours
 ```


And you're done! The next time you open an SSH session in PuTTY it will use the customized Catp color theme.

Let me know if you have any other questions!

