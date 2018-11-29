# mute-individual-program
Can mute individual programs with hotkey

This is a modified version of 'mute-current-application', by kristoffer-tvera
https://github.com/kristoffer-tvera/mute-current-application

You need AutoHotKey installed to run this as it is not a compiled ahk file
https://www.autohotkey.com/download/

The default as is setup will mute spotify.exe with the F1 key. The application and hotkey are easily editable in the code. Edit the 'Application' variable for which exe to mute and edit which hotkey you want to use by using the following logic:

      ; Alt = '!'
      ; Control = '^'
      ; Shift = '+'
      ; +F1 then becomes Shift+F1 on keyboard.
      ; ^m then becomes Control+M on keyboard.
      ; ^+m then becomes control + shift + m on keyboard
      ; It is possible to stack multiple keybinds on top of each other to all perform the same action.
