### nigamsa1.github.io

# Project 1: A Multi-Component Music Synthesizer

## Group Members
Sanya Nigam

## Format of Your Score Files
The score files are formatted in xml and I used ChatGPT to create the actual score file itself.

## Score File Used
Link to Score file: https://drive.google.com/file/d/1m_sMMTxpl6MgghZYtGipn9aaH7dtPH89/view?usp=sharing

# WaveTable Synthesis
#### By: Sanya Nigam

## Function:
Wavetable synthesis creates sound by repeatedly cycling through a stored waveform. This waveform has an attack and sustain phase. The attack shapes the initial sound, while the sustain phase loops smoothly between set loop points. The pitch is controlled by the reading speed through the wavetable, with glissando added by gradually adjusting this speed to slide between notes. Table cross-fading blends two waveforms over time for a smooth timbre change. An ADSR envelope adjusts the volume through four stages—attack, decay, sustain, and release—making the sound more expressive. Dynamic filtering like a low-pass filter adjusts which frequencies are heard, changing the tone. As sound frames are generated, we read samples, apply the ADSR envelope, add filtering, and crossfade if needed, creating flexible, rich, and dynamic sounds.

## Grading elements implemented:
- Wave playback on demand from the sequencer
- Envelope generation
- Pitch
- Attack and sustain waves OR loop points
- Table cross-fading OR glissando
