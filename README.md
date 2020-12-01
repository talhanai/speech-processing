# Readme

This repo contains simple code example for reading audio files, plotting it, extracting spectral energy features, and plotting word / phone level alignments.

- __1-AudioToSpectrogram.ipynb__ shows how to plot a spectrogram.
- __2-SpectrogramTranscriptAlignment.ipynb__ shows how to plot word- and phone-level alignments.
- _data/_ contains an example audio file, transcript, word-level alignment, and phone-level alignment.
- _figures/_  contains the output of figures generated. 



## Environment Setup

You can setup a virtual environment as follows:

```
virtualenv venv
source venv/bin/activate
pip install librosa
```

