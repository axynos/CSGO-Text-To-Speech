# CSGO-Text-To-Speech
AutoHotKey script to make TTS in CSGO.

####Prerequisites:
- CSGO
- [AutoHotKey](www.autohotkey.com)
- [Virtual Audio Cable](http://software.muzychenko.net/eng/vac.htm)
- [CheVolume](http://chevolume.com/)

####Instructions:
1.  [Download latest release](https://github.com/axynos/CSGO-Text-To-Speech/releases/tag/1.0-Initial)
2.  Extract script
3.  Open script with any text editor.
4.  Add in your logfile path in the variables section.
5.  Save and close your text editor.
6.  Create 2 VAC Lines.
7.  Open 2 instances of audiorepeater_ks
8.  Set them up like this: 
  
    ![alt tag](https://i.imgur.com/oIorEJT.png)

9.  Start CSGO
10. Open console any type this in: `con_logfile !tts-axynos`
11. Type `echo !tts ` and add something long to the end so you can do the next step.
12. Alt-Tab out, start the script and then start CheVolume
13. Press the button at the bottom(orange) and send it to "Line 1"
  
  ![alt tag](https://i.imgur.com/CmnRgeB.png)
14. Close CSGO
15. Open Steam go into settings and change your voice input to "Line 2"
16. Open csgo, enter this command: `con_logfile !tts-axynos; voice_loopback 1`
17. Go into game and then enter this command into console: `+voicerecord`
18. If all goes well you can now use !tts and should be able to hear the text to speech. Others should be able to hear it aswell.

#####Warning: Virtual Audio Cable can cause bluescreens because it's messing with sound drivers.
