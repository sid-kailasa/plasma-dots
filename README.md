#### External Themes:

- **Wallpaper:** Smart Video Wallpaper Reborn
     > - Right click on the desktop, select 'Desktop and Wallpaper', then click on 'Get New Plugins'.
     > - There, you should see it as the first plugin, but if you don't, you can always search it.
     > - The blur that exists only when floating windows are open can be configured in the 'Playback' tab.
     > - You can use any live wallpaper with it, but make sure to change the accent colors in the cava theme file(.config/cava/themes/) as deemed convenient.

- **SDDM Theme:** [sddm-astronaut-theme](https://github.com/Keyitdev/sddm-astronaut-theme)
     > - To use the sddm theme, install the above original theme and copy the backgrounds in sddm/Backgrounds to sddm-astronaut-theme/Backgrounds and the config file in sddm/Themes to sddm-astronaut-theme/Themes.
     > - Then, open the scripts.sh from the cloned sddm-astronaut-theme folder using your preferred code editor and add "yor_forger" to the THEMES array that has elements starting with "astronaut" and "black_hole".
     > - Finally, run the same scripts.sh you just edited using the terminal, highlight on 'Select Theme Variant' and click enter. Then, scroll down to yor_forger, select it, and click enter to confirm.
     > - There you have the sddm theme! You might need to reboot to see the changes.
     >   <br/>
     >   <br/>
     **TIPS:**
     > - You can preview the theme without logging out using the following command: <br/>
     > ```sddm-greeter-qt6 --test-mode --theme /usr/share/sddm/themes/sddm-astronaut-theme/```
     > - You can also replace the original sddm-astronaut-theme/Main.qml with my sddm/Main.qml if you want the custom padding visible in my login screen.
     > - You can make your own configurations by copying/editing the presets the kind owner of the original theme provided.
     > - Every time a change is made, you need to reinstall the theme into sddm using "Install Theme" after running the local setup.sh to see the change.

- **Discord:** [Vencord](https://vencord.dev/download/) + [Midnight Theme](https://betterdiscord.app/theme/midnight)
     > - Found in discord/midnight.theme.css, this theme is a modification of the original Midnight theme linked above. Credits go to the original creators.
     > - Download Vencord using the link above, place the css in .config/Vencord/themes/, and restart discord.
     > - Then, go to Settings -> Themes(under Vencord Settings), "Load Missing Themes" if not present, and enable the Midnight theme.
     > - The css file has custom --custom-* and transparent --bg-* colors. Feel free to edit them if you feel like it.

- **Global color scheme:** Breeze Dark with a green accent color
     > - The cava color config file can be placed in ".config/cava/themes/".
     > - After placing it there, open .config/cava/config (generated after the first cava run) with your preferred code editor and replace any existing theme = * line with theme = 'cava'.

- **Terminal:** Konsole + Orchis Konsole Theme + JetBrains Mono Font
     > - To get the theme, you'll need to make a new profile in Konsole and set it as the default, then right click and click on 'Edit Current Profile'.
     > - After that, go to 'Appearance' -> 'Get New' and search for "Orchis".
     > - Download the Orchis Konsole Theme and you can apply it in the appearance tab itself.
     > - The font is JetBrains Mono, size 12. download it using ```zypper install jetbrains-mono-fonts``` and you can apply that in 'Appearance' as well.
