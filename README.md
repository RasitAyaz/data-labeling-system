# Data Labeling System

## Vision
Labeled data is a group of samples that have been tagged with one or more labels. A labeling system typically takes a set of unlabeled data and augments each piece of it with informative tags. After obtaining a labeled dataset, machine learning models can be applied to the data so that new unlabeled data can be presented to the model and a likely label can be guessed or predicted for that piece of unlabeled data.

## Scope
The aim of this project is to design and implement a data labeling system in objectoriented manner. The data labeling system has multiple labeling mechanisms. These are; random, machine learning, simple search, user interface, and sentence labeling mechanism. In our program, instances of the dataset will be labeled based on the labeling mechanism provided by the user. There is an authentication mechanism for human users too.

## Use Cases
### Simulation
Actors: User, Data Labeling System

Precondition: User must provide input files (config.json, dataset.json, machine learning data)

1) User starts the system.
2) System selects the dataset which determined by config.json.
3) System parses dataset.json and constructs the dataset.
4) System asks for user name and password.
5) User leaves user name and password blank.
6) System determines the corresponding data labeling mechanism based on the user type.
7) Bots start labeling instances one by one.
8) System outputs the labeled dataset to output.json.
9) System calculates and outputs performance metrics to metrics.json.

### User Interface Labeling
Actors: User, Data Labeling System

Precondition: User must provide input files (config.json, dataset.json)

1) User starts the system.
2) System selects the dataset which determined by config.json.
3) System parses dataset.json and constructs the dataset.
4) System asks for user name and password.
5) If user name and password do not match any credentials in config.json system should prompt the user to enter again.
6) System determines the corresponding data labeling mechanism based on the user type.
7) System outputs the labeled dataset to output.json.
8) System outputs performance metrics to metrics.json.

## Developers
* Eymen Topçuoğlu
* Berkay Deniz
* Muhammed Raşit Ayaz
* Ahmet Emirhan Bakkal
* Yunus Yıldırım
* Vahap Gözenelioğlu
* Ahmet Faruk Yılmaz
* Ubeydullah Günay
