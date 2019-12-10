# Troyanskaya Lab Overview
In general, the Troyanskaya lab works on functional genomics: the process of analyzing and integrating large-scale experimental datasets in order to understand gene function, the interactions between genes and proteins as they carry out cellular tasks, and the systems-level extensions of these relationships. A basic example might be function assignment, the task of assigning a biological role to an uncharacterized gene/protein (e.g. "We predict that the gene XYZ1 participates in the process of amino acid synthesis.")

More sophisticated functional analyses often involve networks of functional relationships, graphs in which nodes represent genes and edges represent some type of interactions between these genes. These interactions might be physical (direct binding, complexing, protein modifications), genetic (synthetic lethality), regulatory (transcription factors and their targets), or even just indicate participation in the same general pathways (e.g. two enzymes in different parts of the glycolysis pathway).

Part of what allows us to make these fairly high-level predictions is integrating very large amounts of data. Even a single genome-scale dataset such as a microarray can provide a surprising amount of functional information, but high-throughput data tends to be noisy and difficult to interpret in isolation. By mining dozens or hundreds of datasets simultaneously, though, we're able to more easily determine which signals represent real biology and which are just noise. This integration requires both the ability to collect and normalize very large amounts of data and the ability to generate "gold standards" of known functionally related genes. Both aspects of this process - data analysis and gold standard generation - have their own collections of subtleties and pitfalls.

To get a flavor for these tasks, some good papers to start with include:

* [Understanding multicellular function and disease with human tissue-specific networks](http://www.nature.com/ng/journal/v47/n6/full/ng.3259.html), *Nature Genetics*
* [Genome-wide prediction and functional characterization of the genetic basis of autism spectrum disorder](http://www.nature.com/neuro/journal/v19/n11/full/nn.4353.html), *Nature Neuroscience*
* [Predicting Effects of Noncoding Variants with Deep Learning-Based Sequence Model](http://www.nature.com/nmeth/journal/v12/n10/full/nmeth.3547.html), *Nature Methods*
* [Targeted Exploration and Analysis of Large Cross-Platform Human Transcriptomic Compendia](http://www.nature.com/nmeth/journal/v12/n3/full/nmeth.3249.html), *Nature Methods*

Additionally, the introduction section of Curtis Huttenhower's Ph.D. [thesis](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=5&cad=rja&uact=8&ved=0ahUKEwjf0Yni-dXQAhUg24MKHTxRCLsQFgg1MAQ&url=ftp%3A%2F%2Fftp.cs.princeton.edu%2Freports%2F2008%2F841.pdf&usg=AFQjCNGg8uj4I5M4W3j-8IwNS7JSKuEIFA&sig2=y5yUx8Th7Lqa2AnsOj0hlw) is an excellent (and thorough) primer on functional genomics and related algorithms.

## Lab Meeting

Our weekly lab meeting consists of:
  1. A slightly more formal one hour presentation (typically with slides, a general project intro, etc.) with group discussion. The rotation schedule is pinned to #functional on Slack.
  2. A series of 30 minute mini group meetings that are project focused (typically quick updates on project progress, challenges, etc.). 
 
The lab meeting location alternates between Princeton and Flatiron (NYC). Meeting times and locations will be updated on the FunctionLab Google Calendar.


## Journal Club / Primer
Journal clubs / primers are usually immediately before / after lab meeting. (Currently on hiatus) 

These meetings are a chance for people to present on either a recent paper or a topic of interest, either biological or technical (e.g., single-cell sequencing, kidney disease, deep learning, coding standards, new packages that may be of use to others).

Everyone is expected to lead discussion at some point so check out the rotation spreadsheet (pinned to #functional on Slack) and sign up for your favorite date before someone else does. Dates are tentative and will adjust with lab meeting changes. 

The rotation is in the journal club / primer rotation spreadsheet (pinned to #functional on Slack).

Contacts: Ruth, Rachel

## Individual meetings with Olga

These 15-minute individual meetings are typically on the same day as lab meeting. Usually, Princeton folks have their meetings when lab meeting is at Flatiron and vice versa for Simons folks. Meeting details will be updated on the FunctionLab Google Calendar.

## Servers

### Princeton
Princeton genomics machine information can be found at the FunctionLab GitHub wiki (https://github.com/FunctionLab/function-docs/wiki).

### Flatiron
Flatiron/Simons server information can be found on the internal wiki.

## Accounts

New members should create accounts and be added to the FunctionLab group for the following services:

1. Slack
2. Github
3. Google calendar

Contacts: Aaron, Alicja

## Princeton Genomics Account

If you don't have a Genomics account (typically if you are from CS), you will need to get one if you plan to use genomics resources. Fill out this form:
http://genomics.princeton.edu/support/forms/account-form.html

## Mailing Lists

We have two mailing lists for lab communication:

* One is for current lab members (functionlab@lists.cs.princeton.edu) used for day-to-day issues such as lab meeting reminders.

* One is for all lab members (functionlab-all@lists.cs.princeton.edu), current and past, used very rarely for general announcements like reunions, new babies and other life changing events.

To subcribe a the mailing list, visit these sites and fill in your name and email address with a password (note that the password is sometimes sent out as a plaintext email reminder, so don't use anything you use for other important things). You will be put on both lists.

* https://lists.cs.princeton.edu/mailman/listinfo/functionlab
* https://lists.cs.princeton.edu/mailman/listinfo/functionlab-all

## Software Technologies
The Troyanskaya lab makes extensive use of the following technologies. New lab members should familiarize themselves with the tools that are most relevant to their projects.

* Programming languages
  * R
  * Python
  * C++
  * Javascript
* Source control
  * [GitHub](https://github.com/)
  * [BitBucket](https://bitbucket.org/)
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
