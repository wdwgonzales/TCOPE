# The Twitter Corpus of Philippine Englishes (TCOPE)

![](https://github.com/wdwgonzales/TCOPE/blob/main/banner_tcope_2022.jpg?raw=true)


### Overview
The Twitter Corpus of Philippine Englishes (TCOPE) is a 135-million-word corpus created from roughly 27 million public tweets sampled from 29 major cities in the Philippines.

<br />

#### Features
- Contains the following metadata (as reflected in tags)
	- geographical region
	- twitter user id
	- month of tweet
	- year of tweet
	- unique corpus line id

- Has different formats
	- hierarchical text format (txt): primed for concordance software including AntConc, CasualConc
	- spreadsheet format (csv): primed for analysis using popular data analysis tools such as R and Python

- Is tagged for part-of-speech using [`spaCy`](https://spacy.io/usage/linguistic-features)
- Contains dependency parsing information derived from  [`spaCy`](https://spacy.io/usage/linguistic-features#dependency-parse)

<br />
<br />

### Disclaimer
The current public version of the TCOPE is a "sample" version. As such, please exercise caution in using this version of the corpus. I put forward my intention of contributing to the scholarly community by showing whatever I can at this time. Thank you for your patience.

<br />
<br />

### Overview


#### Collection methodology

Please check out the overview paper on English World-Wide when it comes out! Meanwhile, you can take a look at the pre-print.

<br />
<br />

#### Corpus metadata or tag format
Every line of utterance has been tagged with an identifier tag. The tag format allows for easy identification of a line of utterance within the corpus, and for easy interpretation of relevant metadata. For example, the tag <COPE-TW-CEB-2021-01:73805-1371947328> indicates that the tweet was sampled from the Cebu region in January 2021 and was produced by user 1371947328; it shows that the tweet has a unique identification number of 73805.

<br />
<br />



#### Corpus Version

##### Version 1 (master)
The current version stands at 135 million words (as of November 15, 2022). This version is private. If you are interested in the entire corpus, please contact Prof. Wilkinson Daniel Wong Gonzales at wdwonggonzales@cuhk.edu.hk to discuss options.

<br />

##### Version 1 (public)
The current public version is roughly 13.5 million words. The data was randomly sampled from the version 1 master corpus using the `sample` function in the `pandas` package in the Python environment. Due to current storage constraints, I am not able to release the entire corpus with its full set of features as of the moment. See previous section for details. But I hope that the sampled corpus would still be useful for individuals who have memory or storage limitations or individuals who are only interested in conducting brief, exploratory analyses using TCOPE data. I hope to release corpus incrementally over the next few years.

<br />
<br />

##### Plans for future versions

- increased size
- temporal window expansion (2022 data and beyond)

<br />
<br />


#### Downloading the public corpus

The current public version of corpus (v1) has two formats:

- Hierarchical text format (multiple .txt files arranged by year and region)
 	- Plain text version
	- POS-tagged version
- Spreadsheet CSV format containing columns with POS-tagged text and Dependency-parsed text (single CSV file)

<br />
<br />

They can be downloaded in a compressed ZIP file...

- Via OneDrive: [HERE](https://1drv.ms/u/s!AphIchZOHtHEjfI_HNdn4CqSEsnv5w?e=Cw1buM)
- Via OSF: http://doi.org/10.17605/OSF.IO/3Q5PW

<br />
<br />

###  Manager and owner
- [Asst. Prof. Wilkinson Daniel Wong GONZALES](https://www.wdwgonzales.com "Asst. Prof. Wilkinson Daniel Wong GONZALES") (The Chinese University of Hong Kong, Hong Kong SAR, People's Republic of China)

<br />
<br />

### Overview paper
I have an overview paper that was just accepted for publication in _English World-Wide_, scheduled to be published in 2023. In that paper, I first discuss the considerations that went into TCOPE’s design, the compilation procedure, the format, and access. Then, I demonstrate how it can be used to examine the linguistic features of Philippine English (PhilE) as well as the relationship between these features and other language-internal and language-external factors (e.g., ethno-geographic region, time, age, sex) insightfully. The paper focuses on four documented PhilE features: (1) the use of irregular past tense morpheme -t, (2) double comparatives, (3) subjunctive were in subordinate counterfactual clauses, and (4) the phrasal verb base from. A distributional analysis of these features without considering other factors generally indicated similar patterning as previous work. A deeper analysis of the data using Bayesian multivariate regression revealed structured heterogeneity within PhilE, pointing to the multifaceted and dynamic nature of the variety. Because of its large size, sampling distribution, and its availability in different formats, TCOPE can be used to investigate ‘general’ contemporary PhilE as well as different types of variation within this PhilE. It can broaden horizons in the diachronic and sociolinguistic study of Philippine English(es).

You can find the pre-print [here](https://github.com/wdwgonzales/TCOPE/tree/main/Related%20papers).


<br />
<br />
<br />

##### To Cite
Please cite the overview paper if you use my corpus or mention it in your work.

<br />
<br />

Gonzales, Wilkinson Daniel Wong. 2023. Broadening horizons in the diachronic and sociolinguistic study of Philippine English with the Twitter Corpus of Philippine Englishes (TCOPE). _English World-Wide_, John Benjamins.

<br />
<br />

```
@article{gonzales_broadening_2023,
	title = {Broadening horizons in the diachronic and sociolinguistic study of {Philippine} {English} with the {Twitter} {Corpus} of {Philippine} {Englishes} ({TCOPE})},
	copyright = {CC0 1.0 Universal Public Domain Dedication},
	journal = {English World-Wide},
	author = {Gonzales, Wilkinson Daniel Wong},
	year = {2023},
}

```

<br />
<br />


### Related papers
I would highly appreciate it if you can cite these papers alongside the overview paper, if you decide to use or mention my corpus:


1. Gonzales, Wilkinson Daniel Wong. 2017. Philippine Englishes. _Asian Englishes_ 19(2): 79–95. Routledge. 
https://doi.org/10.1080/13488678.2016.1274574

2. Gonzales, Wilkinson Daniel Wong & Mie Hiramoto. 2020. Two Englishes diverged in the Philippines? A substratist account of Manila Chinese English. _Journal of Pidgin and Creole Languages_ 35(1): 125–159. John Benjamins.
https://doi.org/10.1075/jpcl.00057.gon

3. Gonzales, Wilkinson Daniel Wong. 2022. Hybridization. In Ariane Macalinga Borlongan (Ed.) _Philippine English: Development, Structure, and Sociology of English in the Philippines_. London: Routledge. 

4. Gonzales, Wilkinson Daniel Wong. 2022. Interactions of Sinitic languages in the Philippines:  Sinicization, Filipinization, and Sino-Philippine language creation. In Zhengdao Ye (Ed.), _The Palgrave Handbook of Chinese Language Studies_ (pp. 369–408). London: Palgrave-MacMillan.

They can be downloaded [here](https://github.com/wdwgonzales/TCOPE/tree/main/Related%20papers).

```

@article{gonzales_philippine_2017,
	title = {Philippine {Englishes}},
	volume = {19},
	copyright = {CC0 1.0 Universal Public Domain Dedication},
	issn = {1348-8678},
	doi = {10.1080/13488678.2016.1274574},
	number = {1},
	journal = {Asian Englishes},
	author = {Gonzales, Wilkinson Daniel Wong},
	year = {2017},
	pages = {79--95},
}

@article{gonzales_two_2020,
	title = {Two {Englishes} diverged in the {Philippines}? {A} substratist account of {Manila} {Chinese} {English}: {A} substratist account of {Manila} {Chinese} {English}},
	volume = {35},
	copyright = {CC0 1.0 Universal Public Domain Dedication},
	issn = {0920-9034},
	doi = {10.1075/jpcl.00057.gon},
	journal = {Journal of Pidgin and Creole Languages},
	author = {Gonzales, Wilkinson Daniel Wong and Hiramoto, Mie},
	year = {2020},
	pages = {125--159},
}


@incollection{gonzales_hybridization_2022,
	address = {London},
	title = {Hybridization},
	copyright = {CC0 1.0 Universal Public Domain Dedication},
	booktitle = {Philippine {English}: {Development}, {Structure}, and {Sociology} of {English} in the {Philippines}},
	publisher = {Routledge},
	author = {Gonzales, Wilkinson Daniel Wong},
	editor = {Borlongan, Ariane Macalinga},
	year = {2022},
	pages = {170--183},
}

@incollection{ye_interactions_2022,
	address = {Singapore},
	title = {Interactions of {Sinitic} {Languages} in the {Philippines}: {Sinicization}, {Filipinization}, and {Sino}-{Philippine} {Language} {Creation}},
	copyright = {CC0 1.0 Universal Public Domain Dedication},
	isbn = {9789811609237 9789811609244},
	shorttitle = {Interactions of {Sinitic} {Languages} in the {Philippines}},
	url = {https://link.springer.com/10.1007/978-981-16-0924-4_31},
	language = {en},
	urldate = {2022-08-01},
	booktitle = {The {Palgrave} {Handbook} of {Chinese} {Language} {Studies}},
	publisher = {Springer Nature Singapore},
	author = {Gonzales, Wilkinson Daniel Wong},
	editor = {Ye, Zhengdao},
	year = {2022},
	doi = {10.1007/978-981-16-0924-4_31},
	pages = {369--408},
}

```

<br />

### Support
##### Related Funding/Grants
<br />

The Chinese University of Hong Kong Direct Grant
<br />
_The linguistic ‘silk road’ in East Asia: Patterns of variation and change in Chinese‐related East Asian contact languages_
(SBRE‐22‐0128)
<br />
*Principal Investigator*: Assistant Professor Wilkinson Daniel Wong Gonzales

<br />
<br />

