### nigamsa1.github.io

# Project 1: A Multi-Component Music Synthesizer

## Group Members
Sanya Nigam

## Format of Your Score Files
The score files are formatted in xml and I used ChatGPT to create the actual score file itself.

## Score File Used
Link to Score file: https://drive.google.com/file/d/1m_sMMTxpl6MgghZYtGipn9aaH7dtPH89/view?usp=sharing
<?xml version="1.0" encoding="utf-8"?>
<score bpm="120" beatspermeasure="2">
    <instrument instrument="WaveTable">


        <note measure="1" beat="1" duration="0.75" note="C4"/>
        <note measure="1" beat="1.75" duration="0.75" note="E4"/>
        <note measure="2" beat="1" duration="0.75" note="D4"/>
        <note measure="2" beat="1.75" duration="0.75" note="F4"/>


        <note measure="3" beat="1" duration="0.66" note="E4"/>
        <note measure="3" beat="1.66" duration="0.66" note="G4"/>
        <note measure="4" beat="1" duration="1.0" note="B4"/>
        <note measure="4" beat="1.75" duration="0.75" note="A4"/>

 </instrument>

 <instrument instrument="noisegate">
        <note measure="5" beat="1" duration="0.75" note="G4"/>
        <note measure="5" beat="1.75" duration="0.75" note="D4"/>
        <note measure="6" beat="1" duration="0.75" note="Bb4"/>
        <note measure="6" beat="1.75" duration="0.75" note="F4"/>	
 </instrument>

 <instrument instrument="WaveTable">


        <note measure="7" beat="1" duration="1.0" note="A4"/>
        <note measure="7" beat="1.75" duration="0.75" note="F4"/>
        <note measure="8" beat="1" duration="1.0" note="C5"/>
        <note measure="8" beat="1.75" duration="0.75" note="E5"/>

        <note measure="9" beat="1" duration="1.25" note="D5"/>
        <note measure="9" beat="1.75" duration="0.75" note="Bb4"/>
        <note measure="10" beat="1" duration="1.0" note="G4"/>
        <note measure="10" beat="1.75" duration="0.75" note="D4"/>

        <note measure="11" beat="1" duration="0.75" note="C4"/>
        <note measure="11" beat="1.75" duration="0.75" note="E4"/>
        <note measure="12" beat="1" duration="1.0" note="D4"/>
        <note measure="12" beat="1.75" duration="0.75" note="F4"/>

        <note measure="13" beat="1" duration="1.0" note="E4"/>
        <note measure="13" beat="1.75" duration="0.75" note="G4"/>
        <note measure="14" beat="1" duration="1.25" note="B4"/>
        <note measure="14" beat="1.75" duration="0.75" note="D5"/>
        
        <note measure="15" beat="1" duration="1.5" note="C5"/>
        <note measure="15" beat="1.75" duration="0.75" note="G4"/>
        
        <note measure="16" beat="1" duration="1.25" note="A4"/>
        <note measure="16" beat="1.75" duration="0.75" note="C5"/>
        
        <note measure="17" beat="1" duration="1.25" note="D5"/>
        <note measure="17" beat="1.75" duration="0.75" note="F5"/>
        <note measure="18" beat="1" duration="1.0" note="E5"/>
        <note measure="18" beat="1.75" duration="0.75" note="G5"/>
        
        <note measure="19" beat="1" duration="1.5" note="B5"/>
        <note measure="19" beat="1.75" duration="0.75" note="C6"/>
        
        <note measure="20" beat="1" duration="1.25" note="A5"/>
        <note measure="20" beat="1.75" duration="0.75" note="D5"/>

	<note measure="21" beat="1" duration="1.0" note="A4"/>
        <note measure="21" beat="1.75" duration="0.75" note="F4"/>
        <note measure="22" beat="1" duration="1.0" note="C5"/>
        <note measure="22" beat="1.75" duration="0.75" note="E5"/>

        <note measure="23" beat="1" duration="1.25" note="D5"/>
        <note measure="23" beat="1.75" duration="0.75" note="Bb4"/>
        <note measure="24" beat="1" duration="1.0" note="G4"/>
        <note measure="24" beat="1.75" duration="0.75" note="D4"/>

        <note measure="25" beat="1" duration="0.75" note="C4"/>
        <note measure="25" beat="1.75" duration="0.75" note="E4"/>
        <note measure="26" beat="1" duration="1.0" note="D4"/>
        <note measure="26" beat="1.75" duration="0.75" note="F4"/>

 </instrument>

 <instrument instrument="compressor">
        <note measure="27" beat="1" duration="1.0" note="E4"/>
        <note measure="27" beat="1.75" duration="0.75" note="G4"/>
        <note measure="28" beat="1" duration="1.25" note="B4"/>
        <note measure="28" beat="1.75" duration="0.75" note="D5"/>	
 </instrument>

 <instrument instrument="WaveTable">

        
        <note measure="29" beat="1" duration="1.5" note="C5"/>
        <note measure="29" beat="1.75" duration="0.75" note="G4"/>
        
        <note measure="30" beat="1" duration="1.25" note="A4"/>
        <note measure="30" beat="1.75" duration="0.75" note="C5"/>

    <note measure="31" beat="1" duration="1.0" note="C4"/>
    <note measure="31" beat="1.75" duration="0.75" note="E4"/>
    <note measure="32" beat="1" duration="1.0" note="G4"/>
    <note measure="32" beat="1.75" duration="0.75" note="B4"/>

    <note measure="33" beat="1" duration="1.25" note="D5"/>
    <note measure="33" beat="1.75" duration="0.75" note="F5"/>
    <note measure="34" beat="1" duration="1.0" note="A4"/>
    <note measure="34" beat="1.75" duration="0.75" note="C5"/>

    <note measure="35" beat="1" duration="0.75" note="E5"/>
    <note measure="35" beat="1.75" duration="0.75" note="G5"/>
    <note measure="36" beat="1" duration="1.0" note="F5"/>
    <note measure="36" beat="1.75" duration="0.75" note="D5"/>

    <note measure="37" beat="1" duration="1.0" note="B4"/>
    <note measure="37" beat="1.75" duration="0.75" note="C6"/>
    <note measure="38" beat="1" duration="1.25" note="A5"/>
    <note measure="38" beat="1.75" duration="0.75" note="F4"/>

    <note measure="39" beat="1" duration="1.0" note="E4"/>
    <note measure="39" beat="1.75" duration="0.75" note="G4"/>
    <note measure="40" beat="1" duration="1.25" note="D5"/>
    <note measure="40" beat="1.75" duration="0.75" note="F5"/>

 </instrument>

 <instrument instrument="ringmod">
    <note measure="41" beat="1" duration="1.0" note="C5"/>
    <note measure="41" beat="1.75" duration="0.75" note="B4"/>
    <note measure="42" beat="1" duration="1.25" note="A4"/>
    <note measure="42" beat="1.75" duration="0.75" note="D5"/>
 </instrument>

 <instrument instrument="WaveTable">


    <note measure="43" beat="1" duration="1.0" note="F4"/>
    <note measure="43" beat="1.75" duration="0.75" note="G4"/>
    <note measure="44" beat="1" duration="1.25" note="C4"/>
    <note measure="44" beat="1.75" duration="0.75" note="A4"/>

    <note measure="45" beat="1" duration="1.0" note="D4"/>
    <note measure="45" beat="1.75" duration="0.75" note="E4"/>
    <note measure="46" beat="1" duration="1.25" note="B4"/>
    <note measure="46" beat="1.75" duration="0.75" note="C5"/>

    <note measure="47" beat="1" duration="1.0" note="A5"/>
    <note measure="47" beat="1.75" duration="0.75" note="D5"/>
    <note measure="48" beat="1" duration="1.25" note="F5"/>
    <note measure="48" beat="1.75" duration="0.75" note="G5"/>

    <note measure="49" beat="1" duration="1.0" note="C6"/>
    <note measure="49" beat="1.75" duration="0.75" note="F4"/>
    <note measure="50" beat="1" duration="1.25" note="B5"/>
    <note measure="50" beat="1.75" duration="0.75" note="C5"/>

    <note measure="51" beat="1" duration="1.0" note="G4"/>
    <note measure="51" beat="1.75" duration="0.75" note="D5"/>
    <note measure="52" beat="1" duration="1.25" note="E4"/>
    <note measure="52" beat="1.75" duration="0.75" note="B4"/>

    <note measure="53" beat="1" duration="1.0" note="C5"/>
    <note measure="53" beat="1.75" duration="0.75" note="F5"/>
    <note measure="54" beat="1" duration="1.25" note="D4"/>
    <note measure="54" beat="1.75" duration="0.75" note="C6"/>

    <note measure="55" beat="1" duration="1.0" note="E5"/>
    <note measure="55" beat="1.75" duration="0.75" note="B4"/>
    <note measure="56" beat="1" duration="1.0" note="A4"/>
    <note measure="56" beat="1.75" duration="0.75" note="G4"/>

    <note measure="57" beat="1" duration="1.25" note="F4"/>
    <note measure="57" beat="1.75" duration="0.75" note="D5"/>
    <note measure="58" beat="1" duration="1.0" note="C5"/>
    <note measure="58" beat="1.75" duration="0.75" note="A4"/>

    <note measure="59" beat="1" duration="1.25" note="B4"/>
    <note measure="59" beat="1.75" duration="0.75" note="E5"/>
    <note measure="60" beat="1" duration="1.0" note="D5"/>
    <note measure="60" beat="1.75" duration="0.75" note="F4"/>

    <note measure="61" beat="1" duration="1.25" note="F4"/>
    <note measure="61" beat="1.75" duration="0.75" note="D5"/>
    <note measure="62" beat="1" duration="1.0" note="C5"/>
    <note measure="62" beat="1.75" duration="0.75" note="A4"/>

    <note measure="63" beat="1" duration="1.25" note="B4"/>
    <note measure="63" beat="1.75" duration="0.75" note="E5"/>
    <note measure="64" beat="1" duration="1.0" note="D5"/>
    <note measure="64" beat="1.75" duration="0.75" note="F4"/>

        <note measure="65" beat="1" duration="4.0" note="G4"/>
        
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
