# Introduction to Natural Language Processing
### *Prepared by Laura Stegner, stegner@wisc.edu*
These materials were prepared for the 2021 Data Science Workshop at UW Madison for Natural Language Processing, specifically walking through an example of semantic analysis. The introductory materials are presented below. A Jupyter Notebook containing the tutorial walkthrough is located [here]().

## What is Natural Language Processing?
Natural Language Processing (NLP) can be broadly thought of as the computational tools used to help computers understand and manipulate spoken or written natural language to do useful things. This goal can be achieved with the help of various NLP tasks, such as:
 * Part of speech taggings
 * Speech recognition
 * Word sense disambiguation
 * Sentiment analysis
 * Natural langauge generation
 * Named entity recognition
 * Co-reference resolution
Each of the above tasks is briefly described in [this article](http://www.ibm.com/cloud/learn/natural-language-processing) by IBM. 

Practically, NLP is present in our everyday lives. Some common examples include autocorrect, autocomplete, *related search* terms in a web engine, email filtering, smart agents (e.g. Siri or Alexa), and machine translation (e.g. Google Translate). It is also useful in business applications such as to analyze reviews or to create automated calling systems and chat bot assistants.
 
## When would I want to use NLP?
While NLP is being readily implemented in everyday products, it is also greatly useful in data science. NLP can be used to convert messy, unstructured natural language responses (such as interview data or open responses to survey questions) into more structured, processable data forms. Using NLP techniques to analyze data can serve to speed up processing time and also eliminate inconsistencies from manual analysis.

## Preparation
Prior to our meeting, please review the following materials:
 * (optional but interesting) Article that walks through the history of NLP: https://machinelearningmastery.com/natural-language-processing/
 * High level introduction to NLP (12-minute video): https://www.youtube.com/watch?v=fOvTtapxa9c
 * Slightly different take on NLP (4-minutes video): https://www.youtube.com/watch?v=d4gGtcobq8M
 * Lecture that introduces sentiment analysis (7-minte video): https://www.youtube.com/watch?v=S4z0UG07-b0
 * Article about bias in NLP: https://towardsdatascience.com/bias-in-natural-language-processing-nlp-a-dangerous-but-fixable-problem-7d01a12cf0f7
 * Short article about general ethical considerations when using NLP in a clinical setting: https://arxiv.org/pdf/1703.10090.pdf

Also think about:
 * Times you have encountered NLP in either your research or your daily life.
 * Situations where you don't use NLP but why it would come in handy, and how.
 * Why we should care about the ethical considerations of NLP in data science.

We will have a discussion related to some of these topics :)

Additionally, install the following packages in Python 3:
 * nltk: ```pip3 install nltk==3.3``` or ```python3 -m pip install nltk==3.3```

## Additional Reading / Reference
Chowdhury, G.G. (2003), Natural language processing. Ann. Rev. Info. Sci. Tech., 37: 51-89. https://doi-org.ezproxy.library.wisc.edu/10.1002/aris.1440370103

Hovy, D., & Spruit, S. L. (2016, August). The social impact of natural language processing. In Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (Volume 2: Short Papers) (pp. 591-598). https://www.aclweb.org/anthology/P16-2096.pdf

Leidner, J. L., & Plachouras, V. (2017, April). Ethical by design: Ethics best practices for natural language processing. In Proceedings of the First ACL Workshop on Ethics in Natural Language Processing (pp. 30-40). https://www.aclweb.org/anthology/W17-1604.pdf
