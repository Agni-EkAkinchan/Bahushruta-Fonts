This is an attempt to create 'bahushruta' fonts for Indian languages. Starting with Bahushruta Devanagari.
This first upload - more of a POC. Includes below scripts.
Odia
Kannada
Gujarati
Gurumukhi
Telugu
Bengali
Malayalam

Note that current output is NOT expected to be nearly problem free / very reliable. Some known issues are listed below and there will be more.

- हृस्व इ matra (i matra) is shown on right (instead of left) for Odia, Kannada, Telugu, Malayalam.
- e and/or ai matra alignment has problems in many scripts.
- Malayalam - both r (r and rr) mapped to r, pronunciation mapping may be incorrect for some. chillu letters behaviour is not understood and will show up as stand alone.

-----------------------------------------------

I am a non programmer and mostly software illiterate.

below are some immediate problems that I am trying to find solution for.

1) How to use these fonts as webfonts so that I can create a demo page showcasing them? - that is, without having own website (i.e. using blogger etc.). If cant solve this, will go for a website once this is at more advanced stage.

2) Need to create independent files for each language which can fallback on each other. (so that user can exclude all scripts he/she can read). It is not happening right now (despite mentioning same family for them) so this one file with multiple languages is temporary workaround.
----------------------------------------------------
to use,
download and install ttf file, in chrome->setting->appearance->customise fonts-> choose bahushruta devanagari for standard and sans serif

if updating, close all instances of browser before installing newer file. (if not done, new file wont show effect till computer is restarted)
