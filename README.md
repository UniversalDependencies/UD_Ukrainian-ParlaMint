# Summary

UD_Ukrainian-ParlaMint is a collection of Ukrainian parliamentary transcripts annotated in Universal Dependencies. The texts are published on the official website of the Ukrainian parliament (https://www.rada.gov.ua/documents/Stenbul_pz/) and are taken for UD_Ukrainian-ParlaMint from the Ukrainian section of the ParlaMint project (https://www.clarin.eu/parlamint).


# Introduction

The corpus consists of Ukrainian parliamentary plenary session transcripts, with morphological and syntactic annotation checked manually. It contains transcripts of political meetings from 2003 to 2022 from the Ukrainian ParlaMint corpus (Kopp et al., 2023) and other open sources. 
For the corpus, we selected full transcripts of Verkhovna Rada plenary sessions for several days (2003-2022) and one transcript of the National Security and Defense Council meeting (2014). The transcripts provide a fairly accurate record of real speech, preserving elements of colloquial syntax, grammatical inconsistencies, lexical errors, and Ukrainian-Russian code switching. To have the most authentic material, we did not use texts from before 2003, where partial grammatical corrections were observed, nor texts from after 2023, which show signs of excessive normalization due to speech-to-text recognition programs (e.g., replacing vernacular words like щас with зараз, 'now'). We also removed text containing Ukrainian-Russian code switching and some sentences in Russian. The selected sessions are those related to important events in modern Ukrainian history, characterized by a larger share of spontaneous speech, while also including samples of routine parliamentary sessions during which regular laws were considered.
 

# Acknowledgments

Syntactic annotation of the corpus is implemented on the basis of UD_Ukrainian-IU with manual correction. For morphological annotation, we used VESUM morphological dictionary (https://github.com/brown-uk/dict_uk/tree/master) and UD_Ukrainian-IU with manual correction.

## References

* Kopp, Matyáš; Kryvenko, Anna and Rii, Andriana, 2023, Ukrainian parliamentary corpus ParlaMint-UA 4.0.1, Slovenian language resource repository CLARIN.SI, ISSN 2820-4042, http://hdl.handle.net/11356/1900.
* Tomaž Erjavec, Maciej Ogrodniczuk, Petya Osenova, Nikola Ljubešić, Kiril Simov, Andrej Pančur, Michał Rudolf, Matyáš Kopp, Starkaður Barkarson Steinþór Steingrímsson, Çağrı Çöltekin, Jesse de Does, Katrien Depuydt, Tommaso Agnoloni, Giulia Venturi, María Calzada Pérez, Luciana D. de Macedo, Costanza Navarretta, Giancarlo Luxardo, Matthew Coole, Paul Rayson, Vaidas Morkevičius, Tomas Krilavičius, Roberts Darģis, Orsolya Ring, Ruben van Heusden, Maarten Marx, and Darja Fišer. 2022. The ParlaMint corpora of parliamentary proceedings. In “Language Resources and Evaluation”, https://doi.org/10.1007/s10579-021-09574-0


# Changelog

* 2024-11-15 v2.15
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.15
License: CC BY-SA 4.0
Includes text: yes
Genre: government legal spoken
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Shvedova, Maria; Lukashevskyi, Arsenii
Contributing: here
Contact: corpus.textiv@gmail.com
===============================================================================
</pre>
