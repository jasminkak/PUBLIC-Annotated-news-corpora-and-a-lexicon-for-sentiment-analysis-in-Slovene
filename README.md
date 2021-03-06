# Annotated-news-corpora-and-a-lexicon-for-sentiment-analysis-in-Slovene
Annotated news corpora and a lexicon for sentiment analysis in Slovene

Author: Jože Bučar, Laboratory of Data Technologies, Faculty of Information Studies in Novo mesto, Slovenia (contact: joze.bucar@gmail.com)

Abstract:
This work deals with a construction of the annotated web-crawled corpora and lexicon for sentiment analysis in Slovene. It also provides the tools that were required for their construction. Web crawlers, written in R language, retrieve the content of web pages formatted and annotated with Hyper Text Markup Language (HTML) from the news archives. The corpora contain 256,567 documents enriched with political, business, economic and financial content published between 1 September 2007 and 31 January 2016 from five Slovenian web media: 24ur, Dnevnik, Finance, Rtvslo, Žurnal24. More than ten thousand of them, which were published between 1 September 2007 and 31 December 2013, were manually annotated as negative, neutral and positive on three levels, i.e. document-level, paragraph-level and sentence level. However, we used sentiment classification techniques to estimate the sentiment to documents that were not manually annotated. The lexicon for sentiment analysis (JOB) is based on the AFINN model and uses the List of Slovenian words, i.e., a word list of 354,205 different headwords from the Slovenian words data base.

Keywords:
Annotated corpus, News corpus, Corpus linguistics, Web-crawling, Lexicon, Word list, AFINN, Slovene, Sentiment analysis, Opinion mining, Text mining, Document classification, Monitoring sentiment dynamics, Machine learning

Web resources:
- Slovenian news texts with political, business, economic and financial content published between 1 September 2007 and 31 January 2016 from five Slovenian web media from five web media: www.24ur.com, www.dnevnik.si, www.finance.si, www.rtvslo.si, www.zurnal24.si
- ToTaLe text analyser for Slovene texts - Tokanizer, Tagger and Lemmatizer for Slovene texts, Department of Knowledge Technologies, Jožef Stefan Institute (http://nl.ijs.si/analyse/)
- List of Slovenian words, Fran Ramovš Institute of Slovenian Language ZRC SAZU (http://bos.zrc-sazu.si/besede_en.html)

Type: .txt, .csv, .xlsx, .zip

Encoding: UTF-8

Year: 2013-2016

Acknowledgements:
The authors gratefully acknowledge Fran Ramov{\v s} Institute of Slovenian Language ZRC SAZU for the web list of Slovenian words and Department of Knowledge Technologies, Jožef Stefan Institute for the ToTaLe text analyser for Slovene texts. We also thank Dejan Zidar for his assistance at building the web application and annotators for outstanding work in the context of the annotation process. This paper is based upon work supported by the European Union, The European Regional Development Fund, Slovene Human Resources Development and Scholarship Fund, Ministry of Education, Science and Sport, Slovenia and Young Researcher Programme by Slovenian Research Agency. Our research was carried out within the framework of the Operational Programme for Strengthening Regional Development Potentials for the period 2007-2013, Development Priority 1: Competitiveness and research excellence, Priority Guideline 1.1: Improving the competitive skills and research excellence.

Citation:
If you are a scientist and use the wordlists or code you can cite this publication:

@inproceedings{buvcar2016sentiment,
  title={Sentiment Classification of the Slovenian News Texts},
  author={Bu{\v{c}}ar, Jo{\v{z}}e and Povh, Janez and {\v{Z}}nidar{\v{s}}i{\v{c}}, Martin},
  booktitle={Proceedings of the 9th International Conference on Computer Recognition Systems CORES 2015},
  pages={777--787},
  year={2016},
  organization={Springer}
}

Copyright:
Web media are credited for publishing the news. Web texts, that we required within our project, are under their copyrights, therefore they are available for non-commercial scientific and research purposes only. Research can be performed by a faculty member at an accredited academic institution (college or university) or a research institute member; wherein the research (i) does not now or in the future benefit, or does not now or in the future involve, or is not funded by, a commercial entity; and/or (ii) is not now, or in the future, subject to consulting or licensing obligations or other grant of rights to any commercial entity or third party, and (iii) will not generate any intellectual property rights for any one or more of the faculty member, academic institution, third party, or commercial entity, and (iv) the results of which will be released in the public domain by publication. If your research does not meet these criteria, please contact the author.

Through our work we support the open source community, in order to allow future researchers to contribute to (computational) linguistics community. Thus, some of our work, such as web crawlers, manual and automatic annotations of the news and a lexicon for sentiment analysis in Slovene, is publicly available under Creative Commons copyright license Attribution-ShareAlike 4.0 International (CC BY-SA 4.0 or newer version). This license allows others to use, distribute, reproduce, and build upon this work as long as they credit this work by clearly mentioning its author and title. Moreover, they can license their new work under the identical terms, so any derivatives will also allow commercial use. For more details, check out the information available on the website https://creativecommons.org/licenses/by-sa/4.0/.