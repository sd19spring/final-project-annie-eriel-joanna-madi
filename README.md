# GERSHWIN

GERSHWIN is a music generator software that takes lyrical and genre input and outputs a melody in audio and visual form (sheet music). GERSHWIN works by taking the lyrical input, counting the number of syllables, and connecting each syllable to a note (generally notes from a major or minor scale). The output of notes will adhere to standard music convention (so it won't sound like random notes strung together) and a specific genre of music (jazz, pop, etc.). Artists and music enthusiasts can use this program to get inspiration for song creation.

## Authors

All unattributed code has been written by Annie, Madi, Eriel, and Joanna.

## Built Using

[The CMU Pronunciation Dictionary](http://www.speech.cs.cmu.edu/cgi-bin/cmudict) - Used to count lyric syllables

[music21](https://web.mit.edu/music21/) - Used to generate notes

[MuseScore](https://musescore.org/en) - Used to produce sheet music

[TiMidity++](http://timidity.sourceforge.net/) - Used to play MIDI track

[NLTK](https://www.nltk.org/) - Used for sentiment analysis of lyrics


## Getting Started

Download relevant python packages:
```
pip install -r requirements.txt
```

Download MuseScore python library:
```
sudo snap install musescore
```
or
```
install AppImage on the MuseScore website
```

Download MIDI Player Timidity:
```
sudo apt-get install timidity
```

To use MuseScore with music21, connect musicxmlPath key to application path

## To Run

In order to run GERSHWIN, make sure all applicable software has been downloaded, then run the follwing file:
```
 framework.py
```
