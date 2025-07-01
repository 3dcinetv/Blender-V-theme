# Stylize-V theme
🏆 Darker UI with context matching colors for selection, editing, highlighting through all the editors.
I created this theme because a lot of users in the community were asking for a darker theme that was sober to read even if you’re an experienced 3D user or a client gazing at the workspace. Created in 2022.

Unnecessary multi-colored bones are distracting, so the selected colored channels by Blender’s default theme add to the visual noise. All bone channels in the NLA, Graph editor, DopeSheet were edited to have sober colors. Everything about these choices are explained in a 14 minute video in the link at the end of the thread.

![Highlight pressed menu button](/img/Theme_win_bg.webp)
*ImageEditor, Background color matches dark gray theme*

![Highlight pressed menu button](/img/Blender-Neutral-bone-colors02.webp)
*DOPESHEET, NLA tracks in neutral color and selectable/editable in green*

Movie clip editor (a.k.a the TRACKER) didn’t work with most of the settings it had, I already reported them as bugs. Aside from that, the CRUCIAL parameters as well as the playhead are not obvious from the Blender default theme and I switched them to bright orange, since ALL of the tracking operations reside in these (hidden by the default grey color) tabs.
![Highlight pressed menu button](/img/Blender-Tracking03.webp)
*Crucially important parameters to track are located in the tabs, now identified in orange.*

When big files load the “blue-cyan” color of the bar, which is used everywhere else for SELECTIONS, doesn’t communicate clearly that there is a background process being “completed”.
Hence, Blender V switches the color of the progress bar to something that presents a completed process in GREEN COLOR.

Green (in different shades) is what we use in Blender for the keyframes, in the dope sheet, in the NLA in the graph editor, it only makes sense for the new user that all of these key-to-screen colors for completing a task are presented in Green as in “ready” state.

Also, I can’t emphasize enough how important is for the new user to READ the outliner properly when you have multiple selections. In Blender V, last selected is Cyan blue and Active selection is White.

![Highlight pressed menu button](/img/Loading04.webp)
*Green progress bar for compiling shaders and renders. Ready to go!.*

![Highlight pressed menu button](/img/Selections05.webp)
*New users can quickly identify which is the last selected and the active selected elements.*

> You can see extensive details as to why these color choices were necessary in video presentation at the bottom of this page covering NLA, Tracker, Grease Pencil, VSE and other editors.



## INSTALLATION
For LOCAL, SYSTEM and USER paths relative to Blender in LINUX, MAC and PC, please refer <a href="https://docs.blender.org/manual/en/latest/advanced/blender_directory_layout.html" target="_blank">to this guide.</a><br>

For Blender 2.9x to 3.4 series:
1. Download your version theme file from this repo
2. Unzip, and locate Blender_V_v02-4.xml
3. Open Blender. Go to Edit> User Preferences> Themes> Install theme> Select Blender_V_v02-4.xml from your unzipped folder location
4. Blender's UI will change color
5. In Blender go to FILE> Open, select "startup.blend" (from the unzipped config folder). This will open an empty file with all the tab presets ready
6. File> Defaults> Save Startup file
7. Quit and Restart Blender. You should see Blender V theme active.
8. If you want to further resemble the preferences I use on my videos, copy "userpref.blend" from the unzipped "config" folder, and paste it
into C:\Users\YOURUSER\AppData\Roaming\Blender Foundation\Blender\3.4\config (Windows Blender Path). Click "accept" to replace the file. Otherwise just delete the "userpref.blend" file from the unzipped folder and create your own preferences inside Blender (text size, text colors, etc...)


## Changelog(May 202%):
Blender_V_v02-5
  - "Image Render Background set to darker gray" 

## Changelog:
Blender_V_v02-4
  - "Color compatible editing spaces" Green: Animatable (keyframes, nla), Yellow (editable: Uvs, vertex, mesh), White (main selections), Blue (secondary selected items), NLA clips are yellow because they are editable containers for animation, if you press TAB they will turn green, giving you the context of "keyable" editing.
  - VSE and Movie clip custom workspaces were customized.
  

Click on the following thumbnail to watch the **Blender V theme features in this video**:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=IbuVWQhV_uk
" target="_blank"><img src="http://img.youtube.com/vi/IbuVWQhV_uk/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="640" height="480" border="10" /></a>

## AUTHOR
<a href="https://github.com/3dcinetv" target="_blank">Pierre Schiller</a><br>

## ALT Link
In case you find this theme helpful, you can visit [:white_check_mark: My BLOG](https://3dcinetv.com/blender-v-darker-ui-for-blender-to-showcase-your-work), and scroll to the bottom of the page through the Gumroad link.
