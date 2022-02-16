# RUSERRC v2

This part contains 136 annotated texts in Russian.

Mark up contains entities (terms), semantic relations between them and links to Wikidata entities.

Info about dataset:
- Number of texts: 136
- Number of tokens: 12 809
- Number of terms: 2 028
- Number of links with Wikidata: 938
- Number of relations: 356

Relations by type:
- USAGE: 126
- ISA: 96
- TOOL: 54
- SYNONYMS: 35
- PART_OF: 23
- CAUSE: 19
- COMPARE: 3

We uploaded data in two formats:
1. **ruserrc_v2.zip** contains a directory with files, annotated with terms and links to Wikidata, and a file `relation.csv` with information about relations for the terms in these files. `File_name` column refers to a file name from that dir. `TOOL(158:166)` means that terms which start from 158 and 166 positions are connected with "TOOL" relation.
2. **ruserrc_v2_re_data.zip** contains information about relations like this: `В качестве <e2>среды разработки</e2> выбрана <e1>система компьютерной математики Mathcad</e1>.	ISA`
