## Komi-Zyrian [Universal Dependency](universaldependencies.org) annotations

This is an experimental setup for Komi-Zyrian syntactic annotations. It is a part of a larger task to produce Komi-Zyrian gold corpus, and is primarily based into Public Domain data. However, a longer term goal is to include also spoken Komi-Zyrian data from [IKDP language documentation project](https://langdoc.github.io/IKDP). At the moment the files `kpv-ud-test.conllu` and `kpv-ud-ikdp.conllu` reflect these two data sources.

The work is mainly done and coordinated by [Niko Partanen](https://github.com/nikopartanen), and they certainly contain numerous errors as some of the authors have been just recently learning how the annotation model works. The files are being cleaned up and systematized continuously. The annotation work has been done in [LATTICE-CNRS](http://www.lattice.cnrs.fr/) laboratory in Paris. This has been a collaborative effort with several people. Alexandra Kellner has been helping with everything, KyungTae Lim and Thierry Poibeau have been involved especially with LATTICE work, and Rogier Blokland and Michael Rießler with IKDP data. IKDP data and translations (to be added soon) derive directly from [IKDP](https://langdoc.github.io/IKDP/) research project, which was funded by [Kone Foundation](koneensaatio.fi) in 2014-1016.

Morphological annotations are created with [Giellatekno's](http://giellatekno.uit.no/) Komi-Zyrian morphological analysator, and the majority of dependencies are drawn manually, and there have been manual and semi-manual steps all over the place. However, the direction is toward more automatized methodology.

Some of the annotations have been taken from [this collection](http://ilazki.thinkgeek.co.uk/brat/#/uralic/kpv), with the understanding that this data is intended as publicly available.

## List of known problems

- Subordinate clauses are often marked incorrectly
- Conjunctions are classified haphazardly
- Especially kpv-ud-ikdp.conllu treebank contains lots of Russian
    - Not all Russian is marked with full Russian morphological tags, i.e. gender is probably often missing
- kpv-ud-ikpd.conllu still misses some basic annotations here and there
- Things marked in misc column with Note=Check tag need to be checked specifically
- Note=CheckAll means that everything in that sentence has to be checked, but there are only few of those now!

Edits or comments are more than welcome!