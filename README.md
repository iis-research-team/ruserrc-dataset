# Russian Scientific Entity Recognition and Relation Classification (RuSERRC) dataset

Contains abstracts of 1,680 scientific papers on information technology in Russian:
* 1,600 unlabeled
* 80 manually labeled.

The dataset is available as a [release](https://github.com/iis-research-team/ruserrc-dataset/releases/tag/v1.0).

## ⭐️ Cross-domain RuSERRC

See details [here](/cross-domain-ruserrc/).

## Entity recognition
Entity annotation was performed in BIO format. Entities are terms represented by nouns or noun phrases. 

## Relation Classification
The following types were used to annotate semantic relations: 
* `CAUSE`
* `COMPARE`
* `ISA`
* `PART_OF`
* `SYNONYMS`
* `TOOL`
* `USAGE`

## Nested entities

See details [here](/russerc_el/).

## Entity linking

See details [here](/russerc_el/).

## Aspects

See details [here](/ruserrc_aspects/).

## Citation

If you find this repository useful, feel free to cite our paper:
Marshalova A., Bruches E., Batura T. [Automatic Aspect Extraction from Scientific Texts](https://link.springer.com/chapter/10.1007/978-3-031-67008-4_6). Recent Trends in Analysis of Images, Social Networks and Texts. AIST 2023. Communications in Computer and Information Science. Springer, 2024. V. 1905. pp. 67–80.
```
@inproceedings{ruserrc-aspect,
  title={Automatic Aspect Extraction from Scientific Texts},
  author={Marshalova, Anna and Bruches, Elena and Batura, Tatiana},
  booktitle={Recent Trends in Analysis of Images, Social Networks and Texts. AIST 2023. Communications in Computer and Information Science},
  publisher={Springer Nature Switzerland},  
  year={2024},
  pages={67--80}
}
```
Bruches E., Pauls A., Batura T., Isachenko V. [Entity recognition and relation extraction from scientific and technical texts in Russian](https://arxiv.org/pdf/2011.09817.pdf). Proceedings of 2020 Science and Artificial Intelligence conference (S.A.I.ence). IEEE. 2020. p. 41-45.
```
@inproceedings{ruserrc-dataset,
  title={Entity recognition and relation extraction from scientific and technical texts in Russian},
  author={Bruches, Elena and Pauls, Alexey and Batura, Tatiana and Isachenko, Vladimir},
  booktitle={2020 Science and Artificial Intelligence conference (SAI ence)},
  pages={41--45},
  year={2020}
}
```
