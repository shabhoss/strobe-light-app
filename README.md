# Strobe Light App

Phone-screen RGB strobe that listens to surrounding music through the microphone, estimates the BPM, and flashes the whole display in sync with the beat. Made for small raves and parties with no lighting rig — everyone's phone becomes part of the light show.

## Use

Open `index.html`, allow microphone access, tap Strobe Mode. Your screen pulses with the music.

- Tap-tempo fallback if the mic can't lock onto a beat
- Brightness, flash length, and sensitivity controls
- Photosensitivity warning on first launch; hard cap of 3 flashes/second

## Safety

Strobe lights can trigger seizures in people with photosensitive epilepsy. Warn people around you before using it in a crowd.

Single-file build, no dependencies.
