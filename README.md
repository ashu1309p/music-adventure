# 🎵 Music Adventure

A free, playful website that introduces kids (and grown-ups) to musical instruments:
piano, guitar, drums, ukulele, keyboard/synth, and singing. It runs right in the
browser, with nothing to install.

**▶ Try it live:** https://YOUR-USERNAME.github.io/music-adventure/
*(this link works once the site is published, see PUBLISH.md)*

## What is it

Pick who you are (Little Musicians 4 to 6, Music Explorers 7 to 9, Rising Stars 10 to 12,
or Grown-ups) and whether you have played before. Then choose an instrument and start
playing. Every instrument has real, tappable sound plus songs and mini-games tuned to
your age.

Highlights:

- A playable touch keyboard with follow-the-glowing-key songs
- Strummable guitar and ukulele with chord shapes
- A tappable drum kit with a Beat Builder loop composer
- A synth keyboard with switchable sounds (Piano, Bells, Space, Robot)
- A no-microphone singing corner (Do-Re-Mi warm-ups and copy-the-tune)
- Shared rhythm and ear-training games
- A Grown-ups track with a "which instrument suits you?" guide, beginner fundamentals,
  and buying tips

## How to use it

Open the link on any device (phone, tablet, or laptop). It works best on a tablet.
Tap a key, string, or pad to hear it. The very first tap turns the sound on (browsers
require one tap before playing audio). Once loaded, it works offline too.

## Privacy

No accounts, no sign-ups, no data collection, no ads, and no microphone. Nothing is ever
recorded. Progress stars are saved only in your own browser (localStorage), never sent
anywhere.

## Giving feedback

I would love your thoughts, especially from the kids trying it. You can:

- Open an **Issue** on this repo (the "Issues" tab above), or
- Just message me directly.

Helpful things to tell me: what was fun, what was confusing, whether the sound worked,
whether the reading level felt right for the age, and any instrument you wish it had.

## For the curious (how it is built)

The whole thing is a single self-contained HTML file. All sound is generated live in the
browser with the Web Audio API, so there are no audio files to download and it stays one
tidy file. There is no build step and no backend. `music-adventure.html` and `index.html`
are the same file; `index.html` is the copy GitHub Pages serves at the site's root.

## Status

Kids edition (six instruments) and a Grown-ups track are live. Still planned: a Hindi
version and more instruments. This is a family side project, made for fun and learning.
