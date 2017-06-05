# Tokyo Metropolitan University Paraphrase Corpus (TMUP) #

**TMUP** is an evaluation corpus for Japanese paraphrase identification. It consists of 655 sentence pairs in total.
* 363 paraphrase sentence pairs
* 292 non-paraphrase sentence pairs

### Candidate Acquisition Method ###

To acquire both *paraphrase* and *non-paraphrase* instances, we
* generated sentence pairs using Google PBMT and NMT to acquire paraphrases
* extracted sentence pairs from Japanese Wikipedia to acquire non-paraphrases

To acquire both *trivial* and *non-trivial* instances, we
* calculated word overlap rate (Jaccard score) of each sentence pair and uniformly sampled candidates

### Annotation ###

Two annotators judged whether the candidates are paraphrases.

\*For more details, please refer to the paper.

## Data Format ##

label &lt;\t&gt; sentence_A_ja &lt;\t&gt; sentence_B_ja &lt;\t&gt; source_sentence_en *(if applicable)*

### Labels ###
* 1: Paraphrase
* 0: Non-paraphrase

## Citing ##

If you make use of this corpus, please cite the following publication:

Yui Suzuki, Tomoyuki Kajiwara and Mamoru Komachi. Building a Non-Trivial Paraphrase Corpus using Multiple Machine Translation Systems.
In *Proceedings of ACL 2017 Student Research Workshop*, Vancouver, Canada. July 2017 (to appear).

    @inproceedings{,
        author      = {Suzuki, Yui and Kajiwara, Tomoyuki and Komachi, Mamoru},
        title       = {Building a Non-Trivial Paraphrase Corpus
                      using Multiple Machine Translation Systems},
        booktitle   = {Proceedings of ACL 2017 Student Research Workshop},
        month       = {July},
        year        = {2017},
        address     = {Vancouver, Canada},
        publisher   = {Association for Computational Linguistics},
        pages     = {(to appear)},
        url       = {http://www.aclweb.org/anthology/}
    }

## License ##
<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a>

This work is licensed under a [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/).

Copyright (c) 2017 TMU-NLP

## Contact ##

For inquiry and feedback please contact the authors below:

* Yui Suzuki       &lt;suzuki-yui at ed.tmu.ac.jp&gt;
* Tomoyuki Kajiwara     &lt;kajiwara-tomoyuki at ed.tmu.ac.jp&gt;
* Mamoru Komachi  &lt;komachi at tmu.ac.jp&gt;
