
# OffensiveLanguageResearchLab

This document provides a central point of navigation for a collection of research papers and their associated datasets, primarily focusing on offensive language.

### 1. OLaH-2000 (Version 1)

-   **Description:** The first version of the Offensive Language in Hebrew (OLaH) dataset. This dataset was created for the task of offensive language detection in Semitic languages, with a focus on Hebrew.
    
-   **Language:** Hebrew, Arabic
    
-   **Dataset Repository:**  [OLaH-2000 on GitHub](https://github.com/AbdulrhamnSkout/Dataset/hebrew "null")
    
-   **Associated Paper:**  [Offensive language detection in semitic languages](https://www.inf.uni-hamburg.de/en/inst/ab/lt/publications/2021-alacamyimmam-konvens-mmhs21.pdf#page=15)

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

### 2. OLaH-5000 (Version 2)

-   **Description:** An extended version of the OLaH dataset, containing 5,000 instances. 
    
-   **Language:** Hebrew, Arabic, English
    
-   **Dataset Repository:**  [OLaH-5000 on GitHub](https://github.com/rezeq1/HebrewDataset/Datasets/Hebrew "null")
    
-   **Associated Paper:**  [Offensive language detection in Hebrew: can other languages help?](https://aclanthology.org/2022.lrec-1.396.pdf "null")

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

### 3. OLaH-450 (Taxonomy Annotated)

-   **Description:** A dataset of 450 instances annotated according to a detailed, multi-level taxonomy of offensive language in Hebrew.
    
-   **Language:** Hebrew
    
-   **Dataset Repository:**  [OLaH-450 on GitHub](https://github.com/NataliaVanetik/HebrewOffensiveLanguageByTaxonomy "null")
    
-   **Associated Paper:**  [Hebrew offensive language: Towards a taxonomy and a dataset](https://www.degruyter.com/document/doi/10.1515/lpp-2023-0017/html "null")

-   **BibTeX Citation:**
    ``` bibtex
    @article{LiebeskindVanetikLitvak+2023+325+351,
    	url = {https://doi.org/10.1515/lpp-2023-0017},
    	title = {Hebrew offensive language taxonomy and dataset},
    	title = {},
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

### 4. Propaganda Detection Dataset

-   **Description:** A dataset developed for the task of propaganda detection Telegram posts containing pro-Russian propaganda and benign political texts.
    
-   **Language:** Russian
    
-   **Dataset Repository:**  [Propaganda Dataset on GitHub](https://github.com/Sharik25/propaganda_dataset "null")
    
-   **Associated Paper:**  [Propaganda Detection in Russian Telegram Posts in the Scope of the Russian Invasion of Ukraine](https://aclanthology.org/2023.ranlp-1.123.pdf "null")

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

### 5. OLaH-500 (Detoxification)

-   **Description:** The latest version of the OLaH dataset, specifically curated for the task of text detoxification.
    
-   **Language:** Hebrew
    
-   **Dataset Repository:**  [OLaH-500 Detox on GitHub](https://github.com/NataliaVanetik/HebrewOffensiveLanguageDatasetForTheDetoxificationProject "null")
    
-   **Associated Paper:** This dataset has not been formally published in a paper yet, as it is for an ongoing project.


### 6. TONIC (Negative Campaigning)

-   **Description:** The "deTecting OFFensive and Negative Campaigning" (TONIC) dataset. This research explores using cross-lingual transfer learning to detect negative campaigns in the context of Israeli municipal elections.
    
-   **Language:** Hebrew
    
-   **Dataset Repository:**  [TONIC on GitHub](https://github.com/NataliaVanetik1/TONIC "null")
    
-   **Associated Paper:**  [Cross-lingual Transfer Learning for Detecting Negative Campaign in Israeli Municipal Elections: a Case Study.](https://ceur-ws.org/Vol-3370/paper8.pdf "null")

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

### 7. FARAD Dataset

-   **Description:** This work introduces a novel taxonomy for offensive language in Arabic, accompanied by a new dataset annotated according to this classification scheme.
    
-   **Language:** Arabic
    
-   **Dataset Repository:**  [FARAD on GitHub](https://github.com/NataliaVanetik/ArabicOffensiveLanguage_TaxonomyAndData "null")
    
-   **Associated Paper:**  [Classifying offensive language in Arabic: a novel taxonomy and dataset](https://www.degruyterbrill.com/document/doi/10.1515/lpp-2024-0034/html "null")

-   **BibTeX Citation:**
    ``` bibtex
    @article{LiebeskindAfawiLitvakVanetik+2024+433+462,
    	url = {https://doi.org/10.1515/lpp-2024-0034},
    	title = {Classifying offensive language in Arabic: a novel taxonomy and dataset},
    	title = {},
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

### 8. FARAD-500 Dataset

-   **Description:** A new dataset of offensive texts in Arabic annotated in accordance with multilevel taxonomy.
    
-   **Language:** Arabic
    
-   **Dataset Repository:**  [FARAD-500 on GitHub]( https://github.com/NataliaVanetik/OffensiveLanguageDatasetInArabicFinegrainAnnotation "null")
    
-   **Associated Paper:**  [TBD]("null")

### 9. FTR-dataset (Racism in French Tweets)

-   **Description:** The FTR dataset is designed for detecting racist language in French tweets.
    
-   **Language:** French
    
-   **Dataset Repository:**  [FTR-dataset on GitHub](https://github.com/NataliaVanetik/FTR-dataset "null")
    
-   **Associated Paper:**  [Detection of Racist Language in French Tweets](https://www.mdpi.com/2078-2489/13/7/318 "null")

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
