# BOTC Mobile CSS

A CSS-only portrait phone layout for [Blood on the Clocktower Online](https://botc.app).

It only applies on portrait screens up to 767px wide, so the desktop layout is unchanged.

## Install

1. Open `botc.app` on your phone.
2. Open **Settings → Custom CSS**.
3. Paste in the contents of [`botc-mobile.css`](botc-mobile.css).

Raw file: https://raw.githubusercontent.com/mdouglas90/botc-mobile-css/main/botc-mobile.css

## Layout

```
[ storyteller squares ..][ day ][ users ][ gear ]   <- top bar
[            town square (wedges)                ]   <- middle
[ VOICE TEXT NPCS BLUFFS CHARS NIGHT 1 NIGHTS    ]   <- tab bar
[        big MIC button        ][ deafen ]           <- mute bar
```

- Each player is a wedge running to the edge of the town square, with their character art on it.
- Names sit on the outer edge. Reminders sit near the centre.
- A yellow band at the outer edge shows who is talking.
- Tabs, the settings menu and the users list open over the town square.

Written against BOTC Online v3.58.2. It doesn't use `data-v-*` hashes, so it should survive most app updates.
