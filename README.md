# Acoustic Species Identification

Birds can serve as effective indicators of changes in biodiversity due to their mobility and diverse habitat needs. The alterations in the species composition and bird population can reflect the progress or shortcomings of restoration projects. However, conventional bird biodiversity surveys relying on observer-based methods are often difficult and expensive to conduct over extensive areas. Alternatively, using audio recording devices combined with modern analytical techniques that employ machine learning can enable conservationists to study the correlation between restoration interventions and biodiversity in greater depth by sampling larger spatial scales with higher temporal resolution. Ultimately, the optimal objective is to create a pipeline capable of precisely detecting a wide range of species vocalizations within a specified location where audio equipment is installed.

Our team's MVP was to design and implement a solution for analyzing audio data to identify different bird species based on their distinct calls. By utilizing machine learning techniques, we aim to create a powerful model that can accurately recognize and predict the species of birds present in the audio recordings. We successfully accomplished this.

The proposed end product of this project is a robust and efficient multi-species classifier that can seamlessly process audio data and identify the bird species present in the recordings. Our solution will use melspectogram to represent features from the audio data, which will then be used to train the machine learning model.


## Data Set:

The train data contains 264 species from Kenya, Africa, and the test set consists of 191 10-minute soundscapes. Xeno-canto provided 16,900 audio recordings which can be used to train a classifier. This data is part of the [BirdClef](https://www.kaggle.com/competitions/birdclef-2023/data) 2023 Kaggle competition.

## Methodology 

![Flow Diagram](images/flow_diagram.png)


## Future Roadmap

