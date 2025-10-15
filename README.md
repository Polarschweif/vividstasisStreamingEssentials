# vividstasisStreamingEssentials
*(formerly **vividstasisProfileReader**)*

---

> ⚡ **Note:**  
> When the command window opens, don’t worry — it’s only exchanging information with an internal browser  
> (e.g., checking the newest version, using the random song picker, etc.).  
> Upcoming event stats will be added as soon as they become available.

---

## Join my [Discord](https://discord.gg/XgwM76A3MD)

---

### 📚 Additional Documentation
- [Behind the Scenes](./BEHIND_THE_SCENES.md)

---

## About

`vividstasisStreamingEssentials` detects and displays your data from **vivid/stasis**,  
giving you a quick overview of your Points, Battery, Rating, and even your Soundscan Boosttickets.

It can also be used in an OBS scene by turning the background green:  
simply right-click anywhere and select **Greenscreen mode** to toggle between black and green.

---

## Changelog

### 1.0.0
- First prototype release

### 1.1.0
- Added achievement display

### 1.2.0 – QOL Update
- Added right-click menu  
- Re-order stats by dragging  
- Choose which stats to display  
- Customize background and text colors

### 1.2.1
- Fixed colors not saving

### 1.3.1
- Added **Key Overlay** with key counter  
- Bind a key to reset the counter

### 1.3.2
- Fixed keybindings not updating when changed in-game

### 1.3.3
- Added KPS counters (forgot them in 1.3.1, skill issue lmao)

### 1.3.4
- Fixed KPS not resetting

### 1.3.5
- Removed avg KPS due to inaccuracy  
- Renamed from *ProfileViewer* → *StreamingEssentials*

### 1.4.5
- Added **starfallsapphic’s Random Song Picker** 🎉 (not mine so **Big shoutout**)
- Fixed context menu not disappearing  
- Added “Help” (opens a PDF)

### 1.4.6
- Fixed “Always on top” not loading from config

### 1.4.7
- Fixed random song result not showing after rearranging stats

### 1.5.7
- Window now adapts to different aspect ratios  
- On startup, program checks for newer versions

### 1.6.7
- Added clock display next to *Profile-Overview* header
- Clock display can be en- and disabled
- You can toggle between 12h and 24h format

### 1.6.8
- Adjusted the amount of achievements due to an update of vivid/stasis

### 1.7.8 BIG update
- Fixed the achievement progressbar
- The program now saves its last position and boots up at this position again
- Added a message box appearing when there are news fot vividstasisStreamingEssentials
- News get written to NewsLog.txt to avoid getting the same notification more than once
- Changed the drag and drop mechanic for the profile informations to a simpler and more stable one.
   - Click a stat to select it
   - Scroll your mousewheel to move it
   - Click it again to deselect it or click a different one to change your selection
- Added a cancel button to the update message box wich leads to this website when an Update is out
  (It boots the program normally, message boxes only have ok and cancel and I am too lazy to make an extra window for it)
- Added a window to view all the variables and values running in the program (PASSWORD REQUIRED, only for dev usage!!!)

### 1.8.8 MASSIVE update (Release date tba, more info in the Discord server)
- overhauled the program itself by removing the title bar and added a custom one wich can be accessed by hovering over the gray trigger zone at the top. you can close and drag the wondow there.
- added social links
  - Discord 
  - This GitHub repository
- Added different modes
  - Greenscreen-Mode (I know that it has been existing since the first prototype)
  - Transparent-Mode (Turns the background transparent)
  - SemiTransparent-Mode (Turns EVERYTHING slightly transparent)
- Press F10 to enter the new code entry window. Codes soon (if there are some)
- The window cant be moved out of the screen so it cant be completely unaccessible when closed out of the screen
- Made the context menu (FINALLY) in a dark theme to not burn your eyes
- Cleaned up some unnecessary code (not really neccessary to mention here but it took me almost 2 hours)
- Fixed moving stats up or down only working while the mouse is on a stat. It works now when the mouse is somewhere on the application
  - (On tansparent background, the mouse is practically behind the window itself when it's on the transparent background. This doesnt apply to SemiTransparent-Mode)

---

## Upcoming Features
- Saving (relative) position so the window opens where it closed last time (coming in version 1.7)
- Removing the title bar (the thing that contains minimizing, closing, etc.) and still be able to move the window around (coming with version 1.7 or as an own update in 1.8)
- Having different tabs (4 in total planned), one for the quick profile overview, one for a list of the whole profile file for debug, one for every achievement and their completion and one for tamasatchi)
- thinking about a worldcross mode where the window is a bit smaller and only showing Name, Rating and Class for those who have StreamingEssentials on the right side (bc of worldcross' leaderboard thingy being also on the right side)
- having 3 slots of custom presets (basically 3 different config files) and a few pre-defined presets

---

## Community Ideas
*(none yet – contributions welcome!)*

---

## Screenshots
<img width="444" height="761" alt="grafik" src="https://github.com/user-attachments/assets/457c6da8-6116-4b73-aae7-87079f001873" />

<details>
  <summary></summary>
  Message of the day:

  I need some rest rn, dont feel mentally good at the moment
</details>
