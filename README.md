To use this skin, copy the desfult Estuary skin which comes with Kodi from the system addons directory to your user addons directory, then copy these files over the top of the originals.

Go into Kodi's settings and enable the addon, then set it to be your preferred skin. Configure the skin's settings to enable movie/tv certifications.

I've only added suport for en-gb localisation. Originally, for the Leia version that I'd produced, I'd done all English languages, but unfortunately some crybaby didn't like the the word "certification" in the Kodi code base as it didn't translate into an appropriate word in their language (ignoring the fact that Kodi has an English code base), so the modification wasn't accepting into Kodi.

The original Leia modfications worked on Matrix. Some updated were needed for Nexus, but I never published those, coz I pretty much forgot. It needed a significant rework for Nexus however. In the Nexus release, they decided to merge the TV's 'watched' icon (the eye) with the Movie's 'watched' icon (the tick). They had also been moved to where I'd placed the certificaion logos. I've had to split them into two separate objects again, moving them back to the original locations, plus add in the certification stuff.

It's all good now and I'm happy enough that I'm ready to push these mods again.

One thing to note. I use this skin on single-board computer devices (think Raspberry Pi if you're not familiar). These cannot be suspended or shut down, so I've removed them from the 'shut down' menu for non-Windows systems. Could be an issue on Linux computers. You'll need to command out, or remove, the lines `<visible>System.Platform.Windows</visible>` for the options you want to re-add. 
