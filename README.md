

## Function Lab Overview
In general, the Troyanskaya lab works on functional genomics: the process of analyzing and integrating large-scale experimental datasets in order to understand gene function, the interactions between genes and proteins as they carry out cellular tasks, and the systems-level extensions of these relationships. A basic example might be function assignment, the task of assigning a biological role to an uncharacterized gene/protein (e.g. "We predict that the gene XYZ1 participates in the process of amino acid synthesis.")

More sophisticated functional analyses often involve networks of functional relationships, graphs in which nodes represent genes and edges represent some type of interactions between these genes. These interactions might be physical (direct binding, complexing, protein modifications), genetic (synthetic lethality), regulatory (transcription factors and their targets), or even just indicate participation in the same general pathways (e.g. two enzymes in different parts of the glycolysis pathway).

Part of what allows us to make these fairly high-level predictions is integrating very large amounts of data. Even a single genome-scale dataset such as a microarray can provide a surprising amount of functional information, but high-throughput data tends to be noisy and difficult to interpret in isolation. By mining dozens or hundreds of datasets simultaneously, though, we're able to more easily determine which signals represent real biology and which are just noise. This integration requires both the ability to collect and normalize very large amounts of data and the ability to generate "gold standards" of known functionally related genes. Both aspects of this process - data analysis and gold standard generation - have their own collections of subtleties and pitfalls.

To get a flavor for these tasks, some good papers to start with include:

* Understanding multicellular function and disease with human tissue-specific networks, *Nature Genetics*
* Predicting Effects of Noncoding Variants with Deep Learning-Based Sequence Model, *Nature Methods*
* Targeted Exploration and Analysis of Large Cross-Platform Human Transcriptomic Compendia, *Nature Methods*

## Journal Club
Journal clubs is (roughly) biweekly and immediately before lab meeting in Princeton from 12:00 pm - 1:00 pm. 

Meetings will roughly be divided into 30 min halves with the first 30 minutes for exploring recent papers and the second 30 minute half for the primary presentation. In the first half we will select two papers, one interesting paper that will be the main presentation for the next meeting and a second paper that we will skim and discuss further on the spot. We will primarily be using the FunctionLab citeulike (http://www.citeulike.org) for our pool of articles. If you aren’t already a member of FunctionLab on citeulike email Ruth your citeulike username and she will add you. Feel free to add any interesting papers you come across to the group. 

Everyone is expected to lead discussion on a main paper at some point so check out the rotation spreadsheet (pinned to #journalclub) and sign up for your favorite date before someone else does. Dates are tentative and will adjust with lab meeting changes. 

Contacts: Ruth, Rachel

## Lab Meeting

Our weekly lab meeting consists of:
  1. A one hour presentation with group discussion. Rotation schedule is pinned to #functional.
  2. A series of 30 minute mini group meetings that are project focused. 
 
The lab meeting location alternates between Princeton and Flatiron (NYC).

## Servers

### Princeton
Princeton genomics machine information can be found here: [https://github.com/FunctionLab/function-docs/wiki](https://github.com/FunctionLab/function-docs/wiki)

### Flatiron

## Accounts

New members should create accounts for the following services:

1. Slack (Aaron)
2. Github (Aaron, Alicja)
3. Bitbucket (Aaron, Alicja)

## Genomics Account

If you don't have a Genomics account (typically if you are from CS), you will need to get one. Fill in this form:
http://genomics.princeton.edu/support/forms/account-form.html

## Mailing Lists

We have 2 mailing lists.

One is for current lab members (functionlab@lists.cs.princeton.edu) used for day-to-day issues such as lab meeting reminders.

One is for all lab members (functionlab-all@lists.cs.princeton.edu), current and past, used very rarely for general announcements like reunions, new babies and other life changing events.

To get on the mailing list, visit these sites and fill in your name and email address with a password. You will be put on both lists.

* https://lists.cs.princeton.edu/mailman/listinfo/functionlab
* https://lists.cs.princeton.edu/mailman/listinfo/functionlab-all

## Bayesian Data Integration

[Bayesian Data Integration](http://functionlab.readthedocs.io/en/latest/bayesian-integration.html)
