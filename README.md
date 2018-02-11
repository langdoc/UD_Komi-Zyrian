## Komi-Zyrian [Universal Dependency](universaldependencies.org) annotations

This is an experimental setup for Komi-Zyrian syntactic annotations. It is a part of a larger task to produce Komi-Zyrian gold corpus, and is primarily based into Public Domain data. However, a longer term goal is to include also spoken Komi-Zyrian data from [IKDP language documentation project](https://langdoc.github.io/IKDP). At the moment the files `kpv-ud-test.conllu` and `kpv-ud-ikdp.conllu` reflect these two data sources.

The annotations are mainly done by [Niko Partanen](https://github.com/nikopartanen), and they certainly contain numerous errors as the author has just been learning recently how this annotation model works. If you notice mistakes, please open an issue or edit the file directly. The annotation work has been done in [LATTICE-CNRS](http://www.lattice.cnrs.fr/) laboratory in Paris. KyungTae Lim and Michael Rießler have also participated into this work, and it has been conducted in connection to [IKDP-2](https://langdoc.github.io/IKDP-2/) research project funded by (Kone Foundation](koneensaatio.fi).

Morphological annotations are created with [Giellatekno's](http://giellatekno.uit.no/) Komi-Zyrian morphological analysator, and Francis Tyers [vislcg3-to-conllx-input.py](https://github.com/ftyers/ud-scripts/blob/master/vislcg3-to-conllx-input.py) script is used to convert output of that into CoNLL-U format. At the moment [ud-annotatrix] is also being tested, and the editing workflow is largely changing now there. 

Some of the annotations have been taken from [this collection](http://ilazki.thinkgeek.co.uk/brat/#/uralic/kpv), with the understanding that this data is intended as publicly available.
