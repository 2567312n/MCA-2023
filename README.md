# MCA
|[Week 1](Week1.md)||[Week 2](week2.md)||[Week 3](week3.md)||[Week 4](week4.md)||[Week 5](week5.md)||[Week 6](week6.md)||[Week 7](week7.md)||[Week 8](week8.md)||[Week 9](week9.md)||[Week 10](week10.md)|

## Week 1 Goldberg Variations
Challenges found within music related data would include the differneces between audio recordings and the score, therefore metadata may vary due to differing musicians as well as interpretations of the score/]
/[ These challenges are evident in my chosen piece 'Goldberg Variations BWV988 Aria' by J.S Bach. However, due to the compositions dating, I use the Glenn Gould recording which already deviates from the original metadata. Gould performs the piece mathematically to better show Bach's composition style, however this still will ultimatley most likley differ from Bachs original intent. This intent is lost to time; all interpreation of the score is speculative
## Week 2
[Week two Goldberg](week2.md) 
Importing PDF's into musescore on a base level is effective however the quality of the import vastly differs between scores. Any score with a cover page, or refernce text above/below the manuscript is commonely an issue with and sort of result.
Using the Goldberg Variation Aria; a digitally recreation, Musescore effectively recognised the base level details such as Key, Time Signature and Tempo as well as MOST of the notes such as storng beat notes with the correct rhythms. Musecore struggled with many quicker notes, starting at 1/16th notes as well as ornamnets such as a recurring issue with mordents which could change the character of the piece without. The area which required most development was the way the music was structured and how the original presneted the Aria. The original uses a piano stave with multiple crossing voices and MuseScore struggled to recognise a second/third voice in the bass clef frequently. The second voice was more common due to the third being mostly underutlised, confusing the software with uneven note rhythm to the time signature. This fault mainly resides with the original's structuring and the Import done well by keeping the correct time signature regardless. Overall, it was a compotent import with minor changes, at least compared with differing pieces used as a test which where completely unrecognisable or having an incomplete import due to their complexity
## Week 3
[Week 3 Goldberg](week3.md)
{% data/MCA_GoldbergVariations (2).mei verovio_inline.html %}
Within MEI, pitch is represented by 'pname=x' ('x' being the note name) and 'oct=x' ('x 'being that notes numerical octave positioning)
Rhythm/Duration is detailed by 'dur=x' ('x' being the numerical name for the given note (i.e. dur=8 is a quaver/eighth note))
An MEI file displays all data contained within the score.
This information being listed in its entirety removes the user-friendly interface found within software such as MuseScore. This makes it more difficult to operate when composing music. However, MEI allows the user to see and edit every aspect of the file and with basic understanding of the code; allows the user to learn exactly what every notes exact pitch and numerical rhythm duration/ octave placement without having to understand how the music is notated on the staff.
