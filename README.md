# TekOSC

<a rel="license" href="http://creativecommons.org/licenses/by-nd/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nd/4.0/">Creative Commons Attribution-NoDerivatives 4.0 International License</a>.
 
 ## What is this?
 TekOSC is an addon for VRSL that allows for dummy rig testing without needing to use uDesktopDuplicator.
 
 This gives you the ability to easily setup dummy rigs, as you don't have to mess with an OBS fullscreen preview or precise grid node placement on a secondary 16:9 monitor to test your lighting effects in a dummy rig.
 
 TekOSC currently supports horizontal and vertical grid orientations, and has support for up to 9 universes with the 'Expanded Universe Support' option (or RGB mode as VRSL calls it)
 
 ## Requirements
 
 This is an **ADDON** for VRSL. It assumes you have some basic knowledge of VRSL.
 
 To use this addon, you will need to install [VRSL](https://github.com/AcChosen/VR-Stage-Lighting) and its dependencies into your Unity Project, as well as purchase the VRSL lighting bridge node software [here](https://acchosen.gumroad.com/l/xYaPu) (I do not see any profits from the purchase of this software)
 
 ## Usage
 
 To use this addon:
 
 1. Set the grid node to allow OSC output (you may need to edit settings.properties to do this)
 2. Install the latest version of TekOSC by importing the .unitypackage
 3. Place the relevant Prefab, depending on if you are using the grid in vertical or horizontal mode, into the scene (TekView>Prefabs)
 4. If you are using "Expanded Universe Support" (Or RGB mode as the grid node calls it), check the 'Expanded Universe Support' option on the prefab
 5. Enter play mode and test your lighting!
 
 ## Issues/Bugs
 
 Please create an issue on this repo to report and issues or bugs and I will fix them as soon as I can.
 
 **Please include any relevant information to reproduce the issue/bug, I can't fix what I can't re-create!**
