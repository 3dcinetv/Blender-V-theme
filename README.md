# Blender-V-theme
🏆 Darker UI with context matching colors for selection, editing, highlighting through all the editors.
I created this theme because a lot of users in the community were asking for a darker theme that was sober to read even if you’re an experienced 3D user or a client gazing at the workspace. I wanted to make it easier for the UI to point to the little crucial buttons in the UI which were grayed when you click on them.

Unnecessary multi-colored bones are distracting, so the selected colored channels by Blender’s default theme add to the visual noise. All bone channels in the NLA, Graph editor, DopeSheet were edited to have sober colors. Everything about these choices are explained in a 14 minute video in the link at the end of the thread.

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

> You can see extensive details as to why these color choices were necessary in this video covering NLA, Tracker, Grease Pencil, VSE and other editors.



## INSTALLATION
For LOCAL, SYSTEM and USER paths relative to Blender in LINUX, MAC and PC, please refer <a href="https://docs.blender.org/manual/en/latest/advanced/blender_directory_layout.html" target="_blank">to this guide.</a><br>

For Blender 2.9x series:
1. Download your version theme file from this repo
2. Unzip and locate Softimage_292.xml
3. Open Blender. Go to Edit> User Preference

## Changelog:
SOFTIMAGE Theme v01. - Blender 2.9x series
  - "XSIMOD theme" name changes to "Softimage Theme" for Blender.
  - VSE and Movie clip custom workspaces were customized.
  - New previously non-existent workspaces i

Click on the following thumbnail to watch the **Blender V theme features in this video**:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=IbuVWQhV_uk
" target="_blank"><img src="http://img.youtube.com/vi/IbuVWQhV_uk/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="640" height="480" border="10" /></a>

## AUTHOR
<a href="https://github.com/3dcinetv" target="_blank">Pierre Schiller</a><br>

## DONATION
In case you find this theme helpful, you can donate by visiting [:white_check_mark: My BLOG](https://3dcinetv.com/blender-v-darker-ui-for-blender-to-showcase-your-work), and scroll to the bottom of the page through the Gumroad link.
