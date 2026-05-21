**Real-time MIDI event monitor focused on readability and fast diagnosis of MIDI streams.**

Coded in Mozaic by Bram Bos, for use in AUv3 Hosts. 
Uses Mozaic's Log Screen for display.

### Features

- **Event types**: Notes, CCs, Poly/Channel Aftertouch, Pitchbend, Program Changes, Sysex an other.
- Monitoring can be filtered by event type and MIDI channel.
- Event-specific formatted readout in aligned columns. Example: `Note On  |  D#3 (51)  |  vel: 100  |  ch:2`
- In fullscreen mode 30 events are visible at the same time, scrolling is not possible.
- **Clear Screen** to focus on a specific MIDI context
- **Show raw**: Display the raw values of MIDI byte 1-3
- **MIDI Thru**: Incoming MIDI is piped to the output.
