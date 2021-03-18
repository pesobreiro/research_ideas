# Research Ideas

## Predicting time in swimmers
Testing  multivariate linear regression to predict swimming results

## Research Reproducibility
The developments that have been taking place in technologies and information systems allow greater capacities for data processing and analysis, facilitating the development of research. We propose an approach to support reproducibility (Peng, 2009), for Systematic Literature Reviews (SLR) in Football Coaches Intervention and familiarize researchers with an improved workflow using R, R Markdown, and some libraries in the process of developing for scientific production.

## Sentiment Analysis
Testing OpLexicon 3.0 a sentiment lexicon for the Portuguese lan-guage built using multiple sources of information, that which has four categories of words: verbs, adjectives, hashtag, and emoticons. The lexicon is constituted of around 32.000 polarized words classified by their morphological category annotated with po-larities positive, negative, and neutral. 

The sentiment analysis was developed in R, following the steps: 
	(1) extract the words in the answer of for the open question; 
	(2) map the word with OpLexicon words, selecting their polarity negative or positive value or neutral (zero); (3) sum the polarity present in each word in the answer and 
	(4) the sentiment was calculated summing the polarity values (negative, neutral or positive value) using all the words. After the cal-culation of the sentiment, 
	(5) the last step involved a conversion of the values to an ordinal scale, to convert to a scale aligned with the other questions of a survey, calculating the median in the negative and positive words in each question: (1) negative values less or equal to the negative values median was assigned one, (2) negative values less than zero and greater than median two; (3) 0 (neutral) was assigned three; (4) positive value and less than positive median was assigned four and positive value greater than positive mean five. The null values were replaced by 0 representing the absence of answer.
