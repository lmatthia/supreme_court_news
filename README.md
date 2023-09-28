[![DOI](https://img.shields.io/badge/Dataverse%20DOI-10.7910/DVN/1JFUWF-orange)](https://www.doi.org/10.7910/DVN/1JFUWF)


### Overview

This repository contains a sample of evening television news transcripts with identified Supreme Court case mentions analyzed in my dissertation's three empirical chapters examining the volume, format, and presentation of media coverage of the U.S. Supreme Court during the 1990-2018 terms. 

The case mention sample offers granular information on the specific cases referenced on television news, the case stage when they were mentioned, references to other cases alongside them, contextual details of the mention, and the news formats used to discuss them. 

The repo also includes the quantitative analysis and code used in the dissertation chapters and the codebook created for qualitative analysis.

Folder structure:

- The R Markdown files in the [`rmd/`](rmd/) directory provide details about the data analysis. 
- The [`data/`](data/) directory contains data used for this project. 
- The [`docs/`](docs/) directory provides the data dictionary and the codebook used for the qualitative analysis for one of my chapters.

### Stats & Pretty Plots

- [`rmd/001_NewsVolumeStats.Rmd`](rmd/001_NewsVolumeStats.Rmd) contains the results of the statistical analysis for my chapter on news volume. Includes robustness checks. [Rendered here](https://rawcdn.githack.com/lmatthia/supreme_court_news/a1fafa5e0c0c221a556c6a1f89684068d1f62cf5/docs/001_NewsVolumeStats.html)
- [`rmd/002_NewsVolumePlots.Rmd`](rmd/002_NewsVolumePlots.Rmd) presents the plots for the news volume chapter, R version and after manual edits in Adobe Illustrator. [Rendered here](https://rawcdn.githack.com/lmatthia/supreme_court_news/a1fafa5e0c0c221a556c6a1f89684068d1f62cf5/docs/002_NewsVolumePlots.html)
- [`rmd/003_NewsFormatStats.Rmd`](rmd/003_NewsFormatStats.Rmd) contains the results of the statistical analysis for my chapter on news format. Includes robustness checks. [Rendered here](https://rawcdn.githack.com/lmatthia/supreme_court_news/a1fafa5e0c0c221a556c6a1f89684068d1f62cf5/docs/003_NewsFormatStats.html)
- [`rmd/004_NewsFormatPlots.Rmd`](rmd/004_NewsFormatPlots.Rmd) presents the plots for the news format chapter, R version and after manual edits in Adobe Illustrator. [Rendered here](https://rawcdn.githack.com/lmatthia/supreme_court_news/a1fafa5e0c0c221a556c6a1f89684068d1f62cf5/docs/004_NewsFormatPlots.html)
- [`rmd/005_NewsPresentationStats.Rmd`](rmd/005_NewsPresentationStats.Rmd) contains the results of the statistical analysis for my chapter on news presentation (robust sample). [Rendered here](https://rawcdn.githack.com/lmatthia/supreme_court_news/a1fafa5e0c0c221a556c6a1f89684068d1f62cf5/docs/005_NewsPresentationStats.html)
- [`rmd/006_NewsPresentation.Rmd`](rmd/006_NewsPresentation.Rmd) presents the plots for the news presentation chapter, R version and after manual edits in Adobe Illustrator. [Rendered here](https://rawcdn.githack.com/lmatthia/supreme_court_news/a1fafa5e0c0c221a556c6a1f89684068d1f62cf5/docs/006_NewsPresentationPlots.html)

### Data files

In the analysis, the following datasets contained in the repository were used:

#### Transcript-level data

- [`data/NewsTranscriptIndex.csv`](data/NewsTranscriptIndex.csv) is a list of evening news transcripts sourced from NexisUni and Factiva that reference Supreme Court cases. Identifies specific Supreme Court cases mentioned in the transcripts and the stage at which they were discussed.  

#### Mention-level data

- [`data/NewsMentionSample.csv`](data/NewsMentionSample.csv) offers granular information about mentions of Supreme Court cases in news transcripts. Indicates if multiple cases are referenced in a single transcript or mention, the context of the mention, and the various news formats in which the mention appeared.

- [`data/NewsEmotion.csv`](data/NewsEmotion.csv) presents raw counts of emotional language instances derived from a [Docuscope](https://www.cmu.edu/dietrich/english/research-and-publications/docuscope.html) analysis. Quantitative data on the frequency of different emotional language used in news mentions

#### Supreme Court Cases
- [`data/SupremeCourtCaseIndex.csv`](data/SupremeCourtCaseIndex.csv) represents the list of cases I was searching for in the news transcripts. These cases, spanning the Court's terms from 1990-2018, relate to four primary issue areas: abortion, the First Amendment, economic activity, and sex discrimination. Most data is sourced from the [Supreme Court Database](http://scdb.wustl.edu/index.php), with case descriptions supplemented from [Oyez](https://www.oyez.org/).


### License 
I assert no claims of ownership for data acquired through the use of the Supreme Court Database or Oyez.

Data licensed under CC BY. (see Dataverse)

### Contributing

Feel free to build on this project--use the data, make the code better, add to it!

### Code of Conduct
  
Please note that this project is released with a [Contributor Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/). By contributing to this project, you agree to abide by its terms.

### Contact

Lisa Matthias. l.a.matthia@gmail.com






