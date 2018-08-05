# the-octa

hello octa.

## Stories
### Connect an external audio source and quickly record a sample from it
Connect to an input and in the mixer turn up the DIR (direct monitor) for that input. Change a track to flex maschine, assign a recording buffer to it as a sample, record directly to the buffer and place a trig in the sequence.

### Shuffle the order of the slices on the fly with the scene slider
Slice a sample on a flex maschine, add trigs to the pattern and create linear locks. Assign an LFO to the start position. Create a new scene and lock the LFO's depth to an increased value. 

## Specific tasks
### Assign parameters to a specific scene
Hold Scene [A] or [B] and change a parameter.

### Change a track's effect
Press [FX*] twice.

### Changing a track's machine type
Press [T*] and then double tap [SRC].

### Change the length of a sequence
Press [FUNC] + [PAGE] and press [PAGE].

### Change to a new scene
Press and hold Scene [A] or [B] and press a trigger button.

### Clearing a text field
[FUNC] + Clear.

### Clearing the trigs from a sequence
Press [FUNC] + [CLEAR].

### Connect a device and listen to it
Connect to an input, press [MIX] and turn up DIR (direct monitor). 

### Copy and paste a page of trigs
Press [PAGE] + Copy to copy and [PAGE] + Paste to paste.

### Creating a new project
[PROJ] --> Change --> Create new empty project.

### Delete a slice
In [AED] / Slice press [YES] while on the unwanted slice and select Selete Slice.

### Load a recording to a Flex machine
Double tap the [T*] button and select a recording buffer.

### Mute a track
Press [FUNC] + [T*] to mute a track. Press it again to unmute.

### Play slices manually using the 16 steps
Press [FUNC] + [V] and select Slices. Press [SRC] twice to go to SRC SETUP and turn SLIC on.

### Playing back a recording from a recording buffer
Press [T*] + PLAY to trigger the playback manually.

### Recording directly to a track's recording buffer
Press [REC1] + [T*] to start and [T*] + STOP to stop manually.

### Recording trigs live
Press REC + PLAY. To activate metronome preroll, go to [PROJ] --> Control --> Metronome and activate preroll.

### Reset a locked parameter
Press on the corresponding knob to remove the lock while holding the scene or the trig button.

### Save a recording buffer to file
While on the track that uses the recording buffer press [AED] and go to FILE. Select SAVE AND ASSIGN SAMPLE, give the file a name and select ASSIGN TO SELF.

### Slicing a sample
Press [AED] and go to the SLICE tab by pressing [AMP]. Use the [Level] knob to set a starting point. Press [YES] and again on Add slice here and set the end point with knob [C]. Audition with [FUNC] + [YES]. When a small, empty square shows up that means a zero-level crossing. Slice there, to avoid clicks. No need to save in the end.

### Set the length of a recording
Press [FUNC] + [REC1] and set RLEN (recording length shown in steps).

### Set up a stutter effect
On [FX2] Setup page turn on LOCK (and optionally TAPE to off not to hear the digital imitation of tape delay when changing the delay buffer length). On the [FX2] page itself turn up FB (feedback; 127 for infinite repeats) and increase SEND to at least 1. Switch to Delay control mode by pressing [FUNC] + [V] and selecting it. Trigger keys 9-16 light up if a delay is set up on the corresponding track. 

### Set up Track 8 as Master Track
Go to [PROJ] --> CONTROL --> AUDIO --> Set Track 8 as Master 

### Start a recording on time automatically
Press [FUNC] + [REC2] and set QREC (quantized recording shown in steps) .

### Trim a sample
Press [AED] and trim the sample with the knobs. No need to save in the end.

### Turn on the metronome
Press [CUE] + metronome icon.

By default it can only be heard in the headphone out. To hear it in the master out too go to [PROJ] --> Control --> Metronome and turn up the MAIN VOLUME setting.

## Resources
- [Cuckoo - Octatrack Tutorial #1](https://www.youtube.com/watch?v=NrhPOGzn7LI)
  - Sets up a new project, changes maschines to flex, connects OP-1 as an audio input, directly monitors it and records samples to the recording buffer manually. Slices the samples. Uses trig keys to trigger slices. Sets effects and uses the scene slider. Sets up metronome to be heard on the master out and track 8 as a master track. Sets up stutter effect and plays with delay control.

## Project snapshots
- [2018-08-04 - first bar on octa](https://soundcloud.com/freegyes/20180804-first-bar-on-octa)
