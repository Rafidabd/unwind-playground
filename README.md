# unwind.

[Try it here](https://rafidabd.github.io/unwind-playground/)

A little browser playground for when I don't feel like doing anything useful.

I was working on AAS and NIRAPOD one day, and both were taking their sweet time loading. I started messing around with a tiny universe while I waited. Then I kept adding things, and somehow it turned into this.

There isn't really a goal here. You can break stuff, make something, put it back together, and leave whenever you want.

## What's inside

- **Rage Room** — set things up and smash them with different tools. There's a hydraulic press too.
- **Kinetic Lab** — build marble runs with ramps, magnets, springs, portals and whatever else you feel like throwing in.
- **Chess Desk** — drag pieces, flick them around, line them up like dominoes. No clocks or puzzles.
- **Wall Painting** — roll paint across masked designs, then peel the tape off for those neat edges.
- **Cosmos** — explore planets, mess with gravity, make supernovas, and try putting the universe back together. VOID//LAB is part of this.
- **Clean Slate** — pressure-wash dirt off different surfaces. Strangely satisfying.

Sound is optional. There's a music menu with links to streaming searches, or you can choose an audio file from your own device.


## Running it

Download the files and open `index.html` in a browser. That's all. No installation, backend, or account.

The whole playground lives in one HTML file. It got a little bigger than I originally planned, but I liked being able to share one file that opens offline. The page also has its visuals embedded, so the offline file works on its own.

If you're hosting it on Netlify, upload the folder containing `index.html`.

## A few things I learned the hard way

The first time I tried blowing up the Sun, my browser almost froze. That sent me down a rabbit hole of fragment limits, glow rendering, lower-resolution canvases, and less expensive rewind snapshots. Some effects are stylized rather than physically accurate; I'd rather have something that responds smoothly than a realistic-looking slideshow.

Some browsers won't run the full WebGL view, so Cosmos also has a lighter fallback. If it feels slow, try the Smooth graphics setting.

## What it's built with

HTML, CSS, JavaScript, Canvas, WebGL and Web Audio. No framework or runtime dependencies.

## Why I made it

Mostly because I got bored. I built it for myself first, then thought I might as well share it. If someone opens it after a rough day and gets distracted for a few minutes, that's good enough for me.

I'm Rafid, a student at Notre Dame College, Dhaka. I spend most of my coding time on [my Academic Analytics System](https://aas-admissions-demo-rfd.onrender.com) and [education research](https://rafidabd.github.io/Rafidabd/when-80/). I also play chess and organize chess events. You can find more stuff on [my GitHub](https://github.com/Rafidabd).