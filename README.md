# saveobama
Some ARG made by sernutilt, owner of the [Obama Discord server](https://discord.gg/obama).

## Day 0 - Livestream
Obama deletes the picture of Obama [live on Twitch.tv](https://www.twitch.tv/videos/853336110) (maxing out at roughly 3k to 4k viewers), and sends a few messages about saving Obama. The stream ends and a link to https://saveobama.com is shared in the channel shortly after.

Initial page content is a simple white text on black background, reading "save obama" in the center of the screen. [[archive.org](https://web.archive.org/web/20201229014534/https://saveobama.com/)] The page includes an HTML comment with a link the redirects to Never Gonna Give You Up by Rick Astley on YouTube. The page also includes a script tag, which seems to be obfuscated on [obfuscator.io](https://obfuscator.io) and then minified. The script includes a fairly simple "obfuscation" function `b` that returns one of the elements from an array of strings, `a`. After that, it writes a function to `window.onload`.

### Debugger

I messed around in the Chrome DevTools Debugger and triggered a page reaction. It loads and plays an audio track at https://saveobama.com/res/12.oga and uses `setInterval` to shake the text in the center of the screen.

### Clues
No clues at this time.

![](https://ramranchreally.rocks/i/o2642t2b.png)

## Day 1 - ???
