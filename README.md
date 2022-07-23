# Exploitation of Lyrics, Music and Vocals in Multimodal Song Classification Systems

Songs play a central role in everyone’s life nowadays, having become accessible from everywhere thanks to technological development 
which allows us to keep entire music libraries inside our pockets. For this reason, songs have also got the attention of numerous researchers 
from disparate areas, statistics and computer science above all, giving birth to new fields, like music information retrieval (MIR) and 
music emotion recognition (MER). This research will focus in particular on the classification of songs according to two target variables, 
emotion and genre, exploiting three different sources of input: vocals, music and lyrics.

## Dataset

The [Music Mood Dataset](https://iris.polito.it/handle/11583/2669975) is a collection of 2000 songs, identified by the artist name and its title, 
and the associated label ‘mood’, retrieved from the analysis of the last.fm tags given by the users and representing the emotion transmitted.

## Technologies

* Analysis: `transformes`, `sklearn`, `scipy`, `networkx`
* Audio Processing: `pydub`, `spleeter`, `opensmile`, `audiofile`, `pyAudioAnalysis`, `pychorus`, `eyed3`
* Language Processing: `nltk`, `easynmt`, `googletrans` 
* Data Retrieval: `selenium`, `lyricsgenius`

## References

* Yang, Y.-H., & Chen, H. H. (2011). Music Emotion Recognition. CRC Press. https://doi.org/10.1201/b10731
* Müller, M. (2015). Fundamentals of Music Processing. Springer International Publishing. https://doi.org/10.1007/978-3-319-21945-5
* Cano, E., & Morisio, M. (2017). Music Mood Dataset Creation Based on Last FM Tags. In Computer Science &amp; Information Technology (CS &amp; IT). Seventh International Conference on Computer Science, Engineering and Information Technology. Academy & Industry Research Collaboration Center (AIRCC). https://doi.org/10.5121/csit.2017.70603
* Reimers, N., & Gurevych, I. (2019). Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks (Version 1). arXiv. https://doi.org/10.48550/ARXIV.1908.10084
* Ekman, P. (1992). An argument for basic emotions. In Cognition and Emotion (Vol. 6, Issues 3–4, pp. 169–200). Informa UK Limited. https://doi.org/10.1080/02699939208411068
* Castanedo, F. (2013). A Review of Data Fusion Techniques. In The Scientific World Journal (Vol. 2013, pp. 1–19). Hindawi Limited. https://doi.org/10.1155/2013/704504
