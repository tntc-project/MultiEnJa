# Unpolished/Polished translation pairs for the SDs

This directory contains English-to-Japanese translation for [the English SDs](../source-document) produced by professional translators at a translation service provider (TSP).
Aiming at observing actual examples exhibiting art in human translation (or translation strategies), we constrained the process as follows.

* First, we obtained [unpolished translation](en-ja.unpolished) with the following instruction.
	* It must be grammatial and accurately convey the information in the SD.
	* It should be literal as much as possible.  For instance, the order of the words and phrases are as close to as those in the SD.
    * Its quality in terms of fluency with respect to skopos (Vermeer, 2004), norm, register, and text type, as well as cohesiveness (Halliday and Hasan, 1976) is not necessarily extremely high.
* Then, we obtained [polished translation](en-ja.polished) through revising the unpolished translation.
	* It must adhere [the given translation blief](../human-translation/en-ja.brief).
	* It must be fluent and cohesive as if it has been originally written in the target language.  This includes adjustments of information quantity considering the potential readers: e.g., information obvious for the readers should be omitted, while those unfamiliar for the reader should be complemented.

Please refer to Yamamoto et al. (2023) for the detail of the process.

## References

* Michael Alexander Kirkwood Halliday and Ruqaiya Hasan. Cohesion in English. Longman, 1976.
* Mayuka Yamamoto, Atsushi Fujita, and Kyo Kageura 2023. [Refinement of a Typology of Translation Strategies for English-to-Japanese Translation Based on Actual Examples and Multi-Person Discussions](https://doi.org/10.50837/its.2302). Interpreting and Translation Studies, No. 23, pages 15-35, 2023. (in Japanese).
* Hans J. Vermeer. Skopos and Commission in Translational Cction. In Lawrence Venuti, editor, The Translation Studies Reader, pages 227–238, Routledge, 2004.

## Developer

Translations in this directory are created by one of the following three parties (see the workers' ID in [the allocation sheet](en-ja.workers.tsv)).
* National Institute of Information and Communications Technology (NICT): "21N" and "22N"
* The University of Tokyo (UT): "22U"
* Another party: "21R"

The translation data of NICT and UT have been made publicly available under the conditions of license specified below.
The translation data for "21R" are not ready to publish.

## License

See [README.md](../README.md) in the top directory.

## Precautions

* NICT and UT bear no responsibility for the contents of the dataset and assumes no liability for any direct or indirect damage or loss whatsoever that may be incurred as a result of using the dataset.
* If any copyright infringement or other problems are found in the dataset, please contact us at atsushi.fujita[at]nict[dot]go[dot]jp. We will review the issue and undertake appropriate measures as necessary.

## Acknowledgments

The data credited to NICT were developed as a part of work at [Advanced Translation Technology Laboratory](https://att-astrec.nict.go.jp/), [Advanced Speech Translation Research and Development Promotion Center](https://astrec.nict.go.jp/), [National Institute of Information and Communications Technology](https://www.nict.go.jp/en/).
