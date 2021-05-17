# Colored Chat (Server-side mod) Install Guide
Follow these steps to install this mod.
## 1. Find your mod Directory
You mod directory may at these places
 - `$MINETEST_DIR/mods` (For RUN\_IN\_PLACE Build)
 - `~/.minetest/mods` (For non RUN\_IN\_PLACE Build)
## 2. Download this mod
You can download it from command line or from browser.
### Using Command Line
1. Change your current working directory to mod directory
2. download this mod by command
```
# Use git to download
git clone https://github.com/Emojigit/smod_colored_chat # if you want to use https to clone
git clone ssh://git@github.com/Emojigit/smod_colored_chat # If you want to use ssh to clone
# Or use gh(GitHub CLI)
gh repo clone Emojigit/smod_colored_chat
#You can also download the zip (not recommend)
wget https://github.com/Emojigit/smod_colored_chat/archive/master.zip && unzip -d ./smod_colored_chat && rm master.zip
```
### Using browser
1. Go to https://github.com/Emojigit/smod_colored_chat
2. Choose Code > Download ZIP
3. Unzip it after you download the mod zip
4. Move it into your mod directory
## 3. Enable it
### Edit world.mt
1. Loate your mod directory, it may at `$MINETEST_DIR/worlds` or `~/.minetest/worlds`
2. If you had a world, cd into it, if no, create a blank directory then cd into it.
3. Create or open `world.mt`
4. Add this line into world.mt (If your world.mt have a line like this, simply change `false` to `true`): `load\_mod\_smod\_colored\_chat = true`
### Using in-game formspec
1. Open minetest
2. Select world (You may need to choose game to find it)
3. Select Settings > smod\_colored\_chat
4. Enable it by change the `Enabled` from <ul><li>- []</li><li> to <ul><li>- [x]</li><li>
5. Press `Save` to exit








