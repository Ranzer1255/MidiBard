# ** MidiBard **

MidiBard is based on [Guardian Moon Frame](https://bbs.tggfl.com/topic/32/dalamud-%E5%8D%AB%E6%9C%88%E6%A1%86%E6%9E%B6) The powerful and easy-to-use poet midi performance plugin. The current version is compatible with both national and international servers.

# Main features
* No need for tedious key configuration, open and use
* One-key high-precision ensemble with Ensemble Assistant
* Audio track visualization, intuitively view the score effect
* Millisecond-accurate MIDI playback and zero key-press delay to maximize the restoration of song details
* The adaptive function of out-of-range notes saves the time of adapting midi files
* Built-in playlist and support search, import and play all your favorite songs at once
* One-click switching of instruments through plug-in interface/text commands, or automatic switching of corresponding instruments with song playback
* Select any track to play or ensemble at the same time, allowing you to switch/mute/solo/transpose any track at any time
* Good MIDI device support, automatically scan available MIDI devices and connect, the best MIDI keyboard playing experience
* Assign a different electric guitar tone to each track and play solo!

# Plugin interface
![image](https://user-images.githubusercontent.com/33274390/152686485-cc882039-3395-4e88-8568-efaf2b838406.png)

[![2NWbuT.png](https://z3.ax1x.com/2021/06/05/2NWbuT.png)](https://imgtu.com/i/2NWbuT)
[![2NhtTe.png](https://z3.ax1x.com/2021/06/05/2NhtTe.png)](https://imgtu.com/i/2NhtTe)

# installation method
> MidiBard requires [Guardian Moon Frame] (https://bbs.tggfl.com/topic/32/dalamud-%E5%8D%AB%E6%9C%88%E6%A1%86%E6%9E%B6) , if not installed, please refer to [original post](https://bbs.tggfl.com/topic/32/dalamud-%E5%8D%AB%E6%9C%88%E6%A1%86%E6%9E% B6) Continue after installation.

After installing the Weiyue framework correctly and injecting it, enter `/xlsettings` in the game chat box to open the Dalamud settings window and copy the source  
`https://raw.githubusercontent.com/akira0245/DalamudPlugins/api4/pluginmaster.json` and add it to the plugin repository  

[![gw7vxx.png](https://z3.ax1x.com/2021/05/12/gw7vxx.png)](https://imgtu.com/i/gw7vxx)

After adding it successfully, search for MidiBard in `/xlplugins` and install it.

# How to install
You need to add my custom plugin repository to install MidiBard.  
`https://raw.githubusercontent.com/akira0245/DalamudPlugins/api4/pluginmaster.json`  
Click the link below for more detailed instructions.  
https://github.com/akira0245/DalamudPlugins

# Use FAQ
**How ​​to start playing with MIDIBARD? **  
By default, the MIDIBARD window pops up automatically when a character enters performance mode. Click the "+" button in the upper left corner of the window to import the song file to the playlist. Only songs in .mid format are supported. Press Ctrl or Shift when importing to select multiple files to import together. Double-click the song you want to play in the playlist and then click the play button to start playing.

**How ​​to use MIDIBARD for multiplayer ensemble? **  
MIDIBARD uses the in-game ensemble assistant to complete the ensemble, please open the game's metronome window while ensemble. Before playing an ensemble, double-click the song you want to play in the playlist, and all the available tracks will appear below the player. Please select the track you want to play for each ensemble member. After selecting the track, the captain clicks the "Ensemble Preparation Confirmation" button in the Metronome window, and ensures that the "Use Ensemble Assistant" option is checked in the Ensemble Preparation Confirmation window, and then clicks Start to start the ensemble.  
Note: The first two bars of the metronome are preparation time, and the ensemble will officially start from bar 1. Considering that the loading speed of songs may be inconsistent in different usage environments, in order to avoid out-of-sync caused by switching songs, the ensemble will automatically stop at the end of the song.

**How ​​to make MIDIBARD automatically switch key and instrument for different songs? **  
Before importing, add “#<instrument name><number of semitones to transpose>#” before the file name of the song whose instrument and transposition are to be specified. For example: the original song file name is "demo.mid", and renaming it to "#Viola+12#demo.mid" will automatically switch to viola and play it in 1 octave when the song is played. Rename it to "#flute-24#demo.mid" to switch to flute and play it 2 octaves down when playing this piece.  
Note: You can only add #+12# or #harp# or #harp#, there will also be corresponding rise and fall or switch instrument effects.

**How ​​to configure an external Midi input (such as a virtual midi interface or a midi keyboard) for MIDIBARD? **  
Select your Midi device in the "Input Device" drop-down menu. After the message "Monitoring Midi Input" appears at the top of the window, you can use the external input.

**What should I do if there is a slight lag when playing in the background? **  
In-game *System Settings→Display Settings→Framerate Limit* uncheck *"Program to limit framerate when game window is inactive"* and apply the setting.

---
> This project is open sourced under the GNU Affero General Public License v3.0.  
> The source code of the project can be viewed at https://github.com/akira0245/MidiBard (the writing is bad and forced to open source  
> Welcome to add English translation and pr


# other problems

> If you have bugs or feature suggestions or discussions, you can add QQ group: 260985966
