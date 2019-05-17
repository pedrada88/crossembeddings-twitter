## Cross-lingual word embeddings from Twitter

The following repository includes the pre-trained cross-lingual word embeddings from the paper *[Learning Cross-lingual Embeddings from Twitter via Distant Supervision](XXX)*.


### Twitter pre-trained word embeddings

We release the 100-dimension monolingual and cross-lingual word embeddings trained on Twitter used in our experiments (English, Spanish, Italian, German and Farsi):

- **Monolingual FastText embeddings**: Available [here](https://drive.google.com/drive/folders/1a9llDhoM6zD-sOKiM0AdSxDYq2-15PJD?usp=sharing)
- **Cross-lingual embeddings post-processed with *plain* averaging**: Available [here](https://drive.google.com/drive/folders/1nuZLzGhStjflmi6hFK6a3qTSPFQfsC-K?usp=sharing)
- **Cross-lingual embeddings post-processed with *weighted* averaging**: Available [here](https://drive.google.com/drive/folders/1JGNS2s8UwBM1itpMPDRi9wYqDgPBXcKf?usp=sharing)

*Note 1:* All vocabulary words are lowercased.

*Note 2:* If you would like to convert the vector txt files to *bin*, you can use [convertvec](https://github.com/marekrei/convertvec).

### Reference paper

If you use any of these resources, please cite the following [paper](XXX):
```bash
@InProceedings{twitteremb19,
  author = 	"Camacho-Collados, Jose and Doval, Yerai and Mart\'{i}nez-C\'{a}mara, Eugenio and Espinosa-Anke, Luis and Barbieri, Francesco and Schockaert, Steven",
  title = 	"Learning Cross-lingual Embeddings from Twitter via Distant Supervision",
  booktitle = 	"arXiV",
  year = 	"2019"
}

```

If you use [Fasttext](https://www.mitpressjournals.org/doi/pdfplus/10.1162/tacl_a_00051) or [VecMap](https://aclweb.org/anthology/P18-1073), please also cite their corresponding papers.
