

## Function Lab Overview
In general, the Troyanskaya lab works on functional genomics: the process of analyzing and integrating large-scale experimental datasets in order to understand gene function, the interactions between genes and proteins as they carry out cellular tasks, and the systems-level extensions of these relationships. A basic example might be function assignment, the task of assigning a biological role to an uncharacterized gene/protein (e.g. "We predict that the gene XYZ1 participates in the process of amino acid synthesis.")

More sophisticated functional analyses often involve networks of functional relationships, graphs in which nodes represent genes and edges represent some type of interactions between these genes. These interactions might be physical (direct binding, complexing, protein modifications), genetic (synthetic lethality), regulatory (transcription factors and their targets), or even just indicate participation in the same general pathways (e.g. two enzymes in different parts of the glycolysis pathway).

Part of what allows us to make these fairly high-level predictions is integrating very large amounts of data. Even a single genome-scale dataset such as a microarray can provide a surprising amount of functional information, but high-throughput data tends to be noisy and difficult to interpret in isolation. By mining dozens or hundreds of datasets simultaneously, though, we're able to more easily determine which signals represent real biology and which are just noise. This integration requires both the ability to collect and normalize very large amounts of data and the ability to generate "gold standards" of known functionally related genes. Both aspects of this process - data analysis and gold standard generation - have their own collections of subtleties and pitfalls.

To get a flavor for these tasks, some good papers to start with include:

* Understanding multicellular function and disease with human tissue-specific networks, *Nature Genetics*
* Predicting Effects of Noncoding Variants with Deep Learning-Based Sequence Model, *Nature Methods*
* Targeted Exploration and Analysis of Large Cross-Platform Human Transcriptomic Compendia, *Nature Methods*
