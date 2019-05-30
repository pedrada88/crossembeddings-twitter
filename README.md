## Cross-lingual word embeddings from Twitter

The following repository includes the pre-trained cross-lingual word embeddings from the paper *[Learning Cross-lingual Embeddings from Twitter via Distant Supervision](https://arxiv.org/abs/1905.07358)*.


### Twitter pre-trained word embeddings

We release the 100-dimension monolingual and cross-lingual word embeddings trained on Twitter used in our experiments (English, Spanish, Italian, German and Farsi):

- **Monolingual FastText embeddings**: Available [here](https://drive.google.com/drive/folders/1a9llDhoM6zD-sOKiM0AdSxDYq2-15PJD?usp=sharing)
- **Cross-lingual embeddings post-processed with *plain* averaging**: Available [here](https://drive.google.com/drive/folders/1nuZLzGhStjflmi6hFK6a3qTSPFQfsC-K?usp=sharing)
- **Cross-lingual embeddings post-processed with *weighted* averaging**: Available [here](https://drive.google.com/drive/folders/1JGNS2s8UwBM1itpMPDRi9wYqDgPBXcKf?usp=sharing)

**Update:** Embeddings for Japanese now also available!

*Note 1:* All words are lowercased.

*Note 2:* All emoji have been unified into a single neutral encoding across languages (no skin tone modifiers). All Twitter users have been anonymized with *@user*.

### Reference paper

If you use any of these resources, please cite the following [paper](https://arxiv.org/abs/1905.07358):
```bash
@article{twitteremb19,
  author = 	"Camacho-Collados, Jose and Doval, Yerai and Mart\'{i}nez-C\'{a}mara, Eugenio and Espinosa-Anke, Luis and Barbieri, Francesco and Schockaert, Steven",
  title = 	"Learning Cross-lingual Embeddings from Twitter via Distant Supervision",
  journal = 	"arXiv preprint arXiv:1905.07358",
  year = 	"2019"
}

```

Full code coming soon.

If you use [Fasttext](https://www.mitpressjournals.org/doi/pdfplus/10.1162/tacl_a_00051) or [VecMap](https://aclweb.org/anthology/P18-1073), please also cite their corresponding papers.
