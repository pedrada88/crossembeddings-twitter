## Cross-lingual word embeddings from Twitter

The following repository includes the pre-trained cross-lingual word embeddings from the paper *[XXX](XXX)*.


### Pre-trained embeddings

We release the 100-dimension word embeddings used in our experiments (English, Spanish, Italian, German and Farsi) as binary *bin* files:

- **Monolingual FastText embeddings**: Available [here](https://drive.google.com/drive/folders/1sQNZN4_2GRkK0Pb1pRJaOpM6Nh8yHJpX?usp=sharing)
- **Baseline cross-lingual embeddings**: Available [here](https://drive.google.com/drive/folders/1Qq5_fC9kqWUA_YwP3SLPpjCB_KMNvxlB?usp=sharing)
- **Cross-lingual embeddings post-processed with Plain and Weighted**: Available [here](https://drive.google.com/drive/folders/1q0SijS7dcPqN0_N3Ct5_GTKDu3N-_5xB?usp=sharing)

*Note 1:* All vocabulary words are lowercased.

*Note 2:* If you would like to convert the binary files to *txt*, you can use [convertvec](https://github.com/marekrei/convertvec).

### Reference paper

If you use any of these resources, please cite the following [paper](https://arxiv.org/abs/1808.08780):
```bash
@InProceedings{doval:meemiemnlp2018,
  author = 	"Doval, Yerai and Camacho-Collados, Jose and Espinosa-Anke, Luis and Schockaert, Steven",
  title = 	"Improving cross-lingual word embeddings by meeting in the middle",
  booktitle = 	"Proceedings of EMNLP",
  year = 	"2018",
  publisher = 	"Association for Computational Linguistics",
  location = 	"Brussels, Belgium"
}

```

If you use [VecMap](https://github.com/artetxem/vecmap) or [MUSE](https://github.com/facebookresearch/MUSE), please also cite their corresponding papers.
