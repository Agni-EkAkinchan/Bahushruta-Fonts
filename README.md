This is an attempt to create fonts for Indian languages. Starting with Bahushruta Devanagari.
This first upload - more of a POC. Includes below languages.
Odia
Kannada
Telugu
Bengali
Malayalam

Note that current output is NOT expected to be nearly problem free / very reliable. Some known issues are listed below and there will be more.

- हृस्व इ matra (i matra) is shown on right (instead of left) for languages except Bengali. to distinguish between हृस्व and दीर्घ, shape of dirgh matra is also changed. both are adopted from malayalam for these languages.
- Bengali - e, ai matra alignment has problems.
- Odia - e matra alignment, v and b are cross mapped - hoping that is how it should be. need to confirm.
- Telugu - ref (r-kar) processing.
- Malayalam - both r (r and rr) mapped to r to reduce ref problems, pronunciation mapping may be incorrect for some. chillu letters will show up stand alone (and not be part of akhand letters).

-----------------------------------------------

I am a non programmer and mostly software illiterate.

below are some immediate problems that I am trying to find solution for.

1) How to use these fonts as webfonts so that I can create a demo page showcasing them?

2) Need to create independent files for each language which can fallback on each other. (so that user can exclude all scripts he/she can read). It is not happening right now (despite mentioning same family for them) so this one file with multiple languages is temporary workaround.
