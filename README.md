# Russian Scientific Entity Recognition and Relation Classification (RuSERRC) dataset

Contains abstracts of 1,680 scientific papers on information technology in Russian:
* 1,600 unlabeled
* 80 manually labeled.

The dataset is available as a [release](https://github.com/iis-research-team/ruserrc-dataset/releases/tag/v1.0).

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