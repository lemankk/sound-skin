SoundSkin is a light weight (under 1.5k) wrapper for AS3 Sound objects which provides an easy and robust interface for controlling sound playback. SoundSkin can be constructed with a preloaded Sound object, or manage the loading of an external audio file. The SoundSkin code library includes the basic SoundSkin class for simple sound control, and a SoundSkinFx class which adds volume fade transitions.

<strong>Main library features:</strong>

<ul>
<li>Percentage-based scrub and volume controls.</li>
<li>Built in mute controls.</li>
<li>Length estimation for downloading audio.</li>
<li>Robust looping control, including indefinite looping, loop pause, loop rewind, and loop reset.</li>
<li>Persistent control of channel position and pan (even while sound is stopped).</li>
<li>Volume fade in/out/to (SoundSkinFx class).</li>
<li>Toggles for playback and mute.</li>
<li>SoundSkin manages all Flash-native sound related components (Sound, SoundChannel, SoundTransform, etc). You can totally forget the nuances of all of those components!</li>
</ul>

Documentation is included in the download bundle.


<strong>NOTE: when loading sounds externally, make sure to encode your mp3 audio at a bitrate that is compatible with Flash Player 9. Some audio encoding will throw off timescale calculations.</strong>