### nigamsa1.github.io

# Project 1: A Multi-Component Music Synthesizer

## Group Members
Sanya Nigam

## Format of Your Score Files
The score files are formatted in xml and I used ChatGPT to create the actual score file itself.

## Score File Used
<?xml version="1.0" encoding="utf-8"?>
<score bpm="120" beatspermeasure="2">
    <instrument instrument="WaveTable">

        <!-- Intro: Noise Gate and Compression -->
        <effect type="noiseGate" measure="1" beat="1" action="enable"/>
        <effect type="compression" measure="1" beat="1" action="enable"/>

        <note measure="1" beat="1" duration="0.75" note="C4"/>
        <note measure="1" beat="1.75" duration="0.75" note="E4"/>
        <note measure="2" beat="1" duration="0.75" note="D4"/>
        <note measure="2" beat="1.75" duration="0.75" note="F4"/>

        <!-- Theme with Chorus -->
        <effect type="chorus" measure="3" beat="1" action="enable"/>
        <note measure="3" beat="1" duration="0.66" note="E4"/>
        <note measure="3" beat="1.66" duration="0.66" note="G4"/>
        <note measure="4" beat="1" duration="1.0" note="B4"/>
        <note measure="4" beat="1.75" duration="0.75" note="A4"/>

        <!-- Variation with Ring Modulation -->
        <effect type="ringMod" measure="5" beat="1" action="enable" frequency="440"/>
        <effect type="chorus" measure="5" beat="1" action="disable"/>

        <note measure="5" beat="1" duration="0.75" note="G4"/>
        <note measure="5" beat="1.75" duration="0.75" note="D4"/>
        <note measure="6" beat="1" duration="0.75" note="Bb4"/>
        <note measure="6" beat="1.75" duration="0.75" note="F4"/>

        <!-- Flanger for Build-up -->
        <effect type="flanger" measure="7" beat="1" action="enable" depth="0.7" rate="0.25"/>
        <note measure="7" beat="1" duration="1.0" note="A4"/>
        <note measure="7" beat="1.75" duration="0.75" note="F4"/>
        <note measure="8" beat="1" duration="1.0" note="C5"/>
        <note measure="8" beat="1.75" duration="0.75" note="E5"/>

        <!-- Reverb and New Theme Variation -->
        <effect type="reverb" measure="9" beat="1" action="enable" decay="1.2" mix="0.5"/>
        <note measure="9" beat="1" duration="1.25" note="D5"/>
        <note measure="9" beat="1.75" duration="0.75" note="Bb4"/>
        <note measure="10" beat="1" duration="1.0" note="G4"/>
        <note measure="10" beat="1.75" duration="0.75" note="D4"/>

        <!-- Mid-section: Disable Ring Mod, Add Chorus -->
        <effect type="ringMod" measure="11" beat="1" action="disable"/>
        <effect type="chorus" measure="11" beat="1" action="enable"/>
        <note measure="11" beat="1" duration="0.75" note="C4"/>
        <note measure="11" beat="1.75" duration="0.75" note="E4"/>
        <note measure="12" beat="1" duration="1.0" note="D4"/>
        <note measure="12" beat="1.75" duration="0.75" note="F4"/>

        <!-- Extended Theme with Flanger -->
        <effect type="flanger" measure="13" beat="1" action="enable" depth="0.7" rate="0.3"/>
        <note measure="13" beat="1" duration="1.0" note="E4"/>
        <note measure="13" beat="1.75" duration="0.75" note="G4"/>
        <note measure="14" beat="1" duration="1.25" note="B4"/>
        <note measure="14" beat="1.75" duration="0.75" note="D5"/>

        <!-- Outro with Reverb and Cross-fading Effects -->
        <effect type="chorus" measure="15" beat="1" action="disable"/>
        <effect type="compression" measure="15" beat="1" action="disable"/>
        <effect type="noiseGate" measure="15" beat="1" action="disable"/>
        <effect type="flanger" measure="15" beat="1" action="disable"/>
        
        <note measure="15" beat="1" duration="1.5" note="C5"/>
        <note measure="15" beat="1.75" duration="0.75" note="G4"/>
        
        <note measure="16" beat="1" duration="1.25" note="A4"/>
        <note measure="16" beat="1.75" duration="0.75" note="C5"/>
        
        <!-- Repeat and Alternate Patterns for Extension -->
        <note measure="17" beat="1" duration="1.25" note="D5"/>
        <note measure="17" beat="1.75" duration="0.75" note="F5"/>
        <note measure="18" beat="1" duration="1.0" note="E5"/>
        <note measure="18" beat="1.75" duration="0.75" note="G5"/>
        
        <!-- Second Refrain with Flanger and Reverb -->
        <effect type="flanger" measure="19" beat="1" action="enable"/>
        <note measure="19" beat="1" duration="1.5" note="B5"/>
        <note measure="19" beat="1.75" duration="0.75" note="C6"/>
        
        <note measure="20" beat="1" duration="1.25" note="A5"/>
        <note measure="20" beat="1.75" duration="0.75" note="D5"/>

        <!-- Final Reverb Fadeout -->
        <effect type="reverb" measure="21" beat="1" action="disable"/>
        <note measure="21" beat="1" duration="4.0" note="G4"/>
        
    </instrument>
</score>




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
