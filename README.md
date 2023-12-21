# TheArtifact

"The Artifact" is a prototype project that aims to create a gamepad-based musical instrument within Unreal Engine 5. I attempted to utilize much of the features and libraries that come with the Engine, notably Meta Sounds and Quartz. 

# Instructions

To open the project, you must use Unreal Engine Version 5.3.2. Currently, the project only supports gamepads instead of Keyboard + Mouse, so you must use one as well (such as an XBox controller or DualShock 4). 

You should be able to simply open the project in Unreal and play it directly from there. Be patient as Unreal may take some time to open the project. 

# Controls

You can use the two joysticks to control the pitch of two synths. To play each one, use the corresponding trigger buttons (left trigger and right trigger). The angle the joystick is pointing to controls the pitch, while the distance from the center will control its volume. 

The face buttons can toggle the percussion sounds, as well as the recorder. When each percussion sound is toggled it will play on a quantized pattern. 

(XBox/PlayStation)
- 'A' / X button: toggles the bass drum
- 'B' / Circle button: toggles the snare drum
- 'X' / Square button: toggles the "Hihat" drum
- 'Y' / Triangle button: Starts/ends a recording
    - When a recording is started, the game will record any sounds that the player makes in the game. When recording has ended, the game will save that recording as a .wav in the project directory under 'Saved/BouncedWavFiles/'
    - Its important to make sure you stop recording before exiting or ending the game, otherwise it won't save the recording.

To control the tempo of the percussive rhythm, use the shoulder button. The right shoulder button increases the BPM by 5 while the left shoulder button decreases it by 5. 

You can also change the musical scale and key that the two synths play by usin the D-pad. Pressing left or right changes the scale (ranging from major, minor, pentatonic and blues scales) while pressing up or down changes an "offset", i.e. pressing down will change the key from C major to B. 