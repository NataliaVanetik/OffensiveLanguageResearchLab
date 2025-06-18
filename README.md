
# Offensive Language Research Lab Hub

<img src="https://github.com/NataliaVanetik/OffensiveLanguageResearchLab/blob/main/static/OLRL_Banner_scaled.png" alt="OLRL Banner" style="width:auto; height:50%">

Welcome to the central hub for datasets and research from the Offensive Language Research Lab. Our work is dedicated to advancing the understanding and detection of various forms of problematic language online, including offensive speech, hate speech, propaganda, and negative campaigning.

This document provides a comprehensive and organized collection of the datasets we have developed, along with links to the corresponding research papers and repositories. We aim to make these resources accessible to the broader research community to foster collaboration and further innovation in this critical area of Natural Language Processing.

### Quick Overview of Datasets

| *Dataset*  | *Language* | *Primary Task* | *Size* |
|--|--|--|--|
| [**OLaH-2000**](#olah-2000)  | Hebrew     | Offensive Language Detection | 2,000 comments |
| [**OLaH-5000**](#olah-5000)  | Hebrew     | Offensive Language Detection | 5,000 comments |
| [**OLaH-450**](#olah-450)    | Hebrew     | Fine-grained Offense Taxonomy Classification | 450 instances |
| [**OLaH-500**](#olah-500)    | Hebrew     | Text Detoxification | 450 instances |
| [**OLaA**](#olaa)  	   | Arabic     | Offensive Language Detection | 9,000 comments |
| [**FARAD**](#farad)          | Arabic     | Offensive Language Classification | 6,459 instances  |
| [**FARAD-500**](#farad-500)  | Arabic     | Fine-grained Offense Taxonomy Classification | 500 instances |
| [**TONIC**](#tonic)          | Hebrew     | Detecting negative campaigns in the context of Israeli municipal elections | 2,632 comments |
| [**FTR**](#ftr)              | French     | Detecting racist language in French | 2,856 tweets |
| [**Propaganda-Ru**](#propaganda-ru) | Russian    | Propaganda Detection | 11,320 documents |

# Datasets

<a id="olah-2000"></a>
### 1. OLaH-2000 (Version 1)

-   **Description:** The first version of the Offensive Language in Hebrew (OLaH) dataset, created for offensive language detection in Semitic languages.
-   **Language:** Hebrew
-   **Size:** 2,000 comments.
-   **Source:** Facebook
-   **Task:** Offensive Language Detection.
-   **Dataset Repository:** [OLaH-2000 on GitHub](https://github.com/AbdulrhamnSkout/Dataset/tree/main/hebrew "null" )
-   **Associated Paper:** [Offensive language detection in semitic languages](https://www.inf.uni-hamburg.de/en/inst/ab/lt/publications/2021-alacamyimmam-konvens-mmhs21.pdf#page=15  "null")
-   **BibTeX Citation:**

    ``` bibtex
    @inproceedings{litvak2021offensive,
      author    = {Marina Litvak and Natalia Vanetik and Yaser Nimer and Abdulrhman Skout},
      title     = {Offensive Language Detection in Semitic Languages},
      booktitle = {Proceedings of the Multilingual and Multimodal Hate Speech Workshop 2021},
      pages     = {7--12},
      year      = {2021}
    }
    ```

---

<a id="olah-5000"></a>
### 2. OLaH-5000 (Version 2)

-   **Description:** An extended and multilingual version of the OLaH dataset, used to explore if other languages can aid in detecting offensive content in Hebrew.
-   **Language:** Hebrew
-   **Size:** 5,000 comments.
-   **Source:** Facebook
-   **Task:** Cross-lingual and Multilingual Offensive Language Detection.
-   **Dataset Repository:** [OLaH-5000 on GitHub](https://github.com/rezeq1/HebrewDataset/tree/main/Datasets/Hebrew "null")
-   **Associated Paper:** [Offensive language detection in Hebrew: can other languages help?](https://aclanthology.org/2022.lrec-1.396.pdf  "null")
-   **BibTeX Citation:**
    ``` bibtex
    @inproceedings{litvak-etal-2022-offensive,
        title = "Offensive language detection in {H}ebrew: can other languages help?",
        author = "Litvak, Marina  and
          Vanetik, Natalia  and
          Liebeskind, Chaya  and
          Hmdia, Omar  and
          Madeghem, Rizek Abu",
        editor = "Calzolari, Nicoletta  and
          B{\'e}chet, Fr{\'e}d{\'e}ric  and
          Blache, Philippe  and
          Choukri, Khalid  and
          Cieri, Christopher  and
          Declerck, Thierry  and
          Goggi, Sara  and
          Isahara, Hitoshi  and
          Maegaard, Bente  and
          Mariani, Joseph  and
          Mazo, H{\'e}l{\`e}ne  and
          Odijk, Jan  and
          Piperidis, Stelios",
        booktitle = "Proceedings of the Thirteenth Language Resources and Evaluation Conference",
        month = jun,
        year = "2022",
        address = "Marseille, France",
        publisher = "European Language Resources Association",
        url = "https://aclanthology.org/2022.lrec-1.396/",
        pages = "3715--3723",
        abstract = "Unfortunately, offensive language in social media is a common phenomenon nowadays. It harms many people and vulnerable groups. Therefore, automated detection of offensive language is in high demand and it is a serious challenge in multilingual domains. Various machine learning approaches combined with natural language techniques have been applied for this task lately. This paper contributes to this area from several aspects: (1) it introduces a new dataset of annotated Facebook comments in Hebrew; (2) it describes a case study with multiple supervised models and text representations for a task of offensive language detection in three languages, including two Semitic (Hebrew and Arabic) languages; (3) it reports evaluation results of cross-lingual and multilingual learning for detection of offensive content in Semitic languages; and (4) it discusses the limitations of these settings."
    }
    ```

---

<a id="olah-450"></a>
### 3. OLaH-450 (Taxonomy Annotated)

-   **Description:** A dataset of Hebrew comments annotated according to a detailed, multi-level taxonomy of offensive language, allowing for more nuanced classification.
-   **Language:** Hebrew
-   **Size:** 450 instances.
-   **Source:** Facebook
-   **Task:** Fine-grained Offensive Language Classification.
-   **Supplementary Materials:** The repository also includes comprehensive lists of offensive words in Hebrew, which are valuable for lexicon-based approaches and feature engineering.
    -   `Hebrew-abusive_words_by_category.xlsx`: This file contains offensive words categorized by the aspect of the offense (e.g., racism, ageism, etc.). It includes various morphosyntactic forms (male/female, singular/plural) and notes that some words may belong to multiple categories or appear with grammatical errors as seen in original social media posts.
    -   `Hebrew-abusive_words_joint.xlsx`: A combined, alphabetized list of all offensive words from the categorized file.
-   **Dataset Repository:** [OLaH-450 on GitHub](https://github.com/NataliaVanetik/HebrewOffensiveLanguageByTaxonomy "null")
-   **Associated Paper:** [Hebrew offensive language: Towards a taxonomy and a dataset](https://www.degruyter.com/document/doi/10.1515/lpp-2023-0017/html  "null")
-   **BibTeX Citation:**
    ``` bibtex
    @article{LiebeskindVanetikLitvak+2023+325+351,
    	url = {https://doi.org/10.1515/lpp-2023-0017},
    	title = {Hebrew offensive language taxonomy and dataset},
    	author = {Chaya Liebeskind and Natalia Vanetik and Marina Litvak},
    	pages = {325--351},
    	volume = {19},
    	number = {2},
    	journal = {Lodz Papers in Pragmatics},
    	doi = {doi:10.1515/lpp-2023-0017},
    	year = {2023},
    	lastchecked = {2025-06-14}
    }
    ```

---

<a id="olah-500"></a>
### 4. OLaH-500 (Detoxification)

-   **Description:** The latest version of the OLaH dataset, specifically created for the task of text detoxification. It contains offensive Hebrew sentences paired with neutral, detoxified versions.
-   **Language:** Hebrew
-   **Size:** 500 parallel instances (offensive-neutral pairs).
-   **Source:** Facebook
-   **Task:** Text Detoxification.
-   **Supplementary Materials:** The repository also includes comprehensive lists of offensive words in Hebrew, which are valuable for lexicon-based approaches and feature engineering.
    -   `Hebrew-abusive_words_by_category.xlsx`: This file contains offensive words categorized by the aspect of the offense (e.g., racism, ageism, etc.). It includes various morphosyntactic forms (male/female, singular/plural) and notes that some words may belong to multiple categories or appear with grammatical errors as seen in original social media posts.
    -   `Hebrew-abusive_words_joint.xlsx`: A combined, alphabetized list of all offensive words from the categorized file.
-   **Dataset Repository:** [OLaH-500 Detox on GitHub](https://github.com/NataliaVanetik/HebrewOffensiveLanguageDatasetForTheDetoxificationProject  "null")
-   **Associated Paper:** To be determined (ongoing project).

---

<a id="olaa"></a>
### 5. OLaA - Offensive Language in Arabic

-   **Description:** This dataset is a collection of Arabic comments from Twitter that have been annotated for the general task of offensive language detection.
-   **Language:** Arabic
-   **Size:** 9,000 comments.
-   **Source:** Twitter
-   **Task:** Offensive Language Detection.
-   **Dataset Repository:** [OLaA on GitHub](https://github.com/rezeq1/HebrewDataset/tree/main/Datasets/Arabic "null")
-   **Associated Paper's:** 
	1.  [Offensive language detection in semitic languages](https://www.inf.uni-hamburg.de/en/inst/ab/lt/publications/2021-alacamyimmam-konvens-mmhs21.pdf#page=15  "null")
	2.  [Offensive language detection in Hebrew: can other languages help?](https://aclanthology.org/2022.lrec-1.396.pdf  "null")
-   **Citations:**
	#### Offensive language detection in semitic languages
	``` bibtex
	@inproceedings{litvak2021offensive,
	  author    = {Marina Litvak and Natalia Vanetik and Yaser Nimer and Abdulrhman Skout},
	  title     = {Offensive Language Detection in Semitic Languages},
	  booktitle = {Proceedings of the Multilingual and Multimodal Hate Speech Workshop 2021},
	  pages     = {7--12},
	  year      = {2021}
	}
	```
	#### Offensive language detection in Hebrew: can other languages help?
	``` bibtex
    @inproceedings{litvak-etal-2022-offensive,
        title = "Offensive language detection in {H}ebrew: can other languages help?",
        author = "Litvak, Marina  and
          Vanetik, Natalia  and
          Liebeskind, Chaya  and
          Hmdia, Omar  and
          Madeghem, Rizek Abu",
        editor = "Calzolari, Nicoletta  and
          B{\'e}chet, Fr{\'e}d{\'e}ric  and
          Blache, Philippe  and
          Choukri, Khalid  and
          Cieri, Christopher  and
          Declerck, Thierry  and
          Goggi, Sara  and
          Isahara, Hitoshi  and
          Maegaard, Bente  and
          Mariani, Joseph  and
          Mazo, H{\'e}l{\`e}ne  and
          Odijk, Jan  and
          Piperidis, Stelios",
        booktitle = "Proceedings of the Thirteenth Language Resources and Evaluation Conference",
        month = jun,
        year = "2022",
        address = "Marseille, France",
        publisher = "European Language Resources Association",
        url = "https://aclanthology.org/2022.lrec-1.396/",
        pages = "3715--3723",
        abstract = "Unfortunately, offensive language in social media is a common phenomenon nowadays. It harms many people and vulnerable groups. Therefore, automated detection of offensive language is in high demand and it is a serious challenge in multilingual domains. Various machine learning approaches combined with natural language techniques have been applied for this task lately. This paper contributes to this area from several aspects: (1) it introduces a new dataset of annotated Facebook comments in Hebrew; (2) it describes a case study with multiple supervised models and text representations for a task of offensive language detection in three languages, including two Semitic (Hebrew and Arabic) languages; (3) it reports evaluation results of cross-lingual and multilingual learning for detection of offensive content in Semitic languages; and (4) it discusses the limitations of these settings."
    }
	```

---

<a id="farad"></a>
### 6. FARAD Dataset

-   **Description:** This work introduces a novel taxonomy for offensive language in Arabic, accompanied by a new dataset annotated according to this fine-grained classification scheme.
-   **Language:** Arabic
-   **Size:** 6,000 instances.
-   **Source:** Social Media
-   **Task:** Fine-grained Offensive Language Classification.
-   **Dataset Repository:** [FARAD on GitHub](https://github.com/NataliaVanetik/OffensiveLanguageResearchLab/tree/main/Collections/FARAD "null")
-   **Associated Paper Repository:** [Paper Repository on GitHub](https://github.com/NataliaVanetik/ArabicOffensiveLanguage_TaxonomyAndData "null")
-   **Associated Paper:** [Classifying offensive language in Arabic: a novel taxonomy and dataset](https://www.degruyterbrill.com/document/doi/10.1515/lpp-2024-0034/html "null")
-   **BibTeX Citation:**
    ``` bibtex
    @article{LiebeskindAfawiLitvakVanetik+2024+433+462,
    	url = {https://doi.org/10.1515/lpp-2024-0034},
    	title = {Classifying offensive language in Arabic: a novel taxonomy and dataset},
    	author = {Chaya Liebeskind and Ali Afawi and Marina Litvak and Natalia Vanetik},
    	pages = {433--462},
    	volume = {20},
    	number = {2},
    	journal = {Lodz Papers in Pragmatics},
    	doi = {doi:10.1515/lpp-2024-0034},
    	year = {2024},
    	lastchecked = {2025-06-14}
    }
    ```
 ---

<a id="farad-500"></a>
### 7. FARAD-500 Dataset

-   **Description:** A new dataset of offensive texts in Arabic annotated in accordance with a multi-level taxonomy, building upon the FARAD project.
-   **Language:** Arabic
-   **Size:** 500 instances.
-   **Source:** Social Media
-   **Task:** Fine-grained Offensive Language Classification.
-   **Supplementary Materials:** The repository includes a valuable lexicon of offensive seed words.
    -   `offensive_seed_words_Arabic.xlsx`: This file contains a list of offensive words with their English translations and offense categories. The columns include `English_Meaning`, `Arabic_word`, and `categories` (such as `ableism`, `sexism`, `racism`, `ideologism`, etc.), providing a rich resource for lexicon-based analysis and model training.
-   **Dataset Repository:** [FARAD-500 on GitHub](https://github.com/NataliaVanetik/OffensiveLanguageDatasetInArabicFinegrainAnnotation "null")
-   **Associated Paper:** To be determined.
    
 ---

<a id="tonic"></a>
### 8. TONIC (Negative Campaigning)

-   **Description:** The "deTecting OFFensive and Negative Campaigning" (TONIC) dataset. This research explores using cross-lingual transfer learning to detect negative campaigns in the context of Israeli municipal elections.
-   **Language:** Hebrew
-   **Size:** 2,632 posts.
-   **Source:** Facebook
-   **Task:** Negative Campaigning Detection.
-   **Dataset Repository:** [TONIC on GitHub](https://github.com/NataliaVanetik1/TONIC "null")
-   **Associated Paper:** [Cross-lingual Transfer Learning for Detecting Negative Campaign in Israeli Municipal Elections: a Case Study.](https://ceur-ws.org/Vol-3370/paper8.pdf "null")
-   **BibTeX Citation:**
    ``` bibtex
    @inproceedings{vanetik2023crosslingual,
      author    = {Natalia Vanetik and
                   Marina Litvak and
                   Lin Miao},
      title     = {Cross-lingual Transfer Learning for Detecting Negative Campaign in
                   Israeli Municipal Elections: a Case Study},
      booktitle = {Proceedings of the Text2Story'23 Workshop, Dublin (Republic of Ireland), 2-April-2023},
      series    = {CEUR Workshop Proceedings},
      publisher = {CEUR-WS.org},
      year      = {2023},
      url       = {http://ceur-ws.org}
    }
    ```
    
---

<a id="ftr"></a>
### 9. FTR-dataset (Racism in French Tweets)

-   **Description:** The FTR dataset is designed for detecting racist language in French tweets, addressing a gap in resources for this specific type of hate speech.
-   **Language:** French
-   **Size:** 2,856 tweets.
-   **Source:** Twitter
-   **Task:** Racist Language Detection.
-   **Dataset Repository:** [FTR-dataset on GitHub](https://github.com/NataliaVanetik/FTR-dataset "null")
-   **Associated Paper:** [Detection of Racist Language in French Tweets](https://www.mdpi.com/2078-2489/13/7/318 "null")
-   **BibTeX Citation:**
    ``` bibtex
    @Article{info13070318,
    	AUTHOR = {Vanetik, Natalia and Mimoun, Elisheva},
    	TITLE = {Detection of Racist Language in French Tweets},
    	JOURNAL = {Information},
    	VOLUME = {13},
    	YEAR = {2022},
    	NUMBER = {7},
    	ARTICLE-NUMBER = {318},
    	URL = {https://www.mdpi.com/2078-2489/13/7/318},
    	ISSN = {2078-2489},
    	ABSTRACT = {Toxic online content has become a major issue in recent years due to the exponential increase in the use of the internet. In France, there has been a significant increase in hate speech against migrant and Muslim communities following events such as Great Britain’s exit from the EU, the Charlie Hebdo attacks, and the Bataclan attacks. Therefore, the automated detection of offensive language and racism is in high demand, and it is a serious challenge. Unfortunately, there are fewer datasets annotated for racist speech than for general hate speech available, especially for French. This paper attempts to breach this gap by (1) proposing and evaluating a new dataset intended for automated racist speech detection in French; (2) performing a case study with multiple supervised models and text representations for the task of racist language detection in French; and (3) performing cross-lingual experiments.},
    	DOI = {10.3390/info13070318}
    }
    ```

<a id="propaganda-ru"></a>
### 10. Propaganda-Ru Dataset

-   **Description:** A dataset of Russian Telegram posts developed for propaganda detection, focusing on pro-Russian propaganda related to the 2022 invasion of Ukraine.
-   **Language:** Russian
-   **Size:** 11,320 posts (6,038 propaganda, 5,282 neutral).
-   **Source:** Telegram
-   **Task:** Propaganda Detection.
-   **Dataset Repository:** [Propaganda Dataset on GitHub](https://github.com/Sharik25/propaganda_dataset "null")
-   **Associated Paper:** [Propaganda Detection in Russian Telegram Posts in the Scope of the Russian Invasion of Ukraine](https://aclanthology.org/2023.ranlp-1.123.pdf "null")
-   **BibTeX Citation:**
    ``` bibtex
    @inproceedings{vanetik-etal-2023-propaganda,
        title = "Propaganda Detection in {R}ussian Telegram Posts in the Scope of the {R}ussian Invasion of {U}kraine",
        author = "Vanetik, Natalia  and
          Litvak, Marina  and
          Reviakin, Egor  and
          Tiamanova, Margarita",
        editor = "Mitkov, Ruslan  and
          Angelova, Galia",
        booktitle = "Proceedings of the 14th International Conference on Recent Advances in Natural Language Processing",
        month = sep,
        year = "2023",
        address = "Varna, Bulgaria",
        publisher = "INCOMA Ltd., Shoumen, Bulgaria",
        url = "https://aclanthology.org/2023.ranlp-1.123/",
        pages = "1162--1170",
        abstract = "The emergence of social media has made it more difficult to recognize and analyze misinformation efforts. Popular messaging software Telegram has developed into a medium for disseminating political messages and misinformation, particularly in light of the conflict in Ukraine. In this paper, we introduce a sizable corpus of Telegram posts containing pro-Russian propaganda and benign political texts. We evaluate the corpus by applying natural language processing (NLP) techniques to the task of text classification in this corpus. Our findings indicate that, with an overall accuracy of over 96{\%} for confirmed sources as propagandists and oppositions and 92{\%} for unconfirmed sources, our method can successfully identify and categorize pro- Russian propaganda posts. We highlight the consequences of our research for comprehending political communications and propaganda on social media."
    }
    ```
