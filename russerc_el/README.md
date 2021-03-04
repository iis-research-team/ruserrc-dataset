# Nested entities and Entity linking

We annotated [RuSERRC](/russerc_el/data/) with 2 more kinds of information:

## 1. Nested entities

There is information about nested entities for the terms at different levels.
We used BIO tagging as well.

Here an example of nested entities:

| token              | tag   | nested_1 | nested_2 |
|--------------------|-------|----------|----------|
| автоматизированное | B-TAG |          |          |
| извлечение         | I-TAG |   B-TAG  |          |
| речевых            | I-TAG |   I-TAG  |   B-TAG  |
| действий           | I-TAG |   I-TAG  |   I-TAG  |

## 2. Entity linking

We linked the terms with the entities from [Wikidata](https://www.wikidata.org/).

In column "wiki_id" you can find an id to the Wikidata entity and ids of the term (including nested ones)
which is linked.

For example, 

| id | token              | tag   | nested_1 | nested_2 | wiki_id       |
|----|--------------------|-------|----------|----------|---------------|
| 0  | автоматизированное | B-TAG |          |          |               |
| 1  | извлечение         | I-TAG |   B-TAG  |          |               |
| 2  | речевых            | I-TAG |   I-TAG  |   B-TAG  | Q25481968:2,3 |
| 3  | действий           | I-TAG |   I-TAG  |   I-TAG  |               |

means that the tokens with ids 2 and 3 ("_речевых действий_") are linked with an entity 
[Q25481968](https://www.wikidata.org/wiki/Q25481968).

Also we extracted information about entities from Wikidata (version from 27.01.2021) such as name, 
description and aliases in Russian (removing claims and sitelinks) and made it publicly available. 
You can download it from
[here](https://drive.google.com/file/d/1KOJY92ektuAnmnXvDA9VJCnh9NeFplHQ/view?usp=sharing).
