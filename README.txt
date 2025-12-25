The 'Use custom music cues' option allows you to input a music cue that's not on the HedgeModManager list, to listen to while playing 'Island Rush'. 

This is primarily meant to be used to play songs from modded Jukeboxes that add more than 53 songs, though it also works with any ending song, beta Action Chain music, koco trial music, the Birthday mix (*if Party Details are enabled on the title screen) and some others.


HOW TO GET MUSIC CUE NAMES:

The easiest way to find a song's music cue is to open one of the music archives (for example: '<game folder>/image/x64/raw/sound/custom_sound/bgm_custom.awb') in foobar2000 with the vgmstream plug-in installed.

Example of a music cue: bgm_custom01 (all of them have the 'bgm_' prefix)

Some cues may be silent due to the game not loading certain music archives during Battle Rush, so here's a list of archives that are confirmed to work: bgm, bgm_actionchain, bgm_birthday*, bgm_custom, bgm_cyber, bgm_cyber_w1r06, bgm_kodamaexpert, bgm_miniboss_tutorial and bgm_update.

After finding your music cue of choice, follow the instructions above to add it to 'Music_Custom'.


HOW TO ADD CUSTOM MUSIC CUES:

- Enable the 'Use custom music cues?' option in HedgeModManager

- Open 'config.ini' using a text editor

- Under 'Music_Custom', input new music cues for each Island segment (for example: KronosKoco="bgm_custom01") and save the file.

- Done!