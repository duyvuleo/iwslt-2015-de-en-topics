# iwslt-2015-de-en-topics

Date: 2016-06-23
Author(s): Evgeny Matusov, Wenhu Chen
Contact: ematusov [-at-] ebay.com

Original data downloaded from https://wit3.fbk.eu/mt.php?release=2015-01 (de-en.tgz)

If you use this corpus in your work, please cite the paper:
M. Cettolo, C. Girardi, and M. Federico. 2012. WIT3: Web Inventory of Transcribed and Translated Talks. In Proc. of EAMT, pp. 261-268, Trento, Italy.

This corpus train/dev/test split was used for the paper 

Wenhu Chen, Evgeny Matusov, Shahram Khadivi, and Jan-Thorsten Peter.
"Guided Alignment Training for Topic-Aware Neural Machine Translation", 2016.

<Placeholder for Arxiv link>

Please site this paper if you would like to use this corpus in your work.

Package content and format:

####################

./ted-talk-iwslt2014.dev.sents.tsv
./ted-talk-iwslt2014.test.sents.tsv
./ted-talk-iwslt2014.train.sents.tsv

Actual train/dev/test data in tab-separated columns:
column 1: TED talk id
column 2: one or more of 10 topics/keywords
column 3: German sentence
column 4: corresponding English sentence

####################
Lists of TED talk ids for train/dev/test data (can be used to extract it from original TED talk files)
./dev.talkid
./test.talkid
./train.talkid

####################
Whole data (all 2015 IWSLT talks from original distribution), with XML markup of talkid and one or more of 10 topics/keywords

./whole.categ.de-en.de.xml
./whole.categ.de-en.en.xml
####################