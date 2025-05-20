# uav antenna misalignment demo

this is a quick project exploring how antenna alignment affects signal quality and spectral efficiency

## contents:

- basic plot showing how misalignment hurts spectral efficiency
- another plot showing how SNR levels change the shape
- a GUI that plays distorted audio based on alignment angle (using a knob)
- a little animation of a UAV drifting out of beam alignment

## how to run

open the `.mlx` file in MATLAB (tested on R2021+), and run each section from top to bottom.  
make sure you’ve got the `justin_beiber_song.wav` file or use your own audio clip.

## notes

- the gui simulates what a misaligned signal might sound like (lowpass filter + noise + bit crush)
- the UAV animation is just a simple visualization of how spectral efficiency changes as it moves

---

by cesar sanchez
