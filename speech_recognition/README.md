# Introduction
This noebook is to train a deep neural network model for end-to-end
automatic speech recognition (ASR).

# Installation guide

## Install avconv

```
sudo apt-get install ffmpeg libav-tools
```
If the avconv command can't be found, create a link by: 
```
sudo ln -s /usr/bin/ffmpeg /usr/bin/avconv
```
# LibriSpeech Dataset

Obtain the appropriate subsets of the LibriSpeech dataset, and convert all flac files to wav format.
Save them in the directory data/nlpnd_projects/.

Linux or Mac:
```
mkdir data
cd data
mkdir nlpnd_projects
cd nlpnd_projects
wget http://www.openslr.org/resources/12/dev-clean.tar.gz
tar -xzvf dev-clean.tar.gz
wget http://www.openslr.org/resources/12/test-clean.tar.gz
tar -xzvf test-clean.tar.gz
mv flac_to_wav.sh LibriSpeech
cd LibriSpeech
./flac_to_wav.sh
```
