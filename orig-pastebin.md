# Enhanced Ocarina of Time VR Setup Guide - by BrianMp16

Join my Discord server to find up-to-date OoT VR files in #my-oot-documents
[Discord Server](https://discord.gg/2F8javw)

## HOW TO SETUP FOR YOURSELF

1. Download Kaze's first person OoT VR mod (see his YouTube video description):
   [Kaze's OoT VR Mod Video](https://www.youtube.com/watch?v=PbZmiz4emLI)

2. Open the mod in a Hex Editor (I recommend HxD) and change the first four bytes from "RELS" to "PZLE" by typing over them:
   [HxD Hex Editor](https://mh-nexus.de/en/hxd/)

3. Download and extract the latest Dolphin VR (latest build is 2016):
   [Dolphin VR Website](https://dolphinvr.wordpress.com/)
   [Dolphin VR Github](https://github.com/CarlKenner/dolphin)
       (Github: "Code" -> "Download ZIP")

4. Configure your ISO directory in Dolphin
       Dolphin: Config -> Paths -> Add -> (Choose folder containing the mod)

5. Modify Dolphin VR settings as follows:
   [OoTVR_Step_5.zip](https://example.com/OoTVR_Step_5.zip) found in my Discord (see above) #my-oot-documents

6. Download and Apply PZLE01.ini config file:
   [PZLE01.ini.zip](https://example.com/PZLE01.ini.zip) found in my Discord (see above) #my-oot-documents
       Dolphin: Right Click the mod in Dolphin -> Properties -> AR Codes -> Edit Config -> Copy and Paste the text from the downloaded PZLE01.ini file (open the file with Notepad)

7. Download and Apply BrianMp16's Action Replay Enhancing Codes:
   [AR Codes.zip](https://example.com/AR%20Codes.zip) found in my Discord (see above) #my-oot-documents
       Dolphin: Right Click the mod in Dolphin -> Properties -> AR Codes -> Show Defaults -> Copy and Paste the text from the downloaded P.ini, PZL.ini, and PZLE01.ini files, respectively (open the files with Notepad) (NOTE: this is a different PZLE01.ini file than from Step 6).  

8. Download BrianMp16's modified Zelda 64 UHD Texture pack (Original UHD texture pack by Admentus):
   [UHD Texture Pack](https://mega.nz/file/SKwg1DJA#REktKt0ATC4-rCNaGwDmbkUyKcUxuMTbek2gmHha22U)

9. Extract Downloaded Texture Pack to "C:\Users\[USERNAME]\Documents\Dolphin Emulator\Load\Textures"

10. Click "Play" in Dolphin and OoT VR will start shortly! If you have any questions, feel free to ask!

## NOTES (IMPORTANT READ)

- Kaze's first person VR mod: It isn't perfect. The mod activates the built in anti-piracy features in OoT. Thankfully, I was able to bypass the game-breaking ones with AR codes. Unfortunately, Adult Zelda's hair is still wild during cutscenes. Movement jittering is to be expected. Backflipping and sidehopping are not possible. The hookshot target will fill the screen with red when aiming - I fix this issue by making a transparent hookshot target in the modified texture pack. Lifting any of the 3 Golden Gauntlet Stones may softlock the game - always save beforehand. The one in the Fire Trial is guaranteed to softlock - never lift it.

- UHD Texture Pack: A .PNG version is required for this older Dolphin version. I had to modify many textures so they wouldn't crash Dolphin. Sky textures and a few other textures were redone because the .PNG pack contained invalid names (as a result of their .DDS counterparts). Night-time dark cloud sky textures are vanilla because I prefer them this way. Not every texture has a UHD version, but most do.

- AR Codes: I adapted and handmade some game enhancing AR codes for this mod, some of which are explained in more detail below.
- 30 FPS Hack: This sets the default frame rate to 30 FPS and has logic to revert back to 20 FPS under various situations. Pressing D-pad DOWN will manually set the game to 20 FPS and D-pad UP will manually set the game back to 30 FPS. This hack is not perfect. It was originally created by Admentus and I have since improved it to prevent softlocks and to allow the entire game to be beaten without needing to manually change the FPS. However, there are still a handful of unexpected results that can occur that may require the player to manually change back to 20 FPS. Most notably is talking to business scrubs.
- Cull Hack AR Code: This code works as expected 99% of the time. There is one known situation where the screen freezes in Hyrule Field when walking near some signs. Moving away from the signs will resume gameplay back to normal.
- 3 Silver Rupees to Complete Fire Trial AR Code: This code is needed because the mod will softlock after lifting the Golden Gauntlet Stone. Instead, you only need to collect the 3 possible silver rupees to open the door in the Fire Trial.
- Tower Collapse Bars Passable AR Code: The anti-piracy features prevents the bars from raising. Zelda will walk through them. This code allows Link to do the same.
- Equip Boots with D-pad Buttons AR Code: D-pad UP: Kokiri Boots. D-pad LEFT: Iron Boots. D-pad RIGHT: Hover Boots. Boots will only be changed if Link is an adult and owns the respective boots. This code was originally made by Admentus. This hack is not perfect. It will not update Link's speed when changing boots. Pausing or changing maps will fix this. Changing maps may change Link's boots unexpectedly if the code was used in the previous map.

## FOR VALVE INDEX USERS

OPTIONAL: Install Index360 to use your Valve Index Controllers as a Gamepad:
[Index360](https://www.reddit.com/r/SteamVR/comments/d5o2os/made_a_tool_to_use_index_controllers_as_a_regular/)

OPTIONAL: My Valve Index Controller Settings:
[Valve Index Controller Settings](https://mega.nz/file/7DgAkSjB#jezJBr7GpVpU127e3L1C_22SqiYMr5O75GvSRo6NI5Q)

- Left Hand Button Mapping: Trigger = L; Joystick = C-Stick; Joystick Press = D-pad LEFT; B (hold Grips) = X; A = B; Trackpad Down = D-Pad DOWN; Trackpad Up = D-pad UP
- Right Hand Button Mapping: Trigger = R; Joystick = Joystick; Joystick Press = A; B (hold Grips) = Y; B (let go of grips) = Start; A = A; Trackpad Down (hold Grips) = D-Pad Right; Trackpad Down (let go of grips) = D-Pad Left.

Gray Screen issue: This problem only occurs during the Ganondorf and Ganon fights for me. I figured out this is a problem with the Valve Index headset software. To solve this issue, change your computer's PCIe to Gen 3.0 in your computer's BIOS:
[Change PCIe to Gen 3.0](https://www.tomshardware.com/reviews/bios-keys-to-access-your-firmware,5732.html)

And that should sum everything up! Feel free to ask questions if you encounter any issues, enjoy!

If you want to see my OoT VR gameplay, visit my YouTube and Twitch channels!
[YouTube Channel](https://youtube.com/BrianMp16)
[Twitch Channel](https://twitch.tv/BrianMp16)
