A good tf2 config.
Originally Woolen's config, but with added version control + better things

Find your setup below

====I AM NOT A PROGRAMMER AND I JUST WANT TO GET GOOD====
Windows:
Green "clone or download" button -> Download ZIP
Copy the stuff in this folder to C:\Program Files\Steam\steamapps\common\Team Fortress 2\tf\custom\customConfig
Copy the stuff in 'classes' to C:\Program Files\Steam\steamapps\common\Team Fortress 2\tf\custom\customConfig
Make new folders if you need to.
You can delete them any time and re-verify in steam to undo everything.


====I AM A PROGRAMMER====
git clone git@github.com:willtheoct/.0tf2ofig.git

Make some symlinks to drag files quickly:
mklink /J "~custom" "/steamapps/common/Team Fortress 2/tf/custom"
mklink /J "~cfg" "/steamapps/common/Team Fortress 2/tf/custom/customConfig/cfg"
cd classes && mklink /J "~cfg" "/steamapps/common/Team Fortress 2/tf/custom/customConfig/cfg"

Put this project in your quick navigation links in explorer
Leave notepad++ open as you play, have classes folder open


DON'T EVER NOT USE GIT


If you make a bash script to set up the symlinks using the tf2 path as STD input, make a PR and I'll merge it



Yttrium's mod hides viewmodels for some weapons, which lets you see more. Run it to change which weps are hidden.
I think GCFScape is to put GIFs into TF2' sprays
Improved Default hud? I don't remember but it seems alright