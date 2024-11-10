# DATASET SOURCE

Ce repo est en quelques sortes mon `petit nid` d'informations pour stocker des liens ou infos en rapports avec des sources de données d'entrainement pour des modèles de ML. Merci à [Google](www.google.com), [ChatGPT](https://chatgpt.com/) et [Claude](https://claude.ai/) qui m'ont été d'une grande aide dans la recherche d'informations en rapport avec ses domaines spécifiques.

## Sources générales

- Kaggle (<www.kaggle.com/datasets>)
- Google Dataset Search
- UCI Machine Learning Repository
- AWS Open Data Registry
- GitHub (nombreux datasets)
- Hugging Face Datasets

## Images et Computers visions

- ImageNet
- COCO Dataset
- Pascal VOC
- Open Images (Google)
- CIFAR-10/100
- Fashion-MNIST

## Texte et NLP

- Common Crawl
- Wikipedia Dumps
- BookCorpus
- Sentiment140
- IMDB Reviews
- WMT Translation Datasets
- SQuAD (Question Answering)

## Audio

- LibriSpeech
- Common Voice (Mozilla)
- VoxCeleb
- AudioSet (Google)

## Donnés tabulaires

- NYC Taxi Dataset
- Airlines Dataset
- Credit Card Fraud Detection
- Census Data

## Autres sources utiles

- data.gov (données gouvernementales)
- Eurostat
- World Bank Open Data
- WHO datasets
- NASA Open Data

## Données en français

- data.gouv.fr
- INSEE
- SNCF Open Data
- Paris Data

Des bibliothèques utiles pour créer vos propres Datasets:

```python
    # Avec Hugging Face
    from datasets import load_dataset

    dataset = load_dataset("dataset_name")

    # Avec Pytorch
    from torchvision import datasets
    mnist = datasets.MNIST(root="./data", download=True)

    # Avec Tensorflow
    import tensorflow_datasets as tfds
    dataset = tfds.load('mnist')
```
