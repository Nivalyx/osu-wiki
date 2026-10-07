# osu! program files

::: alert-note
**See also:** [osu! File Formats](/wiki/Client/File_formats)
:::

![The file structure of osu!'s installation folder, on Windows and macOS](img/file_structure.jpg "The file structure of osu!'s installation folder, on Windows and macOS")

The **osu! program files** are a set of files that osu! uses to run the game and keep track of different user activities. These files come prepackaged with osu!'s installation and are crucial for the game's routine operations.

## Location

All of osu!'s program files are present in the game's [installation folder](/wiki/Client/Installation), which by default can be found in the following locations:

| Windows | macOS |
| :-- | :-- |
| `C:\Users\<Username>\AppData\Local\osu!` | `/Applications/osu!.app/Contents/Resources/drive_c/osu!` |

## Folders

### Chat

The Chat folder stores the logs of chats that have been saved by the user. This folder will only appear if the player has the `Automatically log private messages` options enabled, or if they have run the `/savelog` command in the [chat console](/wiki/Client/Interface/Chat_console) at least once.

These logs are named following the `{Tab_name}-{YYYYMMDD}-{HHMMSS}` format, and are preserved in a plain text (`.txt`) format that can be opened in any text editor. For example, a chat log with the name 
``#multiplayer-20121115-040845.txt`` indicates that this log comes from a `#multiplayer` chat and was saved on Thursday, 15 November 2012 at 04:08:45 local time.

### Downloads

The Downloads folder stores the beatmap files that are in the process of being downloaded by [osu!direct](/wiki/osu!supporter#osu!direct) (requires [osu!supporter](/wiki/osu!supporter)). These beatmap files will be transferred to the Songs folder once the download is finished.

### Exports

The Exports folder stores the beatmaps and skins the player has exported from the game client. This folder will only appear once the player has used the [skin selector's "Export as .osk"](/wiki/Client/Options) or [beatmap editor's "Export Package"](/wiki/Client/Beatmap_editor/Menu) option at least once.

### Localisation

The Localisation folder stores the files that are used to replace the game's English texts to the user's selected language. This folder will only appear once the player has switched their language in the options at least once.

### Replays

::: alert-notice
**Notice**
Older replay files may suffer from playback issues as they were recorded at a lower sample rate.
:::

The Replays folder holds the player's replay files. A replay file does not work when the beatmaps linked to it is missing. The replay also contains the results data, and reanimates the player's cursor movement while replaying. To create a replay, press F2 at the results screen, or click on the 'Save replay to Replays folder' (in Solo only).

*For players who interested in uploading their replay to YouTube, see: [Osr2mp4 public release. Automatically convert replay file to video.](https://osu.ppy.sh/community/forums/topics/1104243)

The file name structure is `{Local player name} - {Artist} - {Title} {[Difficulty]}{(YYYY-MM-DD)} {Game Mode}`. An example of this is shown below:

``dummytest1 - Loituma - Ievan Polkka \[SPINNER-MADNESS\] (2013-08-12) OsuMania``

### Screenshots

The Screenshots folder holds screenshots the player has created in osu!. By default, the saved screenshot's file extension is `.jpg`, however this can be changed to `.png` in the Options menu.

::: alert-notice
**Notice**
To create a screenshot, press the screenshot key (F12 by default).
:::

The file name structure is `screenshot###`, where "###" is the screenshot number count.

### Skins

The Skins folder holds user-created skins, which can be used to customise the in-game interface. Players can download skins from the [Skinning subforum](https://osu.ppy.sh/community/forums/15). Players can install skins by double-clicking on the skin from a file manager. "osu! by peppy" is the only skin without its folder and cannot be deleted.

::: alert-note
**Note:** For further reference, see [Skinning](/wiki/Skinning)
:::

### Songs

The Songs folder holds the player's osu! beatmaps. Usually contains `.osu` (difficulties), `.mp3`/`.ogg` (music files), `.jpg`/`.png`/`.gif` (background images), `.osb` (storyboard files) and `.mp4`/`.flv` (video files). May also contain `.wav`/`.ogg` (hitsound files) and folders (storyboard sprites and/or skin folders).

The file name structure is `{Beatmap number} {Artist} - {Song Title}`.
**Example:** [57950 SOUND HOLIC - Drive My Life](https://osu.ppy.sh/beatmapsets/57950)

Please note that some very old beatmaps (for example, [Kenji Ninuma - DISCO PRINCE](https://osu.ppy.sh/beatmapsets/1) or [Dudelstudios - Angry Video Game Nerd Theme [MATURE CONTENT]](https://osu.ppy.sh/beatmapsets/66)), as well as unsubmitted beatmaps, do not follow the format.

## Hidden folders

These folders are hidden because any modifications to them could prevent osu! from starting correctly, or at all.

### Data

osu! data files. Contains some of osu!'s cache, like beatmap background cache and avatar caches. They should not be deleted, because they may be in use by osu!.

## Files

::: alert-caution
**Caution**
Be careful with these files, you might break osu! if you are not careful.
:::

### Database files (.db)

The database files are databases that osu! requires to function properly. The files contain vital information that osu! requires, such as saved scores, and the cached list of beatmaps saved on the player's device.

- `collections.db`: Stores the player's "Collections" in-game.
- `osu!.db`: Stores osu!'s database of beatmaps.
- `presence.db`: Stores a cache of osu!players logged in the Chat Console.
- `scores.db`: Stores the local leaderboards.

### .cfg (Configuration files)

Configuration files configure the initial settings for osu! to work. The files can be opened with a text editor.

- `osu!.cfg`: Stores security information about the osu! application files and current release stream. This should never be modified manually.
- `osu!.<operating system username>.cfg`: Stores [Options](/wiki/Client/Options) data and other game settings. See [User Configuration File](/wiki/Client/Program_files/User_configuration_file).

### .exe (Application)

The main component. Click on it to start-up (only applies to Windows). The .exe files are safe to open assuming the player used the osu!installer downloaded from the official website to install osu!.

osu!.exe (Start-up osu!)

### .dll (application extension)

These .dll files are osu!'s components and dependencies.
