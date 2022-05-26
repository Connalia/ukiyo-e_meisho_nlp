# Description
This is the repository related to our LREC2022 paper titled 'A Study of Distant Viewing of *Ukiyo-e* Prints'.

We study relationships between Japanese topography and places featured in early modern landscape prints, so-called *ukiyo-e* or ‘pictures of the floating world’. The printed inscriptions on these images feature diverse place-names, both man-made and natural formations. However, due to the corpus's richness and diversity, the precise nature of artistic mediation of the depicted places remains little understood. In this paper, we explored a new analytical approach based on the macroanalysis of images facilitated by Natural Language Processing technologies. This paper presents a small dataset with inscriptions on prints that have been annotated by an art historian for included place-name entities. By fine-tuning and applying a Japanese BERT-based Name Entity Recogniser, we provide a use-case of a macroanalysis of a visual dataset that is hosted by the digital database of the Art Research Center at the Ritsumeikan University, Kyoto. Our work studies the relationship between topography and its visual renderings in early modern Japanese *ukiyo-e* landscape prints, demonstrating how an art historian's work can be improved with Natural Language Processing toward distant viewing of visual datasets.

The first notebook (01) is used to fine-tune a Japanese BERT for GPE and LOC NER, using our data. The second notebook (02) does the same, but merges GPE and LOC into a single PLACE label. 

If you find our work useful to your research, please cite us as:

```
@inproceedings{liagkou-etal-2022-lrec,
    title = "A Study of Distant Viewing of Ukiyo-e Prints",
    author = "Liagkou, Konstantina  and Pavlopoulos, John and Machotka, Ewa",
    booktitle = "Proceedings of the 13th Language Resources and Evaluation Conference (LREC 2022).",
    month = june,
    year = "2022",
    address = "Marseille, France"
}
```
