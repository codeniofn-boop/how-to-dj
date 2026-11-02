# DJ Academy

A single-file, interactive learning app for beginner DJs. It teaches the four
skills every first mix needs, on a built-in two-deck controller, and scores you
with drills, XP and badges.

Open `index.html` in any modern browser. Nothing to install. The page loads
React, Tailwind CSS, Lucide icons and Babel from public CDNs, so it needs an
internet connection the first time.

## What is inside

**Curriculum roadmap.** Four mandatory lessons unlock in order. Each lesson has
concept cards, a "Follow Me" guided tour on the controller, and a three-question
knowledge check.

1. Counting Beats & Phrasing: beats, bars, 32-beat phrases and dropping on the one.
2. The Art of the Beatmatch: reading BPM, the pitch slider, nudging for phase, blending in.
3. The Perfect Bass Swap: three-band EQ, killing the incoming bass, swapping on the one.
4. Harmonic Mixing: the Camelot Wheel, compatible keys, loading a track in key.

**The controller.** Two decks with three-band coloured waveforms, play, cue,
nudge, sync and pitch sliders, a mixer with HIGH, MID and LOW knobs per channel,
channel faders, a crossfader, a tempo and phase meter, a bass-clash meter and a
track-structure strip. During a guided tour the control you need glows neon
blue. Do the move yourself, or press Next Step and the app performs it while the
faders and waveforms animate.

**Practice drills.** Phrase Drop Challenge (hit CUE on beat 1 of each 32-beat
phrase, graded Excellent, Good or Missed) and Ear Training Equalizer (isolate the
dominant bassline with the two LOW knobs inside 15 seconds, three rounds).

**Progress dashboard.** Lessons completed, timing accuracy score, level and XP,
eight badges, and recent drill rounds.

## Controls

- Knobs: drag up or down, arrow keys, `Home` and `End`, `0` to reset, double-click to reset.
- Faders and pitch sliders: drag, or arrow keys (`Shift` for bigger steps).
- Phrase Drop: click CUE or press the space bar.
- Sound: synthesised in the browser with Web Audio and optional. The toggle is in the top bar.

## Notes

- All tracks are synthesised practice loops, not real songs.
- Progress is kept in React state and mirrored to this browser's local storage.
  Reset it from the dashboard.
- Built with React 18 (UMD), Tailwind CSS (Play CDN), Lucide React and Babel
  Standalone for in-browser JSX. Everything else is in `index.html`.
