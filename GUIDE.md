# Remotion Beginner Guide
Everything you learned in your first session — saved here for reference.

---

## What is Remotion?
Remotion lets you make animated videos by writing instructions (code) instead of clicking buttons in an editor. Think of it like a recipe: you describe what you want, the computer builds it perfectly every time.

---

## What you installed
- **Node.js** — the "engine" your Mac needs to run Remotion (installed from nodejs.org)
- **GitHub Desktop** — the app that downloads your project from GitHub to your Mac
- **Remotion (Hello World project)** — a ready-to-use starter video with a spinning logo, animated title, and subtitle

---

## How to start Remotion Studio (every time)

1. Open **Terminal** (press Command + Spacebar, type Terminal, press Enter)
2. Type this and press Enter:
   ```
   cd /Users/kaiintveld/Documents/GitHub/remotion-installation-
   ```
3. Type this and press Enter:
   ```
   npm run dev
   ```
4. Open **Google Chrome** and go to:
   ```
   localhost:3000
   ```

---

## How to stop Remotion Studio
In Terminal, press **Control + C**

---

## How to get updates I make to your video
1. Open **GitHub Desktop**
2. Click the blue **Pull** button at the top
3. Your browser preview updates automatically

---

## How to export your video as an MP4
In Terminal (while in the project folder), type:
```
npx remotion render
```
The video saves to a folder called `out` inside your project.

---

## Terminal cheat sheet

| What you want | What to type |
|---|---|
| Go to your project | `cd /Users/kaiintveld/Documents/GitHub/remotion-installation-` |
| Install ingredients (first time) | `npm install` |
| Start the preview | `npm run dev` |
| Stop the preview | Press Control + C |
| Export as MP4 | `npx remotion render` |

---

## How we work together
1. You tell me what you want the video to look like (in plain language)
2. I write the code and push it to GitHub
3. You open GitHub Desktop and click **Pull**
4. Your browser preview updates automatically
5. You give feedback and we refine it
6. When happy, you export it as MP4

---

## What Remotion can make
- Animated text videos (words flying in, fading, counting)
- Social media content (TikTok-style)
- Intro/outro animations for YouTube
- Data visualizations (charts, graphs that animate)
- Lyric videos
- Product showcases

---

## Troubleshooting

**"Could not find package.json"**
You are in the wrong folder. Run the `cd` command above first.

**Browser shows nothing at localhost:3000**
Make sure `npm run dev` is running in Terminal (you should see "Server ready").

**Changes I made are not showing**
Open GitHub Desktop and click Pull to download the latest files.
