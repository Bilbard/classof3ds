# classof3ds
<img width="256" height="256" alt="cia" src="https://github.com/user-attachments/assets/e9ab1b92-b4f4-49eb-ab94-c9bf5874e8c9" />

This page will serve as a place for bug reports, suggestions and updates for my Class of '09 ports.

As much as I call these ports, these probably classify better as demakes.

If this repository ever vanishes, look in r/Classof09Game for the new page.

No source is available and it probably never will be, for two reasons:
- I don't want SBN3 claiming the port as "his" and selling it. This isn't something to make profit with.
- I've seen how some people get eaten alive for not programming 100% to the book. I am entirely self-taught, and I never picked up "proper practices", so I'm not going to open the can of worms.

### How this will work
Builds are now uploaded straight to Github. 

If there's any extra steps you must take before updating to a new version, instructions will be provided.

### Where do I download it?
You can either download it from [here](https://db.universal-team.net/3ds/class-of-09) or you can download the newest tag.

# FAQ
### "Any AI?"
**No.** In the alternate universe where I needed AI to make this, it wouldn't have been made at all.

### "Does this work on old 3DS models?"
Yes, by design. Your experience will be enhanced on a new 3DS, but the game is very playable on the old models.

### "I found a bug/I have a feature request/I want to discuss something!"
Open an issue. How you format it is up to you, just make it readable.

### "What engine did you use?"
I made my own. Behind the scenes it works quite differently, but it mimics all of the necessary RenPy functionality needed to run the various games in the series and very little more. In the beginning I was considering using an existing visual novel engine, but none of them were appealing.

### "Can I use the underlying engine for my visual novel/game?"
For reasons cited above, no. I'd advise anyone else to make their own engine, like I did. I promise you, it'll be a hell of a lot easier than trying to adapt my engine. It is a visual novel engine, but it is very tailored to these specific games.

### "What libraries did you use?"
I used devkitARM in conjunction with citro3d/2d. I'm using opusfile for audio decode, and the video decoder is a custom decoder that can only decode MJPEG .avi 120x200@15fps (no audio).

### "Do you plan to port the other games?"
Yes, the second game. I will not port the third game because it's just a weird fetish game. The first two games have a sense of humor.

### "Do you plan to port these games to other consoles?"
Yes. The code was written in a way that should make it pretty easy to pick up shop to another console. I've done some thinking and I've compiled a list of consoles I'd like to do that should be possible:
- Every Xbox, no question.
- Every Playstation (including Vita and PSP), with the possible exception of the PS1. It may not have the texture cache necessary to have a good looking game.
- Every Nintendo home console from the GameCube up. I'd like to have a crack at the N64, but it poses the same problems as the PS1 as well as problems posed by the remaining Nintendo handhelds (good audio playback, audio is half the reason these games are good).
- The Sega Saturn and Dreamcast.

Of course, I am promising nothing. I'd like to do this, but this may prove to be quite the task. I may also be full of shit about a console being "impossible", it's to the best of my knowledge.
