# NI-Kontakt-Scripts
This is a repository for custom Native Instruments Kontakt Scripts.

Adding Midi Channels to CC_Multiplier.ksp
- Increment the total number for the targetBytes array.
  - ex: %targetBytes[18]
        %targetBytes[19]
        %targetBytes[20]  ...  
        etc.
- Then add your channels to the array with the desired index. 
  - ex:  %targetBytes[19] := 93 %targetBytes[20] := midiChannelNumberHere  ...   etc.
  - For the non-programmers, array indexes start at 0. So, index 18 will be the 19th item in the array.
  - The channel numbers do not have to be in ascending order, it's just personal preference.
