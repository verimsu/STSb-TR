# STSb-TR 1.0 (Semantic Textual Similarity benchmark Turkish)


[English STS benchmark dataset](https://ixa2.si.ehu.eus/stswiki/stswiki.html#STS_benchmark) translated into Turkish using [Google Cloud Translation API](https://cloud.google.com/translate/docs/basic/translating-text). No human corrections have been made to the translations.

## Models
All models can be found [here](https://drive.google.com/drive/folders/1mzHnV8H5KqRPdxQfYfoBICvEiBM0aAlW?usp=share_link).

## License
Similar to the original [English STS benchmark dataset](http://ixa2.si.ehu.es/stswiki/images/4/48/Stsbenchmark.tar.gz), STSb-TR **scores** are licensed under [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).

**Note:** Some original text parts have different licenses and attribution rules. See the license file inside the original dataset archive for details.


## Citation

If you use this dataset or models, please cite the following paper:

[Figen Beken Fikri](https://scholar.google.com.tr/citations?user=Rod4MVsAAAAJ&hl=tr), [Kemal Oflazer](https://www.andrew.cmu.edu/user/ko/), [Berrin Yanıkoğlu](http://myweb.sabanciuniv.edu/berrin/). [Semantic Similarity Based Evaluation for Abstractive News Summarization](https://aclanthology.org/2021.gem-1.3.pdf) , In Proceedings of ACL-IJCNLP Workshop GEM: Natural Language Generation, Evaluation, and Metrics, August 6, 2021.

```
@inproceedings{beken-fikri-etal-2021-semantic,
    title = "Semantic Similarity Based Evaluation for Abstractive News Summarization",
    author = "Beken Fikri, Figen  and Oflazer, Kemal and Yanikoglu, Berrin",
    booktitle = "Proceedings of the 1st Workshop on Natural Language Generation, Evaluation, and Metrics (GEM 2021)",
    month = aug,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.gem-1.3",
    doi = "10.18653/v1/2021.gem-1.3",
    pages = "24--33",
    abstract = "ROUGE is a widely used evaluation metric in text summarization. However, it is not suitable for the evaluation of abstractive summarization systems as it relies on lexical overlap between the gold standard and the generated summaries. This limitation becomes more apparent for agglutinative languages with very large vocabularies and high type/token ratios. In this paper, we present semantic similarity models for Turkish and apply them as evaluation metrics for an abstractive summarization task. To achieve this, we translated the English STSb dataset into Turkish and presented the first semantic textual similarity dataset for Turkish as well. We showed that our best similarity models have better alignment with average human judgments compared to ROUGE in both Pearson and Spearman correlations.",
}
```
