# Tokyo Metropolitan University Paraphrase Corpus (TMUP) #

**TMUP** is a Japanese sentential paraphrase corpus. It consists of 655 sentence pairs in total.
* 363 paraphrase sentence pairs
* 292 non-paraphrase sentence pairs

## Data Format ##

*label*	*sentence_A_ja*	*sentence_B_ja*	*source_sentence_en*

## Labels and Statistics ##

| Label              | # Translated | # Extracted |
|:-------------------|-------------:|------------:|
|  1 (paraphrase)    |          363 |           0 |
|  0 (non-paraphrase)|          102 |           0 |
| -1 (non-paraphrase)|            0 |         190 |
|Total               |          465 |         190 |


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

## Contact ##

For inquiry and feedback please contact the authors below:

* Yui Suzuki       &lt;suzuki-yui at ed.tmu.ac.jp&gt;
* Tomoyuki Kajiwara     &lt;kajiwara-tomoyuki at ed.tmu.ac.jp&gt;
* Mamoru Komachi  &lt;komachi at tmu.ac.jp&gt;
