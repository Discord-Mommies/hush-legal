# Privacy Policy

_Last updated: 28 October 2026_

This policy explains what **Hush** ("the bot", "we") stores when you use it on Discord, and how to get it deleted.

## What we store

| Data | Why |
|---|---|
| Server ID and the server's bot settings (auto-join, interval, chosen voice channel, built-in and 18+ pack on/off) | So the bot behaves the way the server set it up |
| Voice channel ID, if a server picks one in `/settings channel` | To know which channel to auto-join |
| Audio clips uploaded with `/clips add`, their names, and the Discord user ID of the uploader | To play the clips, and to know who added them if there's a problem |
| Whether each clip is in the random rotation | So random praise only uses the clips the server chose |

### If you opt in to affection levels

Nothing below is stored about you unless you run `/affection start` yourself.

| Data | Why |
|---|---|
| Your Discord user ID and the server ID | To keep your level separate on each server |
| The name you asked her to call you, and your choice of "good boy", "good girl" or neither | So she can say it |
| Whether you turned on 18+ personal lines | So she only says them if you asked |
| Your affection points and level, today's point counters, when you started, and when you last changed your name | To run the levels and the daily limits |
| Audio recordings of her voice saying your chosen name, and lines that include it | So she can say them to you in voice |

Points come from minutes you spend in a voice channel with the bot (while not deafened) and from using `/play` and `/praise`. We don't keep a log of when you were in voice, only the running totals.

## What we don't store

- **No message content.** The bot only uses slash commands and never reads chat messages.
- **No voice recordings.** The bot joins voice deafened. It plays audio but never listens to or records anyone.
- **No personal profiles.** We don't collect emails, IP addresses or activity history. The only name we store is the one you choose with `/affection start`.

## Who can see it

Your server's data is only used by the bot inside your server. We don't sell or share it with anyone. Clips uploaded to one server are never shown to other servers.

If you opt in to affection levels, other members of that server can see your level, rank and the name she calls you (with `/affection profile` and `/affection leaderboard`), and she says that name out loud in voice.

The bot runs on a cloud server we rent. Uploaded clips, settings and affection data are stored there.

To make her voice say your chosen name, the text of your name and of the lines that include it is sent to [ElevenLabs](https://elevenlabs.io/privacy-policy), the text-to-speech service we use. No Discord ID or other information about you is sent with it.

## How long we keep it

- **While the bot is in your server,** we keep your settings and clips so they keep working.
- **When the bot is removed from your server,** all of that server's settings, clips and affection data are deleted automatically.
- **Any server manager can delete everything at any time** with `/settings reset`, including everyone's affection data.
- **You can delete your own affection data at any time** with `/affection stop`. That removes your level, your chosen name and every recording made for you on that server. Turning off 18+ personal lines with `/affection spicy` deletes the 18+ recordings made for you.
- **If you leave a server,** the bot can't see that, so your affection data on that server stays until you run `/affection stop` there, ask us to delete it, or the server removes the bot.

## Children

The bot follows Discord's Terms of Service, which require users to be at least 13 (or older where local law requires). 18+ clips, and 18+ personal lines, only play in voice channels a server has marked as age-restricted. 18+ personal lines also need the person to turn them on themselves and confirm they're 18 or older.

## Changes

If this policy changes, we'll update the date at the top. Big changes will be announced in our support server.

## Contact

Questions or deletion requests: join our [support server](https://discord.gg/xP4wHW5ypP) or email [hushbot.support@gmail.com](mailto:hushbot.support@gmail.com).
