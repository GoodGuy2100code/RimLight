<div align="center">

# Rimlight

**Light that listens.**

A glowing ring around your Windows screen that moves with your music,
plus word-by-word synced lyrics in English, हिंदी, বাংলা and ਪੰਜਾਬੀ.

[**⬇ Download for Windows**](https://github.com/YOUR-USERNAME/rimlight/releases/latest/download/Rimlight.zip) · [Website](https://YOUR-USERNAME.github.io/rimlight/) · Free · No account

![Rimlight fullscreen lyrics](screenshots/lyrics.png)

</div>

---

## What it does

- **A ring of light around your screen.** A thin neon line hugs the edges of your screen and reacts to every kick, snare and hi-hat. It works with **any** music: Spotify, YouTube Music in a browser, or anything else that plays sound.
- **Synced lyrics, word by word.** Every word lights up exactly when it's sung. Lyrics come from free open databases, and many songs have per-word timing.
- **10 lyric styles.** Drift, Fisheye, Icons, Fisheye Icons, Code, Code Icons, Branches, Web, Constellation and Messages. Each has its own grainy color background.
- **Words that paint the screen.** In fullscreen, sing *red* and red pours out from the word. *Stars* twinkle, *rain* falls, *snow* drifts, *thunder* flashes and *fire* sends embers up, all in time with the beat.
- **4 languages and scripts.** English, Hindi, Bangla and Punjabi, including romanized lyrics like *“dil”* or *“raat”*.
- **Colors from the album cover.** Every song re-paints the ring and the lyrics.
- **Private.** Rimlight only listens to what your PC plays. It never uses your microphone.

## Download and install

1. **[Download Rimlight.zip](https://github.com/YOUR-USERNAME/rimlight/releases/latest/download/Rimlight.zip)**.
2. Right-click the zip → **Extract All**, then open **Rimlight.exe**.
3. **Windows will show a warning. That's normal.**
   Rimlight is a free app without a paid Microsoft certificate, so Windows says *“Windows protected your PC”*.
   Click **More info** → **Run anyway**. You only have to do this once.
4. **If Windows asks for .NET, click Yes.** Some PCs need Microsoft's free **.NET Desktop Runtime 8 (x64)**. Install it, then open Rimlight again.

Rimlight then lives in the **system tray**, the small icons at the bottom-right of the taskbar. A short welcome guide shows you around the first time.

**Needs:** Windows 10 (1809 or later) or Windows 11, 64-bit.

## How to use it

| I want to… | Do this |
|---|---|
| Change what's shown | Right-click the tray icon, or press **Ctrl+Alt+V** to step through: Light only → Now Playing → Floating lyrics → Fullscreen lyrics |
| Change the lyrics style | In fullscreen: **drag the lyrics left or right**, or **hold Tab** to see all 10 styles playing and pick one |
| Change size, font, background or look | In fullscreen, move the mouse and use **Size · Font · Screen · Aesthetics** at the top |
| Jump in the song | Click or drag the progress bar (fullscreen, Now Playing window or mini player) |
| Fix lyrics that are early or late | Press **[** or **]** in fullscreen. The fix is remembered for that song |
| See the tour again | Press **?** in fullscreen, or tray menu → **Getting started** |
| Open all settings | Left-click the tray icon, or ⚙ in fullscreen |

### The four modes

- **Light ring only:** just the glow around your screen.
- **Now Playing:** a big player window with the cover, controls, volume and lyrics.
- **Floating lyrics:** lyrics over your desktop. Clicks pass through, so you can keep working.
- **Fullscreen lyrics:** like a lyric video. Press **Esc** to leave.

### Keyboard shortcuts (work from any app)

| Keys | Action |
|---|---|
| Ctrl+Alt+V | Next mode |
| Ctrl+Alt+R | Light ring on / off |
| Ctrl+Alt+F | Fullscreen lyrics |
| Ctrl+Alt+L | Floating lyrics |
| Ctrl+Alt+N | Now Playing window |
| Ctrl+Alt+M | Mini player |
| Ctrl+Alt+S | Next lyrics style |
| Ctrl+Alt+D | Next ring style |
| Ctrl+Alt+Space | Play / pause |
| Ctrl+Alt+1 / 2 / 3 | Party / Chill / Focus look |

## FAQ

**Does it use my microphone?**
No. It only listens to the sound your PC is already playing.

**Which music apps work?**
The light reacts to everything your PC plays. Lyrics, song info and play controls work with any app in the Windows media panel: the Spotify app, and Spotify or YouTube Music in Chrome, Edge, Firefox, Brave or Opera.

**Why does Windows say it's unsafe?**
Apps without a paid code-signing certificate get this warning when they're new. Click **More info → Run anyway**.

**Will it slow down my games?**
The ring fades out when a game or video is fullscreen, drops to 30 fps on battery, and shows its own fps and CPU use in Settings.

**A song has no lyrics or the wrong ones.**
Settings → Lyrics → **Search again**. Some songs simply aren't in the free lyrics databases yet.

**Where are my settings?**
`%AppData%\Rimlight\settings.json`. Delete that file to reset everything.

## Credits

- Lyrics from [LRCLIB](https://lrclib.net) and NetEase Cloud Music.
- Bundled fonts under the [SIL Open Font License](https://openfontlicense.org).
- Built with .NET 8 and WPF.
