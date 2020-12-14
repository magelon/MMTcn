I've made a little fix for MikuMikuTelop and also translated it to English
The source code of MikuMikuTelop came bundled with the program so that means it's open-source 
and it's ok to modify and re-distribute it.

IMPORTANT CONSIDERATIONS.

The MMT script must be encoded in Shift-JIS, use whatever plain text editor that supports
that encoding (MadEdit recommended) to create the file, or modify a sample script(Recommended)

The program had a bug, that probably many of you have experienced,
when formatting the decimal values for the effect file, that's because the program uses the locale-specific
decimal separator, I have changed that so now there will be no problems.

Other Changes
- There is an auxiliary "Refresh" button to manually refresh the script when you change it,
just in case it's not done automatically

- No drag and drop, this is my first time programming in C#, also this is just a quick patch. 
Maybe I will improve it in the future.