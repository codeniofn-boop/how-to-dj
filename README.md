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
ten badges, Drop Sync score, and recent drill rounds.

**John Summit Tech-House Masterclass.** A premium module, open from the start
and best taken after Lesson 3. It switches the app into expert mode (deep
charcoal, neon pink and electric purple) and loads two presets: "Tech House
Groove" locked at 126 BPM on Deck A, with a dense rolling bassline, and "Vocal
Anthem (Build-Up)" locked at 128 BPM on Deck B, with a snare roll and a riser
that climbs for 32 beats into the drop. The six-step walkthrough covers the
Summit formula: lock the tempo by hand, bring the build in on the 1 of a
phrase, cut Deck B's bass, hard-swap the bass on the 1 of the drop, then let
the drop breathe. The mixer gains a SWAP BASS macro and the waveform panel a
DROP clock. Finishing the tour unlocks the **Drop Sync Challenge** drill:
Deck A runs non-stop, you match Deck B's pitch by hand, cue it as the phrase
countdown hits zero, and hit SWAP BASS the instant the 32-beat countdown ends.
The drop is scored at that moment ("Perfect Drop Swapped!", "Clashing
Basslines - Too Early!", "Missed the Phrase Change!").

## Controls

- Knobs: drag up or down, arrow keys, `Home` and `End`, `0` to reset, double-click to reset.
- Faders and pitch sliders: drag, or arrow keys (`Shift` for bigger steps).
- Phrase Drop: click CUE or press the space bar.
- Drop Sync: `B` cues Deck B, the space bar hits SWAP BASS.
- Sound: synthesised in the browser with Web Audio and optional. The toggle is in the top bar.

## Notes

- All tracks are synthesised practice loops, not real songs.
- Progress is kept in React state and mirrored to this browser's local storage.
  Reset it from the dashboard.
- Built with React 18 (UMD), Tailwind CSS (Play CDN), Lucide React and Babel
  Standalone for in-browser JSX. Everything else is in `index.html`.
