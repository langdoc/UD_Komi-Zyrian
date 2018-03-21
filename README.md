## Komi-Zyrian [Universal Dependency](universaldependencies.org) annotations

This is an collection of annotated Komi-Zyrian data. It is a part of a larger task to produce Komi-Zyrian gold corpus. The part based on written data, `kpv-ud-lattice.conllu` is based entirely on Public Domain data. Other treebank, `kpv-ud-ikdp.conllu`, is based on spoken language data from [IKDP language documentation project](https://langdoc.github.io/IKDP).

The trees in these two treebanks are currently visualized [here](https://langdoc.github.io/UD_Komi-Zyrian/). 

The work is mainly done and coordinated by [Niko Partanen](https://github.com/nikopartanen), and they certainly contain numerous errors as some of the authors have been just recently learning how the annotation model works. However, we have attempted to have different specialists of Komi to check the files (Blokland, Kellner, Rießler). The annotation work has been done in [LATTICE-CNRS](http://www.lattice.cnrs.fr/) laboratory in Paris. This has been a collaborative effort with several people. Alexandra Kellner has been helping with everything, KyungTae Lim and Thierry Poibeau have been involved especially with LATTICE work, and Rogier Blokland and Michael Rießler with IKDP data. IKDP data and translations (to be added soon) derive directly from [IKDP](https://langdoc.github.io/IKDP/) research project, which was funded by [Kone Foundation](koneensaatio.fi) in 2014-1016.

Morphological annotations are created with [Giellatekno's](http://giellatekno.uit.no/) Komi-Zyrian morphological analysator, and the majority of dependencies are drawn manually, and there have been manual and semi-manual steps all over the place. However, the direction is toward more automatized methodology.

Some of the annotations have been taken from [this collection](http://ilazki.thinkgeek.co.uk/brat/#/uralic/kpv), with the understanding that this data is intended as publicly available.

## List of known problems

- Subordinate clauses are often marked incorrectly
- Conjunctions are classified haphazardly
- Annotations with negation seem to need attention
- Especially kpv-ud-ikdp.conllu treebank contains lots of Russian
    - Not all Russian is marked with full Russian morphological tags, i.e. gender is probably often missing
- kpv-ud-ikpd.conllu still misses some basic annotations here and there
- Things marked in misc column with Note=Check tag need to be checked specifically
- Note=CheckAll means that everything in that sentence has to be checked, but there are only few of those now!

Edits or comments are more than welcome!
