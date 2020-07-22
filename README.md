# ru-phonetic-dvorak macos layout

## Install

1. Open Ukelele and choose File > New From Current Input Source. In new versions of Ukelele, it also assigns a new ID to the keyboard layout automatically.
2. Edit the keyboard layout.
3. Save the keyboard layout to some temporary location like the desktop. (Saving directly to /Library/Keyboard Layouts/ fails silently.) You can use either of the two formats. The iOS-style popovers shown when holding keys only work with the bundle format. The single XML file (default) format is simpler though. When using XML, make sure that the file is saved with a .keylayout extension.
4. Move the keyboard layout to /Library/Keyboard Layouts/. Keyboard layouts in ~/Library/Keyboard Layouts/ can't be selected in password dialogs or on the login window.
5. Restart the computer. Logging out and back in is not enough.
6. Enable the new keyboard layout from System Preferences.

To apply changes to a keyboard layout, run sudo touch /Library/Keyboard\ Layouts/ and restart.

See https://web.archive.org/web/20151030180252/http://osxnotes.net/keylayout-files-and-ukelele.html for more information.

