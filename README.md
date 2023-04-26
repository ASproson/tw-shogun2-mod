# Total War: Shogun 2 Mod

Drop  this in your steam directory:

> C:\Program Files (x86)\Steam\steamapps\common\Total War SHOGUN 2

This mod provides Generals 6 skill points on level up. I made this just because I felt that the right branch of the skill tree was pretty useless compared to the left branch, so this method allows you to essentially pick both and potentially try some of the other options. It's on the Steam Workshop but wanted to store it here if the workshop ever disappears.

## How to Mod in TW:S2

If there's a pre-existing mod that you're modifying, it's easiest to open that, make your changes, save, and then export:

1. Get the pack file manager from SourceForge
2. Install && run PackFileManager.exe
3. Open that file, open the database tree, modify the pre-existing values
4. Export that file
5. Run the game, when the mod manager opens up tick your mod to turn it on in game

If isn't a pre-existing mod, essentially you'd have to:

1. Get the pack file manager from SourceForge
2. Install && run PackFileManager.exe
3. Load in the full database
4. Search the file you want to modify
5. Repeat the steps above

## Uploading your mod to the Steam Workshop

If you want to upload it to the steam workshop you need to take a few extra steps.

1. Once your .pack file is exported as above you'll initially see it in the folder `/Total War Shogun 2`, and it'll be within a folder that you named your mod
2. The mod **must** be one word like so: 6SkillPointsGenerals
3. In this folder you'll see your mod ending with the .pack file extension, copy this file
4. In `/Total War Shogun 2/Data` paste this file if it doesn't already exist
5. You'll need a **6SkillPointsGenerals.jpg** file in this folder. It **must** be named the same as the pack file. Any image will do, I just made something basic on GIMP as the thumbnail
6. Start the game and let the mod window open:

![image](https://user-images.githubusercontent.com/77736272/234576108-07e354a1-a131-4cc7-add0-df928503fb39.png)

7. Double click the name of your mod and fill in the Title and Description
8. Submit to the steam workshop

## Why not use BOB that comes with the Assembly Kit? 

It's pretty crash heavy in 2023 and I found it wasn't saving/allowing exporting. PackFileManager is more stable and seems happy with Windows 10/11
