# CHamoru_spellcheck
Hunspell library for CHamoru (Guam Orthography)

Incomplete, and no active development. Partially based on Iloko (Philippines) Orthographic Dictionary by Joseph S. Maza.

Intended as a Hunspell definition file for ELAN (Max Planck) and Firefox.

We ran into the issue that Hunspell is not very well suited to Austronesian languages, specifically with regards to internal reduplication, stem mutation with stress shifts, and (on some platforms, like Firefox) circumfixes. The other problem was that Hunspell was ignoring final ' (glottal stop), which may be a platform instantiation issue, but was enough to kill the usefulness of this approach.

The affix definitions, however, serve as the backbone for other projects, which were build around the Hunspell format.
- [CHamoru stemming tool](https://github.com/drdrphd/CHamoru_morphological_analysis) (also initially developed in the same class)
- [diksionariu.com](https://github.com/drdrphd/diksionariu.com), which incorporates a newer version of the stemmer

If you are interested in trying to set up spellcheck for CHamoru (or other Austronesian language), feel free to use as a starting point, but beware of errors.

# Contributors
Assembled as part of a training class in advanced documentary methods for NSF Grant BCS-1911401, Developing CHamoru Language Infrastructure, Goggue yan CHachalåni Mo'na i Fino'-ta
- David Ruskin
- Sandy Chung (consultant)
- Janice B. P. Toves
- †Jeremy Cepeda
- Daniel Pangelinan
- Roseann Q. Pajarillo
- Marciana Aguon
- Loretta Cruz
- Nolan Flores
- Jeniece Toves Hernandez
