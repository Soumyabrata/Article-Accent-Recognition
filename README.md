# On the Analysis of French Phonetic Idiosyncrasies for Accent Recognition

With the spirit of reproducible research, this repository contains codes required to produce the results in the manuscript:

> P. Berjon, A. Nag, P. Brodeur, M. Checkley, A. Klinkert, S. Dev, On the Analysis of French Phonetic Idiosyncrasies for Accent Recognition, *under review*.

Please cite the above paper if you intent to use whole/part of the code. This code is only for academic and research purposes.

![picture](https://github.com/pberjon/Article-Accent-Recognition/blob/master/images/english1.png)

*Spectrogram of an English sample.*

 ## Code Organization
 All codes are written in `python3`.
 
 ### Data
The audio samples can be found here : https://www.kaggle.com/rtatman/speech-accent-archive.
GitHub doesn't allow me to give you all the spectrogram files generated, so I decided to give you at max 100 of each accent as an example. If you need all of it, feel free to use the dataset of spectrograms present on my personal Kaggle profile : https://www.kaggle.com/pberjon/accent-data.

### Scripts

Each Python Notebook gives one contribution of the article (and one model I have used): 
 + `accentrecognitionsvm.ipynb` : the SVM
 + `accentrecognitioncnn2.ipynb` : the 2-layer CNN
 + `accentrecognitioncnn4.ipynb` : the 4-layer CNN
 + `datasetcreation.ipynb` : a notebook to create the spectrogram samples with the audio samples
