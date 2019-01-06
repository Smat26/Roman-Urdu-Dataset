# Roman Urdu Dataset

[![License](https://img.shields.io/github/license/Smat26/Roman-Urdu-Dataset.svg)](https://github.com/Smat26/Roman-Urdu-Dataset/blob/master/LICENSE)
![repo-size](https://img.shields.io/github/repo-size/Smat26/Roman-Urdu-Dataset.svg)



>This is an extensive compilation of Roman Urdu Dataset (Urdu written in Latin/Roman Script), along with other helpful Roman Urdu NLP resources.

## Motivation
One of the biggest hurdle when working with NLP in Urdu is the lack of comprehensive dataset in the domain unlike other languages. The above resources are therefore a culmination of that effort.
The data is organized so to facilitate other researchers and hobbyist, and help promote research.
Application code for the Roman Urdu NLP can be found here

---

## Description
### Dateset
The dataset consist of sentences gathered from reviews of various e-commerce website, comments on public facebook pages, and twitter accounts. Each row would ideally consist of a single sentence and have a corresponding sentiment attach to it, which would be either `Negative`, `Positive` or `Neutral`.
There are more than 20,000 sentences and they have been manually tagged.

### Dictionary
It contains English meaning of Roman Urdu words.

### Conversion
It consist of words between languages in form of:
``` 
<English> : <Urdu> : <Roman-Urdu>
```

### Negative-and-Positive-Words
It contains negative and positive words for sentiment analysis.
```
<English> : <Roman-Urdu> : <POS-tag>
```

### Urdu-Names
This contains list of common Urdu (Pakistani) names.

---

## Credits
The main dataset compilation for Roman-Urdu NLP processing was done as part of research effort by Zareen Sharf.
More info here: https://archive.ics.uci.edu/ml/datasets/Roman+Urdu+Data+Set

The dataset consist of data gathered from reviews of various e-commerce website, comments of public facebook pages, and twitter accounts, 
Other data have been gathered from wikipedia, and various resources online.


## Contributing
To facilitate more people to actively work in the domain it is requested that if you are building on from these resources, do try to contribute, extend or optimize the current datasets.

If you know of a data source that is not listed here, let me know. 
To do so, you can open a Pull Request with the dataset added in to the relevant file, or just open an issue and mention the dataset & link.

## Usage
You are free to use this dataset for your purposes, do credit the original author, and I would appreciate if you can drop me in a message :) 

## Used in
- https://www.kaggle.com/smat26/sentiment-analysis-on-roman-urdu/
- https://www.kaggle.com/smat26/roman-urdu-dataset

## License 
This project is licensed under the GNU General Public License v3.0 - see the LICENSE.md file for details

