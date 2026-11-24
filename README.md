# 3E MIDI Monitor

Real-time **MIDI event monitor** designed for readability and fast diagnosis of MIDI streams. 
Coded in Mozaic by Bram Bos, for use in AUv3 Hosts. 
Uses Mozaic's Log Screen for display.

3E is an independent project dedicated to developing creative tools for electronic music, improvisation, and live performance.  

### Features

- **Event Types**: Filter events by type: Notes, CCs, Poly/Channel Pressure, Pitch Bend, Program Changes, SysEx, and others.
- **Channel Filter**: Filter events by MIDI channel.
- **Clear Screen**: Clear the Log Screen to focus on a specific MIDI context.
- **Show Raw**: Display the raw values of MIDI bytes 1–3.
- **Show Time**: Display the time in milliseconds since the previous event of the same type.
- **MIDI Thru On/Off**: Forward incoming MIDI events to the output.
    

MIDI Monitor can receive MIDI from multiple sources, but cannot distinguish, filter, or display individual input paths.

The readout uses event-specific formatting with aligned columns. Example:

