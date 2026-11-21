---
name: clip-polish
description: Final quality pass on a cut clip before posting - cut points, caption timing and placement, sound, and the checks that catch broken words. Use after clip-cutter and before rule-check, or when the user says "polish it", "make it cleaner" or "why does this clip feel cheap".
---

# Clip polish

Run this on every clip from `clip-cutter` before `rule-check`. It fixes the small things that make a clip feel amateur.

## 1. Cut points
- Start on the reaction or the line right before it, never on dead air. The first word should land within about 0.1 s.
- Cut between phrases, never inside one. Cutting a filler out of the middle of a sentence clips the words around it and sounds broken. Fewer cuts that sit between phrases beat many tight ones.
- End on the payoff, and let the last word finish. Speech-to-text ends a word 40 to 80 ms before the sound really stops, so add about 0.1 s after the last word's end time.
- Keep pauses between phrases under about 0.2 s. A natural beat after a comma can stay.

## 2. Captions
- One to three words per caption, split where a person would pause.
- Show each caption about 2 frames before its first word is heard, so the eye is never behind the ear.
- Never put captions over the streamer's face or mouth, least of all in the first second, when viewers decide if the clip is worth watching. With a facecam layout, captions sit on the seam between the cam and the game.
- Make captions readable on any background: one look for the whole clip (for example a dark box with a thin light edge). Never white text on a light area.
- Colour at most a third of the captions, and colour whole captions, not single letters.

## 3. Sound
- Final loudness about -14 LUFS with true peak at or below -1.5 dB, measured on the finished, encoded file (not the wav).
- Sound effects only on things the viewer can see happen. No whoosh on every cut. Vary the files if something repeats.
- Never fade out the last spoken word.

## 4. Checks before posting
1. Look at 10 frames on each side of every cut. They catch one-frame black flashes and captions that land on the wrong shot.
2. Transcribe the finished clip and compare it with the transcript of the source around every cut. A word that reads fine in text can still sound broken; listen to every cut once.
3. Read the first 2.5 s frame by frame: nothing covers the face, the hook is readable.
4. Then run `rule-check`.
