# DanceDetect
A max patch generating music from Posenet detected dance.

Requirements:
1. Max 7 or later
2. Modosc max package available here: https://github.com/motiondescriptors/modosc
3. Odot max pacakage available here: https://github.com/CNMAT/CNMAT-odot

To run:
1. Open Dance detect max patch
2. If first time running, double click mo.posenet /body object near Posenet toggle. Then click button under inlet 3 to install posenet. (only needs to be done once) Then go back to main screen.
3. Start Posenet toggle (brings up new window). This window must be up to actively detect poses.
4. Start all-sounds toggle.
5. Load in audio sample by clicking "replace" button and choosing a short audio file (examples provided in audio files).
6. Choose output instrument for sequencer by clicking "noteout" and choosing path. (Default is Microsoft Wavetable Synth, which is just a piano.)
7. For more midi output sounds, download LoopMidi, route Max Midi output to LoopMidi, route loopmidi into a DAW such as Ableton, and choose midi sound in DAW.
8. Download link for loopmidi: https://www.tobias-erichsen.de/software/loopmidi.html
