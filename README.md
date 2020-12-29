# saveobama
Some ARG made by sernutilt, owner of the [Obama Discord server](https://discord.gg/obama).

## Day 0 - Livestream
Obama deletes the picture of Obama [live on Twitch.tv](https://www.twitch.tv/videos/853336110) (maxing out at roughly 3k to 4k viewers), and sends a few messages about saving Obama. The stream ends and a link to https://saveobama.com is shared in the channel shortly after.

Initial page content is a simple white text on black background, reading "save obama" in the center of the screen. [[archive.org](https://web.archive.org/web/20201229014534/https://saveobama.com/)] The page includes an HTML comment with a link the redirects to Never Gonna Give You Up by Rick Astley on YouTube. The page also includes a script tag, which seems to be obfuscated on [obfuscator.io](https://obfuscator.io) and then minified. The script includes a fairly simple "obfuscation" function `b` that returns one of the elements from an array of strings, `a`. After that, it writes a function to `window.onload`.

### Debugger

After you wait a randomly generated amount of time, you will start to hear sounds from the page. The sounds are loaded from `https://saveobama.com/res/xxxx.oga`, where `xxxx` is a random number between 0 and 12.

### Clues
No clues at this time.

![](https://ramranchreally.rocks/i/o2642t2b.png)

## Day 1 - Image
[incomplete]

Image link shared in Discord. Likely steganography.

Webserver is unresponsive, likely getting absolutely destroyed by a bunch of people trying to view the image.

```
Pinging saveobama.com [34.222.110.196] with 32 bytes of data:
Request timed out.
Request timed out.
Request timed out.
Request timed out.

Ping statistics for 34.222.110.196:
    Packets: Sent = 4, Received = 0, Lost = 4 (100% loss),
```

---

The ARG ended way earlier than I thought it would. They stopped the web server very quickly, before I could load the image, so I have no idea what this clue was. If you hava any info please open an issue or pull request.
