``` mermaid
graph TB

A1[Battery Power] --> B[Black Box]
A2[Movement] --> B
A3[SMS & Data] --> B
A4[Charging Bettery ] --> B
A5[GPS Location] --> B
A6[Tactile button press] --> B
B --> C1[1]
B --> C2[2]
C1 --> D1[ audio Message with contact info / diability info]
D1 --> E1[MP3 file uploaded into device]
D1 --> E2[Speaker to play audio]
C2 --> D2[GPS location]
D2 --> E3[SMS Data]
E3 --> G1[GPS data]
E3 --> G2[SIM]
D2 --> E[Audio Cue]
F[FUNTION DECOMP] --> C1
F[FUNTION DECOMP] --> C2
```