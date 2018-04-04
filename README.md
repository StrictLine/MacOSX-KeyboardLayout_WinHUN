# MacOSX-KeyboardLayout_WinHUN
Hungarian (Windows) keyboard layout for Mac OS X (made by Ukele &amp; Karabiner)

1) Install Karabiner elements from https://pqrs.org/osx/karabiner/
2) Copy the _karabiner.json_ into ~/.config/karabiner folder (~/ stands for your user folder path)
3) Copy HungarianWin.keylayout into /Library/Keyboard Layouts/
4) Open Settings > Keyboard > Input sources and Add (+) the imported keyboard layout - you might find it in the section "Others" not in the list of Hungary
5) Be sure, that you selected the right Karabiner config from the tray icon menu (near to the top right corner of your Mac, rectangular icon) of Karabiner - you should be able to choose amongst "HUN_WIN => MacHUN (old Citrix Receiver) v1", "RDP 0/í replace" and "ZeroConf"

## Karabiner configs
 * HUN_WIN => MacHUN (old Citrix Receiver) v1 - older version of Citrix Receiver took the out-of-box Hungarian layout for remoting, this is a fix for that malfunctioning
 * RDP 0/í replace (default for me) - Microsoft RDP swaps this 2 keys out of unknown reason
 * ZeroConf - if you want to turn off Karabiner modifications
 
## Explanation
* modifying the layout by .keylayout (you might have used the Utility called Ukele in order to have a GUI for key replacements) has influence on the software level, that's some kind of override of the default layout
* however some apps access the keyboard layout on the kernel level, where you cannot change the original keyboard layouts. In this cases you might take advantage of key bindings by Karabiner Elements and you also may specify conditions in order to limit the scope to specific Apps/App Bundles.
