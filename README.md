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

## Journal Club
Journal clubs is (roughly) biweekly and immediately before lab meeting in Princeton from 12:00 pm - 1:00 pm. 

Meetings will roughly be divided into 30 min halves with the first 30 minutes for exploring recent papers and the second 30 minute half for the primary presentation. In the first half we will select two papers, one interesting paper that will be the main presentation for the next meeting and a second paper that we will skim and discuss further on the spot. We will primarily be using the FunctionLab citeulike (http://www.citeulike.org) for our pool of articles. If you aren’t already a member of FunctionLab on citeulike email Ruth your citeulike username and she will add you. Feel free to add any interesting papers you come across to the group. 

Everyone is expected to lead discussion on a main paper at some point so check out the rotation spreadsheet (pinned to #functional on Slack) and sign up for your favorite date before someone else does. Dates are tentative and will adjust with lab meeting changes. 

Contacts: Ruth, Rachel

## Lab Meeting

Our weekly lab meeting consists of:
  1. A one hour presentation with group discussion. The rotation schedule is pinned to #functional on Slack.
  2. A series of 30 minute mini group meetings that are project focused. 
 
The lab meeting location alternates between Princeton and Flatiron (NYC). Meeting times and locations will be updated on the FunctionLab Google Calendar.

Contact: Vicky

## Servers

### Princeton
Princeton genomics machine information can be found at the FunctionLab GitHub wiki.

### Flatiron
Flatiron/Simons server information can be found on the internal wiki.

## Accounts

New members should create accounts and be added to the FunctionLab group for the following services:

1. Slack (contacts: Aaron, Alicja, Vicky)
2. Github (contacts: Aaron, Alicja)
3. Bitbucket (contacts: Aaron, Alicja)

## Princeton Genomics Account

If you don't have a Genomics account (typically if you are from CS), you will need to get one. Fill out this form:
http://genomics.princeton.edu/support/forms/account-form.html

## Mailing Lists

We have two mailing lists for lab communication:

* One is for current lab members (functionlab@lists.cs.princeton.edu) used for day-to-day issues such as lab meeting reminders.

* One is for all lab members (functionlab-all@lists.cs.princeton.edu), current and past, used very rarely for general announcements like reunions, new babies and other life changing events.

To subcribe a the mailing list, visit these sites and fill in your name and email address with a password. You will be put on both lists.

* https://lists.cs.princeton.edu/mailman/listinfo/functionlab
* https://lists.cs.princeton.edu/mailman/listinfo/functionlab-all

## Additional Topics

* [Bayesian Data Integration](http://functionlab.readthedocs.io/en/latest/bayesian-integration.html)
* [Genomics File Formats](http://functionlab.readthedocs.io/en/latest/file-formats.html)
