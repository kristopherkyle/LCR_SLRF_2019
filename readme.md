## Resource page for the Learner Corpus Workshop at SLRF 2019

_This page includes important datasets and other related material for Kris' Learner Corpus Workshop at SLRF 2019 (September 19, 2019)._

### Learner Corpus
The learner corpus in this workshop is a sample of the written section of the <a href="http://language.sakura.ne.jp/icnale/" target="_blank">ICNALE corpus</a> (Ishikawa, 2013), which is a cross-sectional learner corpus with a substantial amount of participant metadata.

ICNALE includes writing samples from 500 L2 learners of English. During corpus collection, each participant wrote two argumentative essays (one in relation to smoking in public places and another in relation to whether university students should get part time jobs). Participants also took a [Vocabulary Size Test](https://www.lextutor.ca/tests/vst/index.php?mode=test) (VST; a passive vocabulary size test) and reported standardized language proficiency test scores (e.g., TOEFL, TOEIC, IELTS, etc.), which were converted to CEFR levels.

The sample compiled for this workshop (ICNALE 500) includes both writing samples for 500 participants (both essay responses from each participant are included in a single file) across a range of nationalities (these function as an imperfect proxy for L1). In the larger corpus, some participants failed to report a standardized test score, and the corpus compilers estimated their language proficiency using their VST score. However, in this sample, all proficiency scores are based on standardized test scores. Additionally, there are a number of characters in the original corpus that can cause problems with some text analysis programs. These characters have been removed from the ICNALE 500 texts.

[Click here to download the ICNALE 500 corpus](https://kristopherkyle.github.io/LCR_SLRF_2019/data/ICNALE_500_merged_clean.zip) (This also includes a subset of the metadata).

### Linguistic Complexity Indices

All linguistic complexity indices were computed by one of three tools that are freely available on [www.linguisticanalysistools.org](https://www.linguisticanalysistools.org), namely [TAALES](https://www.linguisticanalysistools.org/taales.html), [TAALED](https://www.linguisticanalysistools.org/taaled.html), and [TAASSC](https://www.linguisticanalysistools.org/taassc.html). Full descriptions of these tools can be found in the documents on their related pages and in a few [published papers](http://www.kristopherkyle.com/publicationsgrants.html). A small (but useful!) sample of these indices are briefly described below.

To download a spreadsheet that includes the ICNALE 500 metadata and sores for each of the indices, [click here](https://kristopherkyle.github.io/LCR_SLRF_2019/data/ICNALE_500_Analyzed.csv.zip)

#### Measuring Lexical Sophistication ([TAALES](https://www.linguisticanalysistools.org/taales.html))
The Tool for the Automatic Analysis of Lexical Sophistication (TAALES) measures over 400 indices related to lexical sophistication (i.e., the relative difficulty of learning and/or using a particular word, see also the related definition of Read (2000)). It is our stance that lexical sophistication is a multifaceted construct and should be measured as such (see, e.g., Eguchi & Kyle, under review; Kim, Crossley, & Kyle, 2018, Kyle & Crossley, 2015; Kyle, Crossley, & Berger, 2018, inter alia). Below are brief descriptions of indices that represent a few of these facets.

##### Frequency
Reference corpus frequency is a time-tested method of measuring how sophisticated a word is (see Laufer, 1994; Laufer & Nation, 1995, inter alia). Of course, the corpus from whence frequency figures are derived will likely have an important impact on how well they measure sophistication in a particular language use domain.

Today, we will look at indices that consider content words (nouns, verbs, adjectives, and most adverbs) from a corpus of sitcom and movie subtitles (SUBTLEXus; Brysbaert & New, 2009), which is represented by the index **_SUBTLEXus_Freq_Log_CW_**, and from the magazine section of the Corpus of Contemporary American English (COCA; Davies, 2010), which is represented by the index **_COCA_magazine_lemma_frequency_Log_CW_**. Each index is calculated using logarithmically transformed frequency figures, which helps account for the Zipfian distribution of frequency data. We would expect that on average, more proficient learners will use lower frequency words (i.e., there will be a negative relationship between proficiency and frequency score).

Also related to frequency is the use of academic language. The TAALES index **_All_AWL_Normed_** represents the proportion of academic words in a text (number of academic words/number of total words multiplied by 100). In this case, academic words are defined as the words in Coxhead's (2000) Academic Word List. We would expect that more proficient learners will use a higher proportion of academic words (though this is highly genre-dependent)

##### Concreteness
Concreteness refers to the degree to which a word represents a perceptible entity (a nice, but imperfect antonym for concretness is abstractness). Words such as _apple_ are more concrete, while words such as _ephemeral_ are much less concrete. We would expect that it is easier to make form-meaning mappings with words that are more salient (concreteness can be considered one index of salience, see Crossley & Kyle, 2018). We would therefore expect that more proficient learners would on average use less concrete lexical items (but this is also dependent on genre/task, see Eguchi & Kyle, under review). The index **_Brysbaert_Concreteness_Combined_CW_TAALES_** represents the average concreteness score for content words, based on the crowd-sourced norms for 40,000 words collected by Brysbaert, Warriner, & Kuperman (2014).

##### Lexical decision times
A related way to look at lexical sophistication is to consider listeners' perceptions of sophistication, which is likely related to the definition provided above, but is not precisely the same. One way to measure this type of sophistication is to use lexical decision times that are average across a large number of proficient language users. These are calculated by determining the amount of time it takes a participant to decide whether a word is from the target language (e.g., English) or not. Words with short latencies (such as _cat_) can be accessed quickly, while words with longer latencies (such as _indefiniteness_) cannot be accessed as quickly and can be perceived as being more sophisticated. We would expect that more proficient learners would on average use words that have longer latencies. The index **_LD_Mean_RT_CW_** is based on the norms reported in Balota et al., (2007).

[Click here](https://kristopherkyle.github.io/LCR_SLRF_2019/data/TAALES_Diagnostic.zip) to download a version of the ICNALE 500 corpus that includes index scores for each word in each text.

#### Measuring Lexical Diversity ([TAALED](https://www.linguisticanalysistools.org/taaled.html))
Lexical diversity refers to the amount of lexical variation in a text. The working hypothesis is that language users with a larger vocabulary will produce texts with more diverse lexical items (given a particular task.  Accordingly, we would expect more proficient language users to produce more lexically diverse texts.

The simplest index of lexical diversity is the type-token ratio (TTR), which is calculated as the number of types (unique words) in a text divided by the number of tokens (running words) in a text. One important issue with the type-token ratio (and other related indices such as Guiraud's index) is that it is inherently related to text length. Longer texts will earn lower diversity scores than shorter texts. Because of this issue, in order to compare diversity scores in a set of texts, the length of the text must be held constant (which means losing data) OR a text-independent measure must be used.

There are at least three indices of lexical diversity that are reasonably independent of text length (see McCarthy & Jarvis, 2007, 2010; Zenker & Kyle, 2019, under review), including **_vocD/HD-D_** (Malvern & Richards, 2002; McCarthy & Jarvis, 2007), **_MTLD_** (McCarthy & Jarvis, 2010), and **_MATTR_** (Covington & McFall, 2010).

In this workshop, we will work with moving average type-token ratio (MATTR). MATTR is calculated by calculating TTR using a moving windows approach. We will be using **_mattr50_aw_** (all words) and **_mattr50_cw_** (content words), which use a 50-word window. TTR is calculated for words 1-50, 2-51, 3-52, etc. until the end of the text is reached. MATTR is calculated by averaging the TTR scores for all windows. For both indices, part of speech specific lemmas are used.

[Click here](https://kristopherkyle.github.io/LCR_SLRF_2019/data/TAALED_results_diagnostic.zip) to download a version of the ICNALE 500 corpus that includes lemmatized type and token lists for each text.

#### Measuring Syntactic Complexity ([TAASSC](https://www.linguisticanalysistools.org/taassc.html))
The measurement of syntactic complexity has a long and storied history in SLA (e.g., Larsen-Freeman, 1978; Wolfe-Quintero et al., 1998; Ortega, 2003; Lu, 2010; Biber et al., 2011; Kyle, 2016). In this workshop we will briefly look at two methods of assessing complexity (noun phrase complexity and verb argument construction characteristics.)

##### Noun phrase complexity
Biber et al. (2011) demonstrated that elaboration through noun phrase complexity was a hallmark of academic writing, whilst elaboration through clausal subordination was a hallmark of spoken conversation. A number of learner corpus studies have also demonstrated a relationship between writing proficiency (broadly construed) and noun phrase complexity (e.g., Lu, 2011; Kyle & Crossley, 2018) in that more proficient learners tended to use more complex noun phrases. Today we will look at five indices related to noun-phrase complexity:
- The **_av_nominal_deps_** index represents the average number of modifiers (direct dependents) there are per noun phrase in a text.
- The **_amod_all_nominal_deps_struct_** index represents the average number of adjective modifiers per noun phrase in a text.
- The **_prep_all_nominal_deps_struct_** index represents the average number of prepositional phrases per noun phrase in a text (this is restricted to prepositional phrases that are modifiers of noun phrases)
- The **_CN_C_** (complex nominals per clause) index is a classic index of syntactic complexity that measures the number of elaborated noun phrases per clause (see, e.g., Lu, 2011).
- The **_MLC_** (mean length of clause) index is a classic index of syntactic complexity that measures the number of words per clause. This index can be a reflection of noun phrase complexity, but other linguistic features also contribute to clause lengthening.

[Click here](https://kristopherkyle.github.io/LCR_SLRF_2019/data/TAASSC_Results_phrase_database.txt.zip) to download a version of the ICNALE 500 corpus that includes each noun phrase and its modifiers/dependents. (Note that this is tab-delimited text file that is best viewed in spreadsheet software)

##### Verb argument construction characteristics
Usage-based and construction grammar perspectives on language learning posit that frequency, contingency, and salience are key factors in what is learned by an individual. Accordingly, these features, which may or may not be related to formal complexity, are good candidates for exploring linguistic development and proficiency (see Ellis, 2002; Ellis & Ferreira, 2009a,b; Kyle, 2016; Kyle & Crossley, 2017).

In this tutorial, we will look at a single index **_mag_av_delta_p_verb_cue_type_**, which represents the average strength of association between a verb and its argument construction. Given the verb _give_, for example, the is a high likelihood that we will find the double object construction. Give the verb _sleep_, however, there is a much smaller likelihood that we will find the double object construction. Research has found that more proficient writers tend to use less frequent but more strongly associated verb-VAC combinations (Kyle, 2016; Kyle & Crossley, 2017), but more research is most certainly warranted!

[Click here](https://kristopherkyle.github.io/LCR_SLRF_2019/data/TAASSC_Results_clause_database.txt.zip) to download a version of the ICNALE 500 corpus that includes each clause/VAC and its dependents. (Note that this is tab-delimited text file that is best viewed in spreadsheet software)
