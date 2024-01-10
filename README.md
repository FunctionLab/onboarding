# Troyanskaya Lab Overview
In general, the Troyanskaya lab works on functional genomics: the process of analyzing and integrating large-scale experimental datasets in order to understand gene function, the interactions between genes and proteins as they carry out cellular tasks, and the systems-level extensions of these relationships. A basic example might be function assignment, the task of assigning a biological role to an uncharacterized gene/protein (e.g. "We predict that the gene XYZ1 participates in the process of amino acid synthesis.")

More sophisticated functional analyses often involve networks of functional relationships, graphs in which nodes represent genes and edges represent some type of interactions between these genes. These interactions might be physical (direct binding, complexing, protein modifications), genetic (synthetic lethality), regulatory (transcription factors and their targets), or even just indicate participation in the same general pathways (e.g. two enzymes in different parts of the glycolysis pathway).

Part of what allows us to make these fairly high-level predictions is integrating very large amounts of data. Even a single genome-scale dataset such as a microarray can provide a surprising amount of functional information, but high-throughput data tends to be noisy and difficult to interpret in isolation. By mining dozens or hundreds of datasets simultaneously, though, we're able to more easily determine which signals represent real biology and which are just noise. This integration requires both the ability to collect and normalize very large amounts of data and the ability to generate "gold standards" of known functionally related genes. Both aspects of this process - data analysis and gold standard generation - have their own collections of subtleties and pitfalls.

To get a flavor for these tasks, some good papers to start with include:

* [Understanding multicellular function and disease with human tissue-specific networks](http://www.nature.com/ng/journal/v47/n6/full/ng.3259.html), *Nature Genetics*
* [Genome-wide prediction and functional characterization of the genetic basis of autism spectrum disorder](http://www.nature.com/neuro/journal/v19/n11/full/nn.4353.html), *Nature Neuroscience*
* [Predicting effects of noncoding variants with deep learning–based sequence model](http://www.nature.com/nmeth/journal/v12/n10/full/nmeth.3547.html), *Nature Methods*
* [Targeted exploration and analysis of large cross-platform human transcriptomic compendia](http://www.nature.com/nmeth/journal/v12/n3/full/nmeth.3249.html), *Nature Methods*

Additionally, the introduction section of Curtis Huttenhower's Ph.D. [thesis](https://www.cs.princeton.edu/techreports/2008/841.pdf) is an excellent (and thorough) primer on functional genomics and related algorithms.

## Lab Meeting

Our weekly lab meeting consists of:
  1. A slightly more formal one hour presentation (typically with slides, a general project intro, etc.) with group discussion. The rotation schedule is pinned to #functional on Slack.
  2. A 60 minute mini-group meeting where lab members can get feedback on projects (typically quick updates on project progress, challenges, etc.). See below for guidelines.
 
The lab meeting location alternates between Princeton and Flatiron (NYC). Meeting times and locations will be updated on the FunctionLab Google Calendar.


### Mini-group Meeting
 1. Before group meeting, all trainees (grad students & post-docs) will post no more than 4 bullet points on Slack describing what they’ve worked on since the last meeting.
    * No paragraphs, no more than 4 bullets!
    * Feedback is not expected on these posts, but if you have something to mention feel free to reply in a thread directly to the post
 2. Mini-group time is only for items you need feedback on from the group. Please avoid lengthy lists of things you did that week.
    * A typical update should only be a few minutes
    * If you need more group feedback, time will be capped at 10min per person
    * If you only need Olga’s feedback, make sure you have a 1-on-1 meeting scheduled
 3. Group meeting will be capped at 2 hours. Lab members who didn’t get a chance to speak will be able to the following week.


## Journal Club / Primer
Journal clubs / primers are usually immediately before / after lab meeting. (**Currently on hiatus**) 

These meetings are a chance for people to present on either a recent paper or a topic of interest, either biological or technical (e.g., single-cell sequencing, kidney disease, deep learning, coding standards, new packages that may be of use to others).

Everyone is expected to lead discussion at some point so check out the rotation spreadsheet (pinned to #functional on Slack) and sign up for your favorite date before someone else does. Dates are tentative and will adjust with lab meeting changes. 

The rotation is in the journal club / primer rotation spreadsheet (pinned to #functional on Slack).

Contacts: Rachel

## Individual meetings with Olga

These 15-minute individual meetings are typically on the same day as lab meeting. Usually, Princeton folks have their meetings when lab meeting is at Flatiron and vice versa for Simons folks. Meeting details will be updated on the [FunctionLab Google Calendar](https://calendar.google.com/calendar/embed?src=a0qlpr9koc8a3rgl6opq97hbl0%40group.calendar.google.com&ctz=America%2FNew_York).

## Servers

### Princeton
Princeton genomics machine information can be found on the [FunctionLab GitHub wiki](https://github.com/FunctionLab/function-docs/wiki).

### Flatiron
Flatiron/Simons server information can be found on the internal wiki.

## Accounts

New members should create accounts and be added to the FunctionLab group for the following services:

1. [Slack](http://functionlab.slack.com)
2. [Github](https://github.com/FunctionLab/)
3. [Google Calendar](https://calendar.google.com/calendar/embed?src=a0qlpr9koc8a3rgl6opq97hbl0%40group.calendar.google.com&ctz=America%2FNew_York)

Contacts:  [Alicja](mailto:atadych@princeton.edu) , [Rachel](mailto:rsealfon@flatironinstitute.org), [Natalie](mailto:nsauerwald@flatironinstitute.org)
 

## Princeton Genomics Account

If you don't have a Genomics (LSI) account (typically if you are from CS), you will need to get one if you plan to use genomics resources. Fill out this form:
https://frevvo-prod.princeton.edu/frevvo/web/tn/pu.nplc/u/fa933f95-a5f1-4acc-988a-389be9c87b5d/app/_MS6fUDoEEemXbYTKx6ZLAw/formtype/_EyExYK-zEemF2ZSr_5kKrQ/popupform
You don't need to it again if you already have an account from a past rotation.

If you need access to any functionlab servers, please touch base with [Alicja](mailto:atadych@princeton.edu)

## Mailing Lists

We have a mailing list for lab communication. To subcribe, visit this site and fill in your name and email address with a password (note that the password is sometimes sent out as a plaintext email reminder, so don't use anything you use for other important things).

* https://lists.cs.princeton.edu/mailman/listinfo/functionlab

## Software Technologies
The Troyanskaya lab makes extensive use of the following technologies. New lab members should familiarize themselves with the tools that are most relevant to their projects.

* Programming languages
  * R
  * Python
  * C++
  * Javascript
* Source control
  * [GitHub](https://github.com/)
* Bayesian Data Integration
   * Our C++ library: [Sleipnir](http://libsleipnir.bitbucket.org/)
* Data exploration and visualization
  * IDE for R: [Rstudio](https://www.rstudio.com/)
  * R web applications: [Shiny](https://shiny.rstudio.com/)
  * Interactive Python: [IPython/Jupyter](https://ipython.org/)
* Web development
  * Backend
    * Framework: [Django](https://www.djangoproject.com/)
    * REST API: [Django REST Framework](http://www.django-rest-framework.org/)
    * Database: [MySQL](https://www.mysql.com/)
    * Search
      * [elasticsearch](https://www.elastic.co/)
      * [solr](http://lucene.apache.org/solr/)
      * [Haystack](http://haystacksearch.org/)
  * Frontend
    * Vizualization
      * [D3.js](https://d3js.org/)
      * [sigmajs](http://sigmajs.org/)
    * Javascript UI Framework: [React](https://facebook.github.io/react/)
    * [Bootstrap](http://getbootstrap.com/)
* Deployment
  * [docker](https://www.docker.com/)
  * [AWS](https://aws.amazon.com/)

## Additional Topics

* [Bayesian Data Integration](http://functionlab.readthedocs.io/en/latest/bayesian-integration.html)
* [Genomics File Formats](http://functionlab.readthedocs.io/en/latest/file-formats.html)

## Glossary of Lab Terms
* [Magical](https://www.medrxiv.org/content/10.1101/2022.12.06.22282077v1): A hierarchical Bayesian approach that leverages paired scRNA-seq and scATAC-seq data from different conditions to map disease-associated transcription factors, chromatin sites, and genes as regulatory circuits. Resolving chromatin remodeling-linked gene expression changes at cell type resolution is important for understanding disease states. By simultaneously modeling signal variation across cells and conditions in both omics data types, MAGICAL achieves high accuracy on circuit inference. 
  * Point of Contact in Lab: Xi Chen (developer)
* [Seqweaver](https://www.nature.com/articles/s41588-019-0420-0): A deep learning-based algorithmic framework for predicting the RNA-binding protein dysregulation effects of sequence alterations with single nucleotide sensitivity.
  * Point of Contact in Lab: Chris Park (developer), Tess Marvin (frequent user), Aviya Litman (frequent user)
* [Expecto](https://www.nature.com/articles/s41588-018-0160-6): a framework for ab initio sequence-based prediction of mutation gene expression effects and disease risks at tissue-specific level. 
  * Point of Contact in Lab: Ksenia Sokolova (frequent user)
* [CLEVER](https://humanbase.readthedocs.io/en/latest/clever.html): A modular deep-learning based framework for predicting cell-type-specific gene expression directly from DNA sequence.
  * Point of Contact in Lab: Ksenia Sokolova (developer)
* [Sei](https://www.nature.com/articles/s41588-022-01102-2): A framework for integrating human genetics data with sequence information to discover the regulatory basis of traits and diseases. Sei learns a vocabulary of regulatory activities, called sequence classes, using a deep learning model that predicts 21,907 chromatin profiles across >1,300 cell lines and tissues. Sequence classes provide a global classification and quantification of sequence and variant effects based on diverse regulatory activities, such as cell type-specific enhancer functions. 
  * Point of Contact in Lab: Kathy Chen (developer)
* [DeepSEA](https://humanbase.readthedocs.io/en/latest/beluga.html): A deep learning-based algorithmic framework for predicting the chromatin effects of sequence alterations with single nucleotide sensitivity. DeepSEA can accurately predict the epigenetic state of a sequence, including transcription factors binding, DNase I sensitivities and histone marks in multiple cell types, and further utilize this capability to predict the chromatin effects of sequence variants and prioritize regulatory variants.
  * [Beluga](https://doi.org/10.1038/s41588-018-0160-6): The 2019 version of DeepSEA can predict 2002 chromatin features.
  * [DeepSEA - original](https://doi.org/10.1038/nmeth.3547): The original, 2015, version of DeepSEA that can predict 919 chromatin features. 
  * Point of Contact in Lab: Kathy Chen (developer of the related Sei), Ksenia Sokolova (uses Beluga in CLEVER), Chandra Theesfeld (frequent user)
* Variant Effect Prediction (VEP): The difference between the the predicted probability of the reference allele and the alternative allele for a regulatory feature (P𝑎𝑙𝑡−P𝑟𝑒𝑓).
* Tissue-Specific Functional Networks: These tissue-networks are constructed using a Bayesian probabilistic framework based on the prior biological information contained within a massive compendium of omics datasets (e.g., gene co-expression, transcription factor binding, and protein-protein interactions)
  * [GIANT Version 1](https://www.nature.com/articles/ng.3259)
  * [GIANT Version 2](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6030827/)
  * Point of Contact in Lab: Zhicheng Pan, Aaron Wong (developer)
* [Module detection](https://humanbase.readthedocs.io/en/latest/modules.html): Community detection to find cohesive gene clusters from a provided gene list and a selected relevant tissue. Genes within a cluster share local network neighborhoods and together form a cohesive, specific functional module. Module detection enables systematic association of genes - even functionally uncharacterized genes - to specific processes and phenotypes represented in the detected modules. Functional modules are identified with tissue-specific functional networks, which predict gene interactions from massive data collections. Thus the discovered modules potentially capture higher-order tissue-specific function.
* Tapioca: A novel framework for predicting protein-protein interactions from thermal proximity coaggregation data. Created in collaboration with Cristea Lab at Princeton. 
  * Point of Contact in Lab: Tavis Reed (developer)



