# 🚚 Bull Desert

A tiny, no-fail wash-the-bulldozer game for **3–6 year olds**. "Bull desert" is the way a lot of little kids say *bulldozer* — so that's the name.

The dump truck helps clean a very dirty bulldozer in four simple steps:

1. 🏜️ **Cover** it in dirt and mud
2. 🫧 **Soap** it up with soapy water
3. 💧 **Rinse** all the soap away
4. 🌀 **Dry** it off with a big fan

Then the bulldozer is squeaky clean and sparkly, with a "You did it!" and a **Play again** button.

## Made for little kids

- **You can't lose.** Every tap makes progress; there are no wrong moves and no game-over.
- **One big button.** Tap it a few times to finish each step (4 taps), then it moves on by itself with a cheer.
- **Voice narration** reads each step aloud for kids who can't read yet.
- **Works by touch or keyboard** — tap the button, or press **Space / Enter / any arrow key**.
- **Sound on/off** button (🔊 / 🔇) mutes the beeps and the voice together.
- Big, bright, chunky art that scales to phones, tablets, and computers.

## Play it

It's a single file with no build step and no dependencies. Either:

- Open [`index.html`](index.html) in any modern browser, **or**
- Turn on **GitHub Pages** (Settings → Pages → Deploy from branch → `main` / root) and play it at
  `https://mansipathak.github.io/bull-desert/`.

> Note: browsers only allow sound and speech after the first tap, so the first spoken line plays when the child first presses the button.

## Tech

Plain HTML, CSS, and vanilla JavaScript. The scene is inline SVG; sound uses the Web Audio API and the narration uses the browser's built-in Speech Synthesis — so there's nothing to install.
