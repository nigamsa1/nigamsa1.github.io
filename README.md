### nigamsa1.github.io

## Project 1: A Multi-Component Music Synthesizer
# Waves of time

## Group Members
Sanya Nigam

## Format of Your Score Files
The score files are formatted in xml and I created the actual score files itself with the help of ChatGPT to create some of the tune.

## Score File Used
- Link to Score file: https://drive.google.com/file/d/1m_sMMTxpl6MgghZYtGipn9aaH7dtPH89/view?usp=sharing

- Link to short audio score file: https://drive.google.com/file/d/1DKStPVH5t9FtDkFv12PrRyioapFhoyh1/view?usp=sharing

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

# WaveTable Synthesis
#### By: Sanya Nigam

## Function:
Wavetable synthesis creates sound by looping through a stored waveform. This waveform has two main parts: the attack, which shapes the start of the sound, and the sustain, which smoothly repeats between set points. The pitch is controlled by how fast we move through the waveform, and glissando is added by gradually changing this speed to slide between notes. Table cross-fading blends two waveforms over time for a smooth transition in timbre. An ADSR envelope controls the volume in four stages—attack, decay, sustain, and release—to make the sound more expressive. Dynamic filtering, like a low-pass filter, adjusts which frequencies are heard and changes the tone. As we generate sound, we read samples, apply the ADSR envelope, filter if needed, and crossfade between waveforms, creating flexible and rich sounds.

## Grading elements implemented:
- Wave playback on demand from the sequencer
- Envelope generation
- Pitch
- Attack and sustain waves OR loop points
- Table cross-fading OR glissando

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Effects
#### By: Sanya Nigam

## Function:
I implemented noise gate, a compression, and a ring modulator with sinusoid. 

The compressor reduces the dynamic range of an audio signal by making loud sounds quieter and soft sounds louder.

The noise gate removes background sounds by muting signals below a certain threshold

The ring modulator combines two audio signals to create a new signal with a frequency that is the sum and difference of the two input signals

## Grading elements implemented:
- Component passes audio
-  1 Effect
-  3  Effects
