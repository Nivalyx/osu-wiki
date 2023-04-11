# AiMod

![](img/AiMod.jpg "The AiMod window lists warnings and errors about a beatmap.")

**AiMod** is a tool built into the [beatmap editor](/wiki/Client/Beatmap_editor) that detects problems in a [beatmap](/wiki/Beatmap). It can be opened via the menu option `File` > `Open AiMod` or the [shortcut keys](/wiki/Client/Keyboard_shortcuts) `Ctrl` + `Shift` + `A`.

While AiMod can be useful for catching basic issues in a map, it is not a replacement for [modding](/wiki/Modding) done by real people. AiMod cannot evaluate the quality of a map or pick out complex issues such as poor [patterning](/wiki/Beatmap/Pattern) or [timing](/wiki/Guides/How_to_Time_Songs). When [creating a map](/wiki/Beatmapping), it is recommended to fix AiMod's warnings first, then ask for other [modders'](/wiki/Modding/Modder) help.

Development of AiMod usually lags behind the standards held by the mapping community and [ranking criteria](/wiki/Ranking_Criteria), and as a result, [some of its output is considered incorrect](#flaws).

## Tabs

- **All:** Gathers the items from the other tabs.
- **Compose:** These problems are generally the problem of object placement. You may need to check the "Check distance snap" box for these warnings to appear (as these checks could cause lag, depending on beatmap size/length).
- **Design:** These problems are generally some of the interface issues, such as the background, storyboards, etc.
- **Timing:** When these problems appear, check the timeline because something is probably placed incorrectly.
- **Meta:** When these problems appear, check the song setup.
- **Mapset:** These problems affect the mapset as a whole.

## Messages

*Note: Numbers inside curly brackets (e.g. `{0}`) are placeholders for a number or a word.*

### Informational

#### All

| Message | Explanation | Solution | Notes |
| :-- | :-- | :-- | :-- |
| No problems were found in this map! | *Self-explanatory* | Your beatmap is good to go! You may upload your beatmap using BSS to allow modders to find other mistakes and issues with your beatmap. |  |

#### Meta

| Message | Explanation | Solution | Notes |
| :-- | :-- | :-- |  :-- |
| HP rate for Easy/Normal is suggested to be at least 4. | *Self-explanatory* | Go to Song Settings and set HP rate to 4 or higher. | ![](/wiki/shared/mode/mania.png) osu!mania maps only |
| HP rate for Hard and up is suggested to be at least 7. | *Self-explanatory* | Go to Song Settings and set HP rate to 7 or higher. | ![](/wiki/shared/mode/mania.png) osu!mania maps only |
| OD rate for maps with few sliders is suggested to be at least 7. | *Self-explanatory* | Go to Song Settings and set OD rate to 7 or higher. | ![](/wiki/shared/mode/mania.png) osu!mania maps only |
| The Slider Velocity should be 1.40 or 1.60. | *Self-explanatory* | Go to Timing tab and change Slider Velocity to 1.40 or 1.60. | ![](/wiki/shared/mode/mania.png) osu!mania maps only |

### Errors

#### Compose

| Message | Explanation | Solution | Notes |
| :-- | :-- | :-- |  :-- |
| These two objects are less than 10ms apart! | Two objects are placed very close to each other timeline-wise, requiring the player to click both objects almost simultaneously. | Find the two objects and either move or delete one of them. | |
| These two objects exist at the same point in time! | Two objects are placed exactly on top of each other timeline-wise, requiring the player to click both objects simultaneously. | Find the two objects and either move or delete one of them. | |
| There are no hitsounds on any objects. Hitsounds are required for rankable beatmaps. | *Self-explanatory* | Hitsound the map using whistles, claps and finishes. | |
| This spinner appears onscreen later than objects which follow it. | Objects appear while the spinner is active. This could be caused by having low AR and/or placing objects too close (timeline-wise) to the spinner. | Change the length of the spinner and/or remove the following objects. | |
| This hold note is less than 10ms long! | A hold note is presented at an unreasonably short length, rendering the map impossible to SS. | Increase the length of the hold note or remove it. | ![](/wiki/shared/mode/mania.png) osu!mania maps only |
| This object overlaps with another object. | Two objects are overlapped by each other on the same column in time, rendering the map impossible to SS. | Remove one of the overlapping objects. | ![](/wiki/shared/mode/mania.png) osu!mania maps only |
| This object is stacked on top of another object. | Two objects are stacked on top of each other on the same column in time, rendering the map impossible to SS. | Find the stacked keys or hold notes and either move or delete one of them. | ![](/wiki/shared/mode/mania.png) osu!mania maps only |
| More than 6 notes simultaneously is not allowed. | One or more patterns in the map requires the player to actively press more than 6 keys at a time. This is prohibited by the [osu!mania ranking criteria](/wiki/Ranking_Criteria/osu!mania) as most keyboards can only allow up to 6 key presses at once due to a phenomenon known as [ghosting](https://nelson-miller.com/what-is-keyboard-ghosting-and-how-do-you-prevent-it/). | Check your beatmap to make sure that each column has at most 6 simultaneous note presses. | ![](/wiki/shared/mode/mania.png) osu!mania maps only |

#### Design

| Message | Explanation | Solution | Notes |
| :-- | :-- | :-- |  :-- |
| Your beatmap has no background image. | *Self-explanatory* | Find a suitable image and use it as the background image. | Videos don't count as background images because the user isn't required to download them. |
| File missing:{0} | Your beatmap is missing certain files. | Recover the missing files or make sure the beatmap is not trying to use non-existent files. | |

#### Timing

| Message | Explanation | Solution | Notes |
| :-- | :-- | :-- |  :-- |
| All timing sections have a volume below 5%. | *Self-explanatory* | Set at least one timing section to have a hitsound volume of 5% or higher. | |

#### Meta

| Message | Explanation | Solution | Notes |
| :-- | :-- | :-- |  :-- |
| Drain time should be over 30 seconds. | The length of your map from start to end, not including breaks times, is under 30 seconds. | Try using a spinner to end the map if your song supports it. Otherwise, your song may be too short. In such case, try to extend your .mp3 file in order to reach the 30 second mark. | AiMod does not detect spinners which may extend over the 30 second drain time mark. |

### Warnings

#### Compose

| Message | Explanation | Solution | Notes |
| :-- | :-- | :-- |  :-- |
| This slider moves in an abnormal way. | The slider moves in a way that overlaps itself by going straight back into the track where it came from (otherwise known as a [burai slider](/wiki/Beatmapping/Mapping_techniques/Unrankable#burai-sliders)). | Make sure that the slider doesn't perfectly overlap itself on its path. | |
| Slider has an absurdly large amount of points! | *Self-explanatory* | Remove some of the anchor points from your slider. | This warning can be safely ignored if the design of the slider in question is intentional, e.g. on complex [slider arts](http://osu.ppy.sh/community/forums/topics/689531) or sliders made using the [Mapping Tools](https://mappingtools.github.io/)' Tumour Generator plugin. |
| This combo is very long. Consider splitting it up. | *Self-explanatory* | Split the long combo chain into several group of combos. It is preferred that length of the combos are, at most, 15-18 objects each. | Most notable in ![](/wiki/shared/mode/catch.png) osu!catch maps, where fruits will continue to ramp up on the catcher's plate as long as the combo chain remains intact (therefore potentially impairing visibility). This warning can be safely ignored if the usage of the long combo chain in question is intentional. |
| Object's end is offscreen! | The object's end is not on-screen (whether fully or partially) on 4:3 resolution. | Remove the object or move the position of the object's end. | AiMod doesn't always detect the upper bounds of the playfield properly, so make sure to verify whether the object's end in question is actually offscreen or not from time to time. |
| Object is offscreen! | The object is not on-screen (whether fully or partially) on 4:3 resolution. | Remove or move the object. | AiMod doesn't always detect the upper bounds of the playfield properly, so make sure to verify whether the object in question is actually offscreen or not from time to time. |
| This object is too close to the previous object. | *Self-explanatory* | Move the object further away from the previous one. | Only visible with the `Check distance snap` option enabled. |
| This object is too far from the previous object. | *Self-explanatory* | Move the object closer to the previous one. | Only visible with the `Check distance snap` option enabled. |
| This spinner is too short. Auto must achieve at least 1000 bonus points on spinners. | The specified spinner is too short, rendering it unable to properly function as a spinner. | Extend the length of the spinner. | |
| Spinners must have a new combo. | *Self-explanatory* | Manually add a new combo to the spinner. | |
| <!-- Potential removal? Wasn't able to make an actual object (not including slider ends) go offscreen as editor forced it back in again -->Object isn't snapped! | The specified object isn't snapped onto the timeline. | Check the timing, if you made a change to it, you may need to resnap all the notes (you can do this manually or click Timing » Resnap all notes (if you do this, you will need to check to see if any notes were placed in the wrong spot!)). | This warning can be safely ignored if the object is intended to be snapped to a divisor that's not supported by the editor (e.g. 1/11). |
| Object's end is not snapped! | The specified object's end isn't snapped onto the timeline. | Check the timing, if you made a change to it, you may need to resnap all the notes (you can do this manually or click Timing » Resnap all notes (if you do this, you will need to check to see if any notes were placed in the wrong spot!)). |

#### Design

| Message | Explanation | Solution | Notes |
| :-- | :-- | :-- |  :-- |
| Background image is larger than 2560x1440. | *Self-explanatory* | Resize or replace the background image. |
| This map may need an epilepsy warning, as it contains frequently toggled storyboards. | The storyboard elements change very quickly. | Enable the `Display epilepsy warning (storyboard has quick strobing)` option in the Design tab of the [song setup](/wiki/Client/Beatmap_editor/Song_Setup). |
| <!-- Not sure how to test this one -->{0}'s dimensions must be {1}x{1} | The dimension of the specified design element does not match its intended default. | Resize the design element in question to its proper resolution. |
| Your video's dimensions must not exceed 1024x768 for the 4:3 format. | *Self-explanatory* | Resize or replace the background video. |
| Your video's dimensions must not exceed 1280x720 for the 16:9 format. | *Self-explanatory* | Resize or replace the background video. |

#### Timing

| Message | Explanation | Solution | Notes |
| :-- | :-- | :-- |  :-- |
| This beatmap is over 6 minutes long. Consider shortening it if it's not a marathon-style map. |  |  |
| Your beatmap is shorter than 45 seconds. Consider making it longer. |  |  |
| <!-- Potential removal? Not sure if this is broken, but AiMod doesn't seem to detect an issue when I use a 320Kbps audio file -->Audio bitrate is higher than 192kbps. Consider recompressing to CBR 192kbps or VBR ~1.0. |  |  |
| <!-- Same as above -->Audio bitrate is lower than 128kbps. Consider finding a better quality source. |  |  |
| Kiai time is toggled on for less than 15 seconds. | *Self-explanatory* | Extend the duration of Kiai time to longer than 15 seconds. |
| The mp3 you are using is a lot longer than the part which is mapped. Consider cropping it to reduce filesize. | *Self-explanatory* | Extend the beatmap or cut the song. |
| Kiai needs an end time point. |  |  |
| A preview point for this map is not set. Consider setting one from the Timing menu. |  |  |
| Two timing points exist at the same time! |  |  |
| {0} out of {1} timing sections have a volume below 5%. |  |  |
| More than 1/3 of the map is Kiai time. Consider reducing this. |  |  |
| More than 1/2 of the TV Size map is Kiai time. Consider reducing this. |  |  |
| Kiai isn't snapped! |  |  |
| Kiai's end isn't snapped! |  |  |
| Breaktime is not suggested for mania maps. | osu!mania maps only! | Insert notes where the break time occurs. |
| <!-- Can't confirm -->Easy/Normal diff contains too many speed changes. |  |  |
| <!-- Can't confirm -->Kiai is toggled very frequently! |  |  |

#### Meta

| Message | Explanation | Solution | Notes |
| :-- | :-- | :-- |  :-- |
| [Stack leniency](/wiki/Beatmap/Stack_leniency) is larger than 0.9 or smaller than 0.3. | The Stack Leniency slider in the Advanced tab of Song Setup is set to either less than 3 or greater than 9. | Set the Stack Leniency slider so that it is between 3 and 9. | This warning can be safely ignored if the usage of the stack leniency in question is intentional. |
| <!-- editor removes any unicode automatically, but this warning probably still exists -->Romanised artist contains unicode. |  |  |
| <!-- editor removes any unicode automatically, but this warning probably still exists -->Romanised title contains unicode. |  |  |
| Countdown is not allowed in mania mode. | osu!mania maps only! | Uncheck `Enable countdown` in the "Design" tab in Song Setup. |
| Letterboxing is not allowed in mania mode. | osu!mania maps only! | Uncheck `Letterbox during breaks` in the "Design" tab in Song Setup. |
| OD rate is suggested to be at least 5. | osu!mania maps only! | Set `Overall Difficulty` in the "Difficulty" tab in Song Setup to 5 or higher. |
| OD rate for maps with very few sliders is suggested to be at least 7. | osu!mania maps only! |  |
| <!-- Both seem to occur, not sure what changes the value -->OD rate for maps with very few sliders is suggested to be at least 8. | osu!mania maps only! |  |
| <!-- potential removal? tried using countdown on taiko maps, and aimod does not complain -->Countdown is not allowed in taiko mode. | osu!taiko maps only! |  |
| <!-- same as above -->Epilepsy warning is not allowed in taiko mode. | osu!taiko maps only! |  |
| Letterboxing is not allowed in taiko mode. | osu!taiko maps only! |  |

#### Mapset

| Message | Explanation | Solution | Notes |
| :-- | :-- | :-- |  :-- |
| Artist conflicts with {0} diff. |  |  |
| Audio file conflicts with {0} diff. |  |  |
| Countdown conflicts with {0} diff. |  |  |
| Audio lead-in conflicts with {0} diff. |  |  |
| Letterbox in breaks conflicts with {0} diff. |  |  |
| Audio preview time conflicts with {0} diff. |  |  |
| Source conflicts with {0} diff. |  |  |
| Tags conflict with {0} diff. |  |  |
| Title conflicts with {0} diff. |  |  |
| Unicode artist conflicts with {0} diff. |  |  |
| Unicode title conflicts with {0} diff. |  |  |
| This mapset cannot have an Insane diff without a Hard diff. |  |  |
| Beatmap exceeds allowed upload size ({0}kb allowed) | The zipped `.osz` file is too large |  |
| This mapset needs an easier difficulty |  |  |
| This mapset is missing diff: {0} |  |  |
| This mapset needs at least 2 osu!catch diffs. | osu!catch maps only! |  |
| This mapset needs at least 1 Easy/Normal diff. |  |  |
| This mapset needs at least 2 osu!mania diffs. | osu!mania maps only! |  |
| This mapset needs at least 2 standard diffs. | Standard maps only! |  |
| This mapset needs at least 2 osu!taiko diffs. | osu!taiko maps only! |  |
| Uninherited timing points conflict with {0} diff. |  |  |

## Flaws

- **AiMod cannot detect a large number of issues** that are considered unrankable by the [ranking criteria](/wiki/Ranking_Criteria), such as potentially missnapped objects, delayed hitsounds, background filesize above 2.5MB, etc.
- **AiMod may warn you of non-issues**, such as the mapset needing two standard difficulties on a [marathon](/wiki/Beatmap/Marathon) map and [kiai time](/wiki/Gameplay/Kiai_time) being toggled on for less than 15 seconds.
- **If `Check distance snap` is enabled, AiMod will not check the distance snap between combos.**
- **If there are multiple MP3 files in the beatmap folder, AiMod may warn you of multiple song files**, however MP3 files can also be used for sound effects such as applause.

It is recommended to use other programs such as [Mapset Verifier](https://github.com/Naxesss/MapsetVerifier/releases) by ::{ flag=SE }:: [Naxess](https://osu.ppy.sh/users/8129817) in addition to AiMod if you are looking to get your beatmap [ranked](/wiki/Beatmap/Category#ranked). Other programs are more up-to-date with the current ranking criteria and can detect many more issues than AiMod. However, do not completely ignore AiMod as some rules in the ranking criteria rely on it.
