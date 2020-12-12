# MCA of Charlie

# Week 1: Musical Datasets

## Dataset Theme 

I have chosen to use the hard rock band Linkin Park as the theme of my dataset due to them being one of my favourite bands meaning I know their music well and feel I will enjoy exploring their music further. 

Linkin Park started out in 1996 in California, following the nu metal path, releasing their debut album ‘Hybrid Theory’ in 2000. The band has 6 members, though Chester \(Lead Vocalist\) passed away in 2017, leaving the band at 5 members currently. The remaining members are:
*	Mike Shinoda – Vocalist/Rhythm Guitar
*	Brad Delson – Lead Guitar 
* Dave Farrell \(aka Phoenix\) – Bassist
*	Joe Hahn – DJ/Mixer
*	Rob Bourdon – Drums 

They are currently on Hiatus following Chester’s passing. Their most recent album ‘One more light’ was released in 2017, three years after their previous album. Linkin park has a mix of original, remix and live albums which total at 11 currently. To date they have sold over 100 million records worldwide, have been nominated for 6 Grammys, numerous other awards and have notably won the ‘Best Hard Rock Performance’ Grammy in 2002 for their performance of ‘Crawling’ from their debut album. 


## Current manifestations of data relating to dataset 


**Descriptive Data**

Descriptive data is very limited on the bands website currently as it requires you to click through to a streaming service/YouTube or to look on their store for any information. The store only shows a few recent albums and only displays the Album name and track lists. The streaming services supply further descriptive data such as the length of each track, release date, running time, style of music and album artwork. It is also possible to select pre-created playlists, search using lyrics and have other bands suggested based on further descriptive data stored in the background. 

Further searching online revealed that further information can be found on other sites that have complied the data. The Linkin Park Association offers a wide range of descriptive data, starting with a description of albums, including notable facts such as awards won. It also shows when the album was released, length of the album, audio formats available \(e.g. CD or Vinyl\), the mixer and producers, the record label and provides a track list. This track list details if the song was released as a single, has a video or tabs available and also offers a link to the lyrics. 

Another site is Allmusic which provides many of the same elements as Linkin Park Association, but also includes musical styles of each album, recording location and is able to suggest similar albums from other artists based on this data. 


**Notated Data**

In terms of notated data, it is possible to find sheet music for most of Linkin Parks songs, with the more popular songs being easiest to locate. The sheet music is possible to find for a range of instruments/vocal arrangements, along with some fan created remixes/tribute pieces. Many of the online catalogues of sheet music include Linkin Park with musicnotes.com, 8notes.com and musescore.com being notable sources. Musescore.com is fan created sheet music but is useful as it can be filtered down by artist, song, instrument type, tempo etc. making it easier to find exactly what is required. 


**Acoutsic Data**

It is possible to find acoustic data on YouTube under the bands official channel, along with recordings of live performance, fan made videos of tributes or covers and lyric videos also possible to access. 

Linkin Park’s official website offers links to streaming services that provide their music. These include Apple music, Spotify, Amazon Music and Tidal. Additionally, some content is posted on the band’s social media pages which includes acoustic aspects. 

---

# Notated Music

For this task I chose to transcribe Linkin Park's song Numb. The specific arrangement I have used can be found [here](https://sheetmusic-free.com/numb-sheet-music-linkin-park/). I have added an image below of my transcription, or you can download my MuseScore file [here](https://charlie-a-mca.github.io/MCA-2020/Week02-Numb.mscz)

![Numb transcription in musescore](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%202/Week02-Numb-1.png)

---

# Encoding Basics - Notated Data

## Task 1: Exporting Score

In this task I exported my MuseScore file into a MusicXML and MEI formats. 

They can be downloaded using the following links:
- Download [MusicXML](https://charlie-a-mca.github.io/MCA-2020/Week03-Numb.musicxml)
- Download [MEI](https://charlie-a-mca.github.io/MCA-2020/Week03-Numb-MEI.mei)

## Task 2: Rendering using Verovio

I have edited the code required to display my file in Verovio and made it viewable [here](https://charlie-a-mca.github.io/MCA-2020/verovio.html)

---

# Computational Analysis - Notated Data

## Task 1: Generating a jSymbolic

For this task I have choosen to run a jSymbolic to determine information about the pitch, range, tones and melody of my piece. The following table displays my results which can also be found [here](https://charlie-a-mca.github.io/MCA-2020/Week04-Numb-Jsymbolic.csv)

Feature | Result 
-------- | --------
Number of Pitches | 21
Number of Pitch classes | 7
Range | 41
Strong Tonal Centres | 2
Mean Pitch | 56
Mean Pitch Class | 5.32
Most Common Pitch | 73
Most Common Pitch Class | 1
Interval between most prevalent Pitches | 28
Pitch Variability | 13.75
Most Common Melodic Interval | 3

As can be seen from the above table the analysis mainly focused on the pitch changes in the song as I felt this would be most valuable in determining variations in the song. 

## Task 2: Piano Roll and Pitch Histogram

The above table is difficult to understand so I have also ran a juypter notebook to produce a histogram, piano roll and scatter plot which display pitch in a more readable format. 

### Pitch Histogram

![Pitch Histogram of Numb transcription](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%204/Pitch%20histogram.png)

The above highlights the most commonly played note by showing how often every note in the song has been played. The graph shows the most common pitch as C/#5 equivalent to the MIDI pitch value of 73 as displayed above. 

### Piano Roll

![Piano Roll of Numb Transcription](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%204/Piano%20Roll%20of%20pitches.png)

This Piano Roll shows the song visually through displaying the order of notes played, length they last and the pitch they are throughout the song. Although I have limited musical knowledge this clearly shows the notes or pitches the song is composed of and appears to correlate with the result of the jSymbolic analysis. 

### Scatter Plot

![Scatter Plot of Numb Transcription, showing pitch](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%204/Scatter%20plot%20of%20pitches.png)

The scatter plot shows all of the pitches in the song against the length of time they are played for, this looks similar to the Piano Roll and also correlates with the most common pitch played. 

---

# Standards in Curation

## Task 1: Metadata Scheme

If theoretically I was to have 1000's of music files to store in my GitHub repository I would include the following metadata elememts to describe the dataset: 

* About the file: 
  * Title (optional subtitle): Name given to transcribed piece
  * Composer: Who created the piece - either an individual, group or band
  * Lyricist: Person(s) responsible for writing the lyrics
  * Encoder: Person(s) responsible for encoding the piece into a digital format
  * Source: Where the transcribed piece came from
  * Location: Where the piece was transcribed
  * Date: When the piece was transcribed
  * Copyright: Identifying who has permission to use the file and in what right
  * Genre 
* Encoding:
  * Purpose: Why the file was encoded/transcribed
  * Edits: Note on if any changes have been made to the piece and why 
  * File type
* Original Piece:
  * Title: If different from above 
  * Artist: If different from above
  * Year: When the song was originally released
  * Album
  * Genre
  
## Task 2: Modified MEI

I have modified my MEI file to contain the abov listed metadata, it can be viewed [here](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%205/Week05-Numb-edited-MEI.mei)

---

# Challenges to Music Curation

## Task 1: Metadata Update

I have checked through the metadata I added to my file in the last task and ensured it contained licensing data, genre classification and other values I deemed important. I did not find anything to add this week, though the file can be viewed [here](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%207/Week07-Numb-edited-MEI.mei)

## Task 2: Rendering with Metadata

I have rendered the MEI file to display in veriovio with the metadata also being displayed above the notated music. This can be viewed [here](https://charlie-a-mca.github.io/MCA-2020/myMeta.html) 

---

# Music as Sound

## Task 1: Identifying tracks and metadata 

Here I have choosen three tracks of different genres and identified the most important metadata about them. 

Feild| Exampe 1 | Example 2 | Example 3
----- | ------- | ------- | ------- 
**Title** | Storybook | Beyond the Warriors | Satan's Smile 
**Artist** |  Scott Holmes | Guifrog | Blood God
**Composer** | N/A | N/A | N/A
**Album** | Inspiring & Upbeat Music | Beyond the Warriors | Catharsis
**Copyright Information** | Attribution non-commercial | Attribution 3.0 International | Attribution-Noncommercial-NoDerivatives
**Genre** | Pop | Celtic | Metal
**Source** | Freemusicarchive.org | Freemusicarchive.org | Freemusicarchive.org
**File/Audio Format** | MP3 | MP3 | MP3
**Number of channels** | 2 | 2 | 2
**Sample rate** | 44100 hz | 44100 hz | 44100 hz
**Bit per Second** | 128000 | 320000 | 320000
**Duration** | 02:11 | 01:59 | 02:57

## Task 2: Spectrograms and Waveforms

### Computing and Exporting Spectrograms and Waveforms 

For the three tracks listed in task 1, I have created a spectrogram and waveform for each. 

**Storybook**
![Waveform of storybook](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%208/Storyook-waveform.png)
![Spectrogram of storybook](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%208/Storybook-spectrogram.png)

**Beyond the Warriors**
![Waveform of Beyond the warriors](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%208/Beyond-waveform.png)
![Spectrogram of Beyond the warriors](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%208/Beyond-spectrogram.png)

**Satan's Smile**
![Waveform of Satan's smile](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%208/Satan-waveform.png)
![Spectrogram of Satan's smile](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%208/Satan-spectrogram.png)

### Advantages of a time-frequency analysis over waveform-based analysis

There are a number of advantages to using a time-frequency analysis over a wave-form analysis, with the main reason being that the time-frequency analysis is representative of the overall music piece, showing the pitch or frequency changes throughout the piece. These pitch changes are represented on the spectrogram and have a scale on the left axis to help people identify what pitch or frequency was used at any given point, without additional musical knowledge being needed. The waveform however only shows the volume or amplitude variation over time, only really representing how the loudness of a piece changes. When looking at the Beyond the Warriors (as shown above) it is possible to see the variety of pitches used in the song, presenting a visual representation of how the song might feel to the listener. The waveform only shows the change in volume which doesn’t show much in regards to the rhythm, pitch or feel of the song. The volume appears fairly consistent throughout whereas the spectrogram shows significant variations as different stages of the song are played. 

---

# Extracting Meaning from Audio

## Task 1: Extracting Features

I have used the same three tracks as last week for this task and have produced a Spectrogram, Mel Frequency Cepstral Coefficient and Chromagram for each track using Sonic Visualiser. 

**Storybook**
![Spectrogram of Storybook](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%209/story-spectrogram.png)
![MFCC of Storybook](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%209/story-mel-co.png)
![Chromagram of Storybook](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%209/story-chroma.png)

**Beyond the Warriors**
![Spectrogram of Beyond the Warriors](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%209/beyond-spectrogram.png)
![MFCC of Beyond the Warriors](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%209/beyond-mel-co.png)
![Chromagram of Beyod the Warriors](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%209/beyond-chroma.png)

**Satan's Smile**
![Spectrogram of Satan's smile](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%209/satan-spectrogram.png)
![MFCC of Satan's smile](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%209/satan-mel-co.png)
![Chromagram of Satan's smile](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%209/satan-chroma.png)

## Task 2: Computing and Visualising Histograms of features

I have not created histograms for the spectrogram element based upon Josh's advice. 

### Histograms computed from Chromagrams

**Storybook**
![Chromagram Histogram of Storybook](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%209/Histograms/Chroma/story-chroma-analysis.png)

**Beyond the Warriors**
![Chromagram Histogram of Beyond the Warriors](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%209/Histograms/Chroma/beyond-chroma-analysis.png)

**Satan's Smile**
![Chromagram Historam of Satan's Smile](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%209/Histograms/Chroma/satan-chroma-analysis.png)

### Histograms computed from MFCCs 

**Storybook**
![MFCC Histogram Storybook](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%209/Histograms/Mel-Co/story-mel-co-analysis.png)

**Beyond the Warriors**
![MFCC Histogram Beyond the Warriors](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%209/Histograms/Mel-Co/beyond-mel-co-analysis.png)

**Satan's Smile**
![MFCC Histogram Satan's Smile](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%209/Histograms/Mel-Co/satan-mel-co-analysis.png)

### Comparing the Histograms

The Chroma histograms vary for the three tracks in a number of ways, by listening to the tracks you would expect to see this variation. The Chroma histograms show the variety of notes being played within each song, irrespective of the octave and without counting instruments or rhythm. There is a significant difference when listening to the tracks between them, with Satan smile being a heavy metal track, featuring mainly guitar and drums in comparison Beyond the Warriors is a Celtic folk track using string and woodwind as the main instruments. However, the variations in the Chroma histograms show that similar notes are used between these songs, in similar frequency levels. The storybook track is a more upbeat pop track which has a piano or keyboard as the main instrument. The storybook tracks Chroma histograms also highlight how very different notes are played in this track compared with Satan Smile and Beyond the Warriors. This is hard to identify without musical knowledge when listening to the track, but there is a different overall feel which could be interpreted as showing the difference in notes used. The storybook histograms also have a different overall shape to them, with less of a smooth arch, with most instead focusing more on the left side of the histogram. 

---

# Audio Similarity and Transcription 

## Task 1: Generating a similarity Matrix 

In this task I used three tracks from the metal genre obtained from freemusicarchive.org.  The similarity matrix displays my tracks in slots 7-9, these tracks are Euology by Castles in the Sky (track 7), She Who Struggles by Tyranny is Tyranny (track 8) and Satan's Smile as used previously is track 9. The tracks in 0-3 are classical and 4-6 are of the rock genre. 

![Similarity matrix](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%2010/similaritymatrix.png) 

The similarity matrix shows how the classical tracks are very different to the rock and metal genre, as would be expected. However the rock and metal genre is interesting as some of the tracks classed as metal appear to match more closely with the rock genre, despite some clear difference in sound when listening to the tracks. 

## Task 2: Transcription

This task uses the track Numb by Linkin Park, which is what I transcribed in week 2/Notated Music. I have completed the task by exporting the MuseScore Notation into a Wav. file which I have then imported into Sonic Visualiser, transformed into a piano roll and then exported as a MIDI file. I have then used MuseScore to open and transcribe the MIDI file as sheet music. I have included the two images below for comparison. 

**Original Transcription** 
![Original Transcription of Numb](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%2010/Week02-Numb-1.png)

**MIDI File Transcription**
![MIDI file transcription of Numb](https://github.com/Charlie-A-MCA/MCA-2020/blob/master/Lab%20Tasks/Week%2010/numb-transribed-1.png)

In terms of sound, the transcribed version sounds similar to the original, however when looking at the notated sheet music there are some clear differences. The main difference is that the transcribed version has more bars to cover the same length of music. This is likely because a ¾ time signature is used instead of the 4/4 used in the original. There is also a different pitch used which is interesting given they still sound similar, though as different notes in the pieces this would help to explain this. Overall, the transcription is not the most accurate as it is much harder for a human to read and use than the original. In addition the transcribed piece lacks the additional information such as the title and artist, but does use the same tempo. 

---
