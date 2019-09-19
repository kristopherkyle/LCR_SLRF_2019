## Resource page for the Learner Corpus Workshop at SLRF 2019

This page includes important datasets and other related material for Kris' Learner Corpus Workshop at SLRF 2019 (September 19)

### Learner Corpus
The learner corpus in this workshop is a sample of the written section of the <a href="http://language.sakura.ne.jp/icnale/" target="_blank">ICNALE corpus</a> (Ishikawa, 2013), which is a cross-sectional learner corpus with a substantial amount of participant metadata.

ICNALE includes writing samples from 500 L2 learners of English. During corpus collection, each participant wrote two argumentative essays (one in relation to smoking in public places and another in relation to whether university students should get part time jobs). Participants also took a [Vocabulary Size Test](https://www.lextutor.ca/tests/vst/index.php?mode=test) (VST; a passive vocabulary size test) and reported standardized language proficiency test scores (e.g., TOEFL, TOEIC, IELTS, etc.), which were converted to CEFR levels.

The sample compiled for this workshop (ICNALE 500) includes both writing samples for 500 participants (both essay responses from each participant are included in a single file) across a range of nationalities (these function as an imperfect proxy for L1). In the larger corpus, some participants failed to report a standardized test score, and the corpus compilers estimated their language proficiency using their VST score. However, in this sample, all proficiency scores are based on standardized test scores. Additionally, there are a number of characters in the original corpus that can cause problems with some text analysis programs. These characters have been removed from the ICNALE 500 texts.

[Click here to download the ICNALE 500 corpus](https://kristopherkyle.github.io/LCR_SLRF_2019/data/ICNALE_500_merged_clean.zip) (This also includes a subset of the metadata)

### Linguistic Complexity Indices

All linguistic complexity indices were computed by one of three tools that are freely available on [www.linguisticanalysistools.org](https://www.linguisticanalysistools.org), namely [TAALES](https://www.linguisticanalysistools.org/taales.html), [TAALED](https://www.linguisticanalysistools.org/taaled.html), and [TAASSC](https://www.linguisticanalysistools.org/taassc.html). Full descriptions of these tools can be found in the documents on their related pages and in a few [published papers](http://www.kristopherkyle.com/publicationsgrants.html). A small (but useful!) sample of these indices are briefly described below.

To download a spreadsheet that includes the ICNALE 500 metadata and sores for each of the indices, [click here]()

#### Measuring Lexical Sophistication (TAALES)
The Tool for the Automatic Analysis of Lexical Sophistication (TAALES) measures over 400 indices related to lexical sophistication (i.e., the relative difficulty of learning and/or using a particular word, see also the related definition of Read (2000)). It is our stance that lexical sophistication is a multifaceted construct and should be measured as such (see, e.g., Eguchi & Kyle, under review; Kim, Crossley, & Kyle, 2018, Kyle & Crossley, 2015; Kyle, Crossley, & Berger, 2018, inter alia). Below are brief descriptions of indices that represent a few of these facets.

##### Frequency
Reference corpus frequency is a time-tested method of measuring how sophisticated a word is (see Laufer, 1994; Laufer & Nation, 1995, inter alia). Of course, the corpus from whence frequency figures are derived will likely have an important impact on how well they measure sophistication in a particular language use domain.

Today, we will look at indices that consider content words (nouns, verbs, adjectives, and most adverbs) from a corpus of sitcom and movie subtitles (SUBTLEXus; Brysbaert & New, 2009), which is represented by the index **_SUBTLEXus_Freq_Log_CW_**, and from the magazine section of the Corpus of Contemporary American English (COCA; Davies, 2010), which is represented by the index **_COCA_magazine_lemma_frequency_Log_CW_**. Each index is calculated using logarithmically transformed frequency figures, which helps account for the Zipfian distribution of frequency data. We would expect that on average, more proficient learners will use lower frequency words (i.e., there will be a negative relationship between proficiency and frequency score).

Also related to frequency is the use of academic language. The TAALES index **_All_AWL_Normed_** represents the proportion of academic words in a text (number of academic words/number of total words multiplied by 100). In this case, academic words are defined as the words in Coxhead's (2000) Academic Word List. We would expect that more proficient learners will use a higher proportion of academic words (though this is highly genre-dependent)

##### Concreteness
Concreteness refers to the degree to which a word represents a perceptible entity (a nice, but imperfect antonym for concretness is abstractness). Words such as _apple_ are more concrete, while words such as _ephemeral_ are much less concrete. We would expect that it is easier to make form-meaning mappings with words that are more salient (concreteness can be considered one index of salience, see Crossley & Kyle, 2018). We would therefore expect that more proficient learners would on average use less concrete lexical items (but this is also dependent on genre/task, see Eguchi & Kyle, under review). The index **_Brysbaert_Concreteness_Combined_CW_TAALES_** represents the average concreteness score for content words, based on the crowd-sourced norms for 40,000 words collected by Brysbaert, Warriner, & Kuperman (2014).

##### Lexical decision times
A related way to look at lexical sophistication is to consider listeners' perceptions of sophistication, which is likely related to the definition provided above, but is not precisely the same. One way to measure this type of sophistication is to use lexical decision times that are average across a large number of proficient language users. These are calculated by determining the amount of time it takes a participant to decide whether a word is from the target language (e.g., English) or not. Words with short latencies (such as _cat_) can be accessed quickly, while words with longer latencies (such as _indefiniteness_) cannot be accessed as quickly and can be perceived as being more sophisticated. We would expect that more proficient learners would on average use words that have longer latencies. The index **_LD_Mean_RT_CW_** is based on the norms reported in Balota et al., (2007).

#### Measuring Lexical Diversity (TAALED)
