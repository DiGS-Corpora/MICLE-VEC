**ENGLISH VERSION**

*This is the GitHub repository of the venetian part (xml:lang="vec") of the [MICLE corpus](https://www.unicaen.fr/projet_de_recherche/micle/). The full repository can be found on the [UniCaen GitLab](https://git.unicaen.fr/mathieu.goux/micle-public)*

*Introduction*

- Most of the texts in the corpus are distributed under the [CC BY-NC-SA 4.0 (Attribution / NonCommercial / ShareAlike / 4.0 Internal) license](https://creativecommons.org/licenses/by-nc-sa/4.0/). Some texts, however, are still protected by copyright and cannot be shared freely in this directory. When the MICLE project does not have permission to share the texts, we will only communicate them with their metadata, without the words, in order to allow research, or in limited context, on the [TXM-CRISCO portal](https://txm-crisco.huma-num.fr/txm/), according to art. L122-5CPI of the French legislation, on which the hosting of the project depends.

*Venetian annotation*

- The Venetian part was annotated manually by Francesco Pinzin in PSD format, in the absence of sufficient documentation for this language, directly in the UPENN system. The labels were then converted to the UD model to serve as a future training model, with some syntactic indications.

*Digital edition*

- For digital editing of the texts, choices of transcriptions and sentence breakdowns, please check the documentation page on the [main website](https://www.unicaen.fr/projet_de_recherche/micle/).

*File format*

- The XML-TEI version includes all the metalinguistic information found in the other formats, with a *header* detailing all the characteristics of the edition and the text concerned. Please refer to it if you have any questions about the editing and encoding of the texts. For ease of navigation, the XML has been encoded with the levels book/chapter/section/paragraph/sentence/word, each continuously numbered and with a resetted counterat each new parent element. In cases where the text has only one level of structure, it was considered as a @section, and we added "empty" @chapter and @book divisions to keep a homogeneous hierarchy of all the texts of the corpus.

- The CONLLU versions of the texts were generated from this main version. Informations about the MICLE project is included in the header, with the title, language and date of the text. Also, the sentence numbering in these versions {Sentence X-X-X-X-X} (POS) #sent_id="X-X-X-X-X" (CONLLU) corresponds to the XPath in the XML-TEI. For example, the sentence "1-27-1-6-1" corresponds to the first sentence of the sixth paragraph of the first section of the twenty-seventh chapter of the first book of this specific text. This numbering, homogeneous between the two versions of the file, facilitates the search.

*Access via TXM-CRISCO*

- The XML-TEI version of the corpus has been uploaded to the [TXM-CRISCO portal](https://txm-crisco.huma-num.fr/txm/) in the "MICLE" folder, to allow reading by the mile (except for copyrighted texts, see *supra*) and searching through the use of [the CQL language](https://www.sketchengine.eu/documentation/corpus-querying/).

*Syntactic parsing*

- The CONLL and the main XML-TEI files offer a dependencies analysis on the sentences of the corpus. The PSD versions and their conversions into XML-TEI propose a constituent analysis. The numbering of the sentences and the XPATH are identical with the main versions, to facilitate their research. With regard to the hierarchical structure of the "base" XML-TEI, there are two additional elements, \<cl\> (for "clause") and \<phr\> ("phrase"), with different attributes. The XML-TEI "Part/Parsed" has been placed separately on the TXM-CRISCO portal so as not to interfere with full text searches.

*Further info*

- For details regarding the tag sets and formats used for this corpus, please visit the various links here.
