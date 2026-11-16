# Jig Essentials Plugins

A set of commonly needed DAW plugins in the Jig format.

DSP implemented in Rust/WebAssembly. Audio quality is the first priority, followed by UI/UX, followed by performance.

Each plugin will have a test fixture including unit tests and integration tests using JigDAW's shared tools.

Build and test will have CI scripts for GitHub Actions. These will be triggered when a new tagged version is pushed.

Documentation will be developed concurrently with the plugins, prepared as markdown with a GitHub CI Action to build and publish Pages.

First review existing plugins under ~/github/jigdaw

GUI

Any plugin that may cause aliasing artifacts should support optional oversampling (ADAA?).
maybe - tape stop, drum loop chopper

## References

- ~/github/easyeffects-presets

## Core

### 1. JigEQ : Parametric EQ

### 2. JigComp : Multi-band Compressor/Expander

- ~/github/downspout/plugins/trio

### 3. JigGlue : Master Bus Glue Compressor

- ~/github/downspout/plugins/glue

### 4. JigLimit : Limiter/Clipper

- ~/github/downspout/plugins/guardian

### 5. JigTrans : Transient Shaper

- ~/github/downspout/plugins/spliff

### 6. JigGate : Gate/Noise Reducer

- ~/github/downspout/plugins/silken

### 7. JigStereo : Stereo Enhancer

## Effects

### 8. JigDelay : Delay Unit

### 9. JigVerb : Reverb

- ~/github/downspout/plugins/HeavyVerb

### JigIR

- reference : ~/github/downspout/plugins/NAM

### 10. JigSpace : Flanger/Phaser/Chorus

- ~/github/downspout/plugins/chorale

### 11. JigDistort : Saturation/Overdrive/Distortion

- ~/github/downspout/plugins/damiano

### 12. JigVoc : Vocal Enhancer, De-Esser, Autotune

- ~/github/downspout/plugins/silken

### 13. JigBass : Bass Enhancer

- ~/github/downspout/plugins/bassops

### 14. JigHarmony : Harmonizer

?

## Metering

### 15. JigMeter : Peak/LUFS/Phase

### 16. JigSpect : Spectrum Analyser

## Instruments

### 17. JigGM : General MIDI Intruments

sfz?

### 18. JigDrum : Drum Kit

### 19. JigSynth : Subtractive Synth

### 20. JigSampler : Sampler/Chopper

### 21. JigPerc : Physical Modelling Percussion Synth

### 22. JigWind : Physical Modelling Wind Instrument Synth

### 23. JigString : Physical Modelling String Synth

## Generators/Composition Aids

### 24. JigBeatGen : MIDI Rhythm Generator

### 25. JigBassGen : MIDI Bassline Generator

### 26. JigMelGen : MIDI Melody Line Generator

### 27. JigChordGen : MIDI Harmonizer

### 28. JigPMix : Probabilistic Mixer
