# Music Curation And Analytics Portfolio

---

## Week 1: Basics of Music Data

### Task 1: Identify a Theme

My dataset focuses on Kanye West's song "Moon" from the 2021 album Donda. It includes three types of data: the musical scores, which are available on 
MuseScore(https://musescore.com/user/35581442/scores/6991389?share=copy_link). Metadata Can be found on Apple Music or other Music platforms. What I've found so far are the song title(Moon), artist(Kanye West), album(Donda), featured artists (Kid Cudi and Don Toliver), genre (Hip-Hop/Rap), track length (2:36), and record label (GOOD Music and Def Jam Recordings), For the audio recordings, the song"Moon" can be found on platforms like Spotify or Youtube(https://github.com/user-attachments/assets/f80dfa26-70a6-4000-b472-cf4e1a726e6e). 

### Task 2: Challenges

The primary challenges in working with music data stem from restricted access, inconsistent curation, and fragmented distribution, all of which make it difficult to fully analyze and engage with music comprehensively. Despite the richness of the data, working with music datasets poses challenges due to restricted access, inconsistent curation, and fragmented distribution, making it difficult to conduct a comprehensive analysis or fully engage with the material.

---

## Week 2: Notation

### Task 1: Identify a piece of music

For this week's assignment, I transcribed a piano arrangement of "Moon" by Kanye West. 

**Screenshots of the Transcript**:

<img src="https://github.com/user-attachments/assets/6203e5e8-c370-49ed-abf8-e0b2fc3cbdfc" alt="Screenshot 1" width="400">
<img src="https://github.com/user-attachments/assets/3968160c-81f6-464b-9dc3-d238579eefe7" alt="Screenshot 2" width="400">
<img src="https://github.com/user-attachments/assets/0249ca31-58af-4763-bb13-13f96a88da4a" alt="Screenshot 3" width="400">

---

## Week 3: Encoding Basics for Notation

### Task 1: Generating MusicXML and MEI files 
The first part is to export the sheet music you created last week as MusicXML and MEI. These are the two files

MusicXML: https://Daniel220204.github.io/MCA-2024/Week3MusicXML

MEI: https://Daniel220204.github.io/MCA-2024/Week3MEI

### Task 2: Rendering the MEI file using Verovio

URL：https://Daniel220204.github.io/MCA-2024/verovio.html.

A comparison of the elements of MusicXML and MEI reveals significant differences in the way they represent music data. Firstly, there is a difference in the representation of musical notes; MusicXML uses the <note> element with its sub-elements <pitch> and <duration> to provide richer semantic information, but MEI shows a more concise structure by using <pname> and <oct> in the <note> element. Secondly, for the representation of time signatures, MusicXML uses the <time> element and its sub-elements <beats> and <beat-type>, while MEI uses the <meterSig> element and its corresponding attributes, and although both convey the same information, the structure of MusicXML is a bit more flexible. Finally, for key signatures, MusicXML expresses them through the <key> element with its sub-elements <fifths> and <mode>, but MEI uses the <keySig> element to express the same. This difference results in MusicXML being better suited for reading, while MEI is better suited for quick parsing. Therefore, when choosing between using MusicXML and MEI, the choice of which to use should be based on the needs of the project.

---

## Week 4: Computational analytics of notated music

### Task 1: Generating a jSymbolic
I chose these features when generating a jSymbolic analysis of my work. Here's the CSV file.[Upload,Range,Mean_Pitch,Most_Common_Pitch_Class,Last_Pitch,Most_Common_Rhythmic_Value
"C:\Users\2774752L\Downloads\Moon__Kanye_West (1).mid",74.0, 66.0, 5.0, 89.0, 0.5
ing Individual Lab Work.csv…]()

**Range: 74.0**

**Mean Pitch: 66.0**

**Most Common Pitch Class: 5.0**

**Last Pitch: 89.0**

**Most Common Rhythmic Value: 0.5**

### Task 2: Generating a piano roll and a pitch histogram

<img width="546" alt="截屏2024-10-27 20 13 44" src="https://github.com/user-attachments/assets/4afcc94f-7840-4f55-9383-b9ac727da719">
<img width="906" alt="截屏2024-10-27 20 14 17" src="https://github.com/user-attachments/assets/01fed76b-2829-4ff5-9df4-d6e0cc953cf9">
<img width="612" alt="截屏2024-10-27 20 14 38" src="https://github.com/user-attachments/assets/3d78cf58-59ca-4d7f-855a-431995466fe0">

---

## Week 5: Standards in curation

### Task 1: Metadata Scheme

These are the metadata I have selected that are relevant to my work:

**Title: The official name of the transcribed piece**

**Artist: The main performing artist(s) of the piece**

**Publisher: The organization or label responsible for distributing the piece.**

**Release Date: The date when the encoded file was officially released to the public.**

**Genre: The primary music style of the music piece**

**Language: Primary language of the lyrics**

**Key: The musical key of the piece**

### Task 2: Modifying the MEI file

**This is the new MEI file with the elements I selected added**

https://Daniel220204.github.io/MCA-2024/Week5UpdatedMEIFile

<img width="1232" alt="Week5Task2" src="https://github.com/user-attachments/assets/a089b46c-9304-4c31-a4c6-f946db8b935e">
<img width="1233" alt="Week5Task2（2）" src="https://github.com/user-attachments/assets/337c2257-afc2-47df-bd4a-7d8b515a7505">

---

## Week 7: Challenges to music curation

### Task 1: Updating last week's metadata

The genre classification "Hip-Hop" was added to the “<projectDesc>” and “<notesStmt>” sections to provide clear context and improve the discoverability of the piece. Licensing data, specifying a Creative Commons Attribution 4.0 license, was included under ”<pubStmt>“ in the ”<availability>“ section to clarify usage rights and ensure proper credit attribution. These additions align with MEI guidelines.

### Task 2: Render the newly created MEI file with Verovio.

URL: https://Daniel220204.github.io/MCA-2024/metaRAW.html

---

## Week 8: Music as sound

### Task 1: Find and describe 3 audio tracks relating to my theme

[Task 1 from Week 8.xlsx](https://github.com/user-attachments/files/17966654/Task.1.from.Week.8.xlsx)

### Task 2: Perform basic analysis of my 3 tracks in SonicVisualizer

**Another Moon waveform and spectrogram**
![AnotherMoonWaveform](https://github.com/user-attachments/assets/9621b877-d777-43c6-87a8-faa6187480ed)
![AnotherMoonSpectrogram](https://github.com/user-attachments/assets/54d9e1d9-ecfb-4c5a-a9f1-683a3b0f8e5a)
**Moonlight Reprise waveform and spectrogram**
![MoonlightRepriseWaveform](https://github.com/user-attachments/assets/347bdb64-7d6a-4295-8139-c877d8a08e48)
![MoonlightRepriseSpectrogram](https://github.com/user-attachments/assets/cebe6f8e-977f-4f0b-ae83-3cad36203aab)
**Moonrise waveform and spectrogram**
![MoonriseWaveform](https://github.com/user-attachments/assets/f67f4a43-3fcc-4ab9-8f66-61f90fe31b54)
![MoonriseSpectrogram](https://github.com/user-attachments/assets/bc3f2c62-e383-4687-940f-197ffa607bc3)

### Task 2.2: Describing the advantages of a time-frequency analysis over a waveform-based analysis

Time-frequency analysis is more helpful than just looking at waveforms because it shows not only the loudness of the music but also which tones or pitches are present at any moment. For example, in the spectrogram of Another Moon, the bright yellow and orange areas show where the loudest and most prominent sounds are, like deep bass or higher-pitched melodies. This gives a clearer picture of how the music changes over time, like when a soft section builds into a louder, more intense part. You can’t see these details in the waveform, which only shows overall loudness without telling you what kind of sounds are playing.

---

## Week 9: Analysing and extracting data from audio

### Task 1: Extract features

For this week's task, I used the same audio track as last week's task. Below is a screenshot from my Sonic Visualiser

**Moonrise**
<img width="1098" alt="Moonrise1" src="https://github.com/user-attachments/assets/5921ac48-1a22-4da7-b1b7-ce21c8224780">
**Another Moon(song)**
<img width="1087" alt="AnotherMoon1" src="https://github.com/user-attachments/assets/77587b03-54df-4c4b-856a-1c052d46793d">
**Moonlight Reprise**
<img width="1093" alt="Moonlight1" src="https://github.com/user-attachments/assets/8f7b0803-86ac-4f8f-9dc2-987000593824">

### Task 2: Computing and visualising histograms of features

**Task 2.1: Computed Spectrograms to Histograms**

**Computed spectrogram to Histograms**

**Moonrise**
![MoonriseSpectrogram](https://github.com/user-attachments/assets/2e4c4af9-b9ff-43e3-b4f1-ae88c734db30)
**Another Moon(song)**
![AnotherMoonSpectrogram](https://github.com/user-attachments/assets/6b3439eb-b493-423b-a96e-b731f52e3887)
**Moonlight Reprise**
![MoonlightSpectrogram](https://github.com/user-attachments/assets/b8e51d5c-6a97-4575-a03f-a004397ba378)

**Computed Chromagrams to Histograms**

**Moonrise**
![MoonriseChromagram](https://github.com/user-attachments/assets/10f730c2-37dd-418f-a971-908ca562bed5)
**Another Moon(song)**
![AnotherMoonChromagram](https://github.com/user-attachments/assets/2ae778bc-474f-4acb-8703-7989f6f50b13)
**Moonlight Reprise**
![MoonlightChromagram](https://github.com/user-attachments/assets/53db800f-1289-4bb9-bcc0-f7ad02f356c8)

**Computed MFCC's to Histograms**

**Moonrise**
![MoonriseMFCC](https://github.com/user-attachments/assets/6db072a1-7a62-4027-bab4-60e125ad297c)
**Another Moon(song)**
![AnotherMoonMFCC](https://github.com/user-attachments/assets/12fb07cf-730f-4fb9-aa7e-bfa080d8f5dd)
**Moonlight Reprise**
![MoonlightMFCC](https://github.com/user-attachments/assets/ebf5e311-acfa-4f9c-8492-753220a90916)

### Task 2.2: Analysis

The MFCC histograms for the three tracks highlight both similarities and differences. "Another Moon" and "Moonlight Reprise" have smoother and more balanced patterns, reflecting their calm and consistent sound.  In contrast, "Moonrise" shows more peaks and variations, which align with its more dynamic and intense sound.  The visual differences in the histograms match the tracks' audio characteristics, with "Moonrise" being more energetic and layered, while the other two tracks feel more relaxed and steady.

---

## Week 10: Audio similarity & transcription

### Task 1: Similarity

For this Individual Lab Work, I have used the same tracks from the previous 2 weeks. 
<img width="688" alt="Screenshot1" src="https://github.com/user-attachments/assets/2acf9b61-4570-43e5-a0e7-d9668551d369">
<img width="531" alt="Screenshot2" src="https://github.com/user-attachments/assets/4c6f970a-aa05-4c32-b1b9-d15570fa2c2e">
<img width="510" alt="Screenshot3" src="https://github.com/user-attachments/assets/5623e96c-b097-47f7-8e87-f36eb22f4634">

### Task 2: Transcription

**Original:**

![MoonKanye（Image）-1](https://github.com/user-attachments/assets/54116817-3bc2-4ca9-a291-ec4730895a66)
![MoonKanye（Image）-2](https://github.com/user-attachments/assets/cc2e055a-0b15-4625-92e6-5903771ecac4)
![MoonKanye（Image）-3](https://github.com/user-attachments/assets/2f499bab-9fcf-475c-aa2d-5988bcb3bd2c)
![MoonKanye（Image）-4](https://github.com/user-attachments/assets/1983e036-aab7-43a5-8cb4-827c7952e34e)
![MoonKanye（Image）-5](https://github.com/user-attachments/assets/550fbdd0-e44b-416d-95bc-cf50ed6a41d6)
![MoonKanye（Image）-6](https://github.com/user-attachments/assets/033c3d88-3d0f-4953-9364-c8b42da091c1)
![MoonKanye（Image）-7](https://github.com/user-attachments/assets/97d8b76a-6d09-4a69-a8ce-da313467dcd7)
![MoonKanye（Image）-8](https://github.com/user-attachments/assets/874cde8e-4374-4850-ae1a-bdb2b7abe2b7)
![MoonKanye（Image）-9](https://github.com/user-attachments/assets/42aa7c3b-d7bd-45e4-8b4d-71218233558e)
![MoonKanye（Image）-10](https://github.com/user-attachments/assets/bb2b0f28-8c1e-40f3-a70b-863cfb299fce)
![MoonKanye（Image）-11](https://github.com/user-attachments/assets/f619084a-383d-47e2-adbb-5374a171eef2)

**Recreated:**

![Week10Task2（Image）-1](https://github.com/user-attachments/assets/969a5a89-32ec-423c-b6c5-d104b9e09a4b)
![Week10Task2（Image）-2](https://github.com/user-attachments/assets/5cce0934-48a0-4a1a-a74a-6bd076cae6ee)
![Week10Task2（Image）-3](https://github.com/user-attachments/assets/398f28b5-810f-473a-92d4-274da6c4d877)
![Week10Task2（Image）-4](https://github.com/user-attachments/assets/362fffc8-e0a9-42a1-9e4f-94a839d54c8e)
![Week10Task2（Image）-5](https://github.com/user-attachments/assets/b9037b27-b205-41a4-b419-45247aa3f901)
![Week10Task2（Image）-6](https://github.com/user-attachments/assets/7da6dda7-598a-4821-8d06-ea21433d9157)
![Week10Task2（Image）-7](https://github.com/user-attachments/assets/60e358d4-b940-4e4e-ac3e-7c88ac60610f)
![Week10Task2（Image）-8](https://github.com/user-attachments/assets/06d9869d-bac2-46c1-bf3f-64fe25cd1ab3)
![Week10Task2（Image）-9](https://github.com/user-attachments/assets/96fc8909-f1cc-430c-bc66-a68b35fb3b76)
![Week10Task2（Image）-10](https://github.com/user-attachments/assets/f215272f-241d-409b-97c2-cb320964f9d4)

### Task 2.2: Analysis

The transcription from the original to the recreated one captures the basic structure, including the rhythmic framework and primary tonal content.  However, significant musical details are lost, such as dynamics, articulations, and pedal markings, which are essential for expression.  Rhythmic complexities and polyphonic voice separation are often oversimplified or inaccurate, leading to misrepresented note groupings.  While the transcription is a useful starting point, it requires substantial manual refinement to accurately reflect the original piece's musical nuance.
