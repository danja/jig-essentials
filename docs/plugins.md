# Jig Essentials Plugins

A set of commonly needed DAW plugins in the Jig format.

DSP implemented in Rust/WebAssembly. Audio quality is the first priority, followed by UI/UX, followed by performance.

Each plugin will have a test fixture including unit tests and integration tests using JigDAW's shared tools.

Build and test will have CI scripts for GitHub Actions. These will be triggered when a new tagged version is pushed.

Documentation will be developed concurrently with the plugins, prepared as markdown with a GitHub CI Action to build and publish Pages.

First review existing plugins under ~/github/jigdaw

Any plugin that may cause aliasing artifacts should support optional oversampling (ADAA?).
maybe - tape stop, drum loop chopper

## References

- ~/github/easyeffects-presets

## Core

### 1. JigEQ : Parametric EQ

### 2. JigComp : Multi-band Compressor/Expander

### 3. JigGlue : Master Bus Glue Compressor

### 4. JigLimit : Limiter/Clipper

### 5. JigTrans : Transient Shaper

### 6. JigGate : Gate/Noise Reducer

### 7. JigStereo : Stereo Enhancer

## Effects

### 8. JigDelay : Delay Unit

### 9. JigVerb : Reverb

### JigIR

- reference : ~/github/downspout/plugins/NAM

### 10. JigSpace : Flanger/Phaser

### 11. JigDistort : Saturation/Overdrive/Distortion

### 12. JigVoc : Vocal Enhancer, De-Esser, Autotune

### 13. JigBass : Bass Enhancer

### 14. JigHarmony : Harmonizer

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
