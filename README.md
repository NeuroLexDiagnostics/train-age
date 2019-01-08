# train-age

Repository for training age detection models using the [Common Voice dataset](https://www.kaggle.com/mozillaorg/common-voice). 

## Team members

Active members of the team working on this repo include:

* Jim Schwoebel (Boston, MA) 
* Rajesh Singh (Nashville, TN - Vanderbilt University)

## how to download data

Before downloading, make sure you have roughly 6 GB of hard disk space on your computer. 

You can download the data by going to [this link](https://drive.google.com/open?id=1A30sXuo4e8VINEfh6BQKKhK84QsPjuyC) and clicking download (an arrow on the top right corner of page). 

## how data is organized

There are 3 folders: male, female, and other. The data take the form of .mp3 files. This data format can be directly read by third party libraries like [librosa](https://github.com/librosa/librosa).

## goals / what to beat 

Here are some goals to beat with the data: 

| Age model name | Accuracy | Standard Deviation | Modeltype | 
| ------------- | ------------- | ------------- | ------------- |
| teens.pickle | 0.76209217575633 | +/- 0.0212424639835302 |  knn | 
| twenties.pickle | 0.747827586437699	| +/- 0.00483503800126851	| knn |
| thirties.pickle | 0.765463935070702	| +/- 0.00626231620665817	| knn |
| fourties.pickle | 0.774859823805254	| 0.0186105837039435 |	knn |
| fifties.pickle | 0.794545131389912 | 0.0151656184818545 |	knn |
| sixties.pickle | 0.797694462400345 | 0.0346864094031604	| knn |
| seventies.pickle | 0.795753660637382 | 0.0378425083662649	| hard voting |

## references 
* [Common Voice Dataset](https://www.kaggle.com/mozillaorg/common-voice)
* [Librosa](https://github.com/librosa/librosa)
* [Spacy](https://spacy.io/)
