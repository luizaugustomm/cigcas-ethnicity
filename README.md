# Ethnicity and Gender Imbalance among Authors of Computer Science Research Conferences

This repository contains CSV files of the following dataset: https://data.mendeley.com/datasets/w5y4xy3zsc/1

There are 4 files: authors, conferences, ethnicity and papers.

* Authors table consists of 3 attributes: paper key, position of author (1st, 2nd,...nth author) and the full name appeared in the dblp records (including the padding bits 0001, 0002 etc)

* Conferences table consists of 10 attributes: global_key (name of the conf), conf_key (specific to the year), year, publisher (ACM/springer/ieee etc), title, link (url to the conference website), and cs | de | se | th (domain of the conference- Computer Science, Data Engineering, Software Engineering and Theory)

* Ethnicity table consists of 5 attributes: name (name of the author), l0, l1, and l2 (ethnicity levels ) and gender

* Papers table consists of 7 attributes: global_key (key of the conference), paper_key (dblp key of the paper), conf_key , link (doi link to the digital library). title, pages, and citations
