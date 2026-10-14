# DJ-tuna

Original generated demo loops for the AFTERHOURS two-deck DJ prototype and an App Builder import experiment.

## Audio

The `audio/` folder contains the exact two synthesized loops used in the local prototype, exported as ordinary WAV files. No third-party sample tracks are included.

| Track | BPM | Length | Bars | Direct audio |
| --- | --- | --- | --- | --- |
| Midnight Drive | 120 | 16 seconds | 8 | [Raw WAV](https://raw.githubusercontent.com/zipse-git-erdone/DJ-tuna/main/audio/midnight-drive.wav) |
| Neon Terrace | 120 | 16 seconds | 8 | [Raw WAV](https://raw.githubusercontent.com/zipse-git-erdone/DJ-tuna/main/audio/neon-terrace.wav) |

Both tracks use 4/4 time, with the first downbeat at 0 seconds. Each file is mono, 16-bit PCM at 22,050 Hz, approximately 689 KiB. Machine-readable metadata and SHA-256 hashes are in [`audio/tracks.json`](audio/tracks.json).

## Use in the prototype

Open **Load a hosted track**, paste either Raw WAV URL, and choose **Load into A** or **Load into B**. Set that deck's **Base BPM** to **120** for beat markers and bar loops.

WaveSurfer is a separate JavaScript dependency. In App Builder it belongs in the page's External libraries setting; these WAV URLs are track sources. Published-app access still needs verification against that runtime's network policy.

The `main` URLs follow the latest committed files. Replace `main` with a commit SHA when a fixed version of the audio is needed.
