# StopWatch

Voice controlled stopwatch for iPhone, in grahamfry.com.au colours.

Two voice modes, chosen in Settings:

- Any sound (default in the Home Screen app): say a short sharp word such as "go", or clap. One sound starts, the next stops. Reacts in milliseconds and needs no speech service.
- Command words: say "start", "stop", "lap" or "reset". Uses Safari speech recognition, runs 0.3 to 1 s behind, and iOS often blocks it in Home Screen apps. If it does not start within 5 s the app switches to Any sound.

Buttons work in both modes.

## Install on iPhone

1. Open https://fryzee71.github.io/StopWatch/ in Safari.
2. Tap Share, then Add to Home Screen.
3. Tap the mic button and allow the microphone when asked.

Siri or Dictation must be on (Settings, General, Keyboard, Enable Dictation).

## Notes

- Any sound mode ignores further sound for 1 s after a trigger (adjustable) so the beep and echo do not retrigger it. Sensitivity is adjustable; the bar under the display shows the live level and the trigger point.
- Command words land about 0.3 to 1 s after you speak. The voice delay correction backdates them by a fixed amount.
- Recognition stops when the screen locks. Keep the screen awake setting on.
