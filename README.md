# DJ-tuna

Track library for [Mix Kitchen](https://app.rewst.ai/runtime/orgs/ziptest/apps/mix-kitchen), the two-deck DJ app built in Rewst App Builder.

## Tracks

The current library contains eight MP3s in `audio/`. All tracks have a base tempo of **140 BPM**.

| File | BPM |
| --- | --- |
| [1 - zipse - obey.mp3](audio/1%20-%20zipse%20-%20obey.mp3) | 140 |
| [2 - zipse - dubting.mp3](audio/2%20-%20zipse%20-%20dubting.mp3) | 140 |
| [aliyah somebody (zipse rmx).mp3](audio/aliyah%20somebody%20(zipse%20rmx).mp3) | 140 |
| [kid cudi - day n night (zipse rmx).mp3](audio/kid%20cudi%20-%20day%20n%20night%20(zipse%20rmx).mp3) | 140 |
| [zipse - diamonds on my wrist.mp3](audio/zipse%20-%20diamonds%20on%20my%20wrist.mp3) | 140 |
| [zipse - pemdas v3.mp3](audio/zipse%20-%20pemdas%20v3.mp3) | 140 |
| [zipse - vibey deep af.mp3](audio/zipse%20-%20vibey%20deep%20af.mp3) | 140 |
| [zipse- dont cry.mp3](audio/zipse-%20dont%20cry.mp3) | 140 |

The starting decks are **1 - zipse - obey** on Deck A and **2 - zipse - dubting** on Deck B. The original generated Midnight Drive and Neon Terrace demo loops are no longer part of this library.

## Using the tracks

Open Mix Kitchen and use each library row’s **A** or **B** button to load that track into a deck. You can also load a local audio file or use **Load a hosted track** with a direct audio URL.

WaveSurfer is the app’s external JavaScript library. MP3 URLs are audio sources, not external libraries.

## Updating the library

Keep audio files in `audio/`. After uploading or renaming a track, update the app’s saved library, audio URL, duration, and matching waveform data, then republish. Refreshing the app does not automatically discover changes in this repository.

Production uses commit-pinned CDN URLs so audio and waveform data refer to the same file version. Links in the table above follow the latest files on `main`.

`audio/tracks.json` is legacy metadata for the removed generated loops; it is not the current Mix Kitchen catalog.


