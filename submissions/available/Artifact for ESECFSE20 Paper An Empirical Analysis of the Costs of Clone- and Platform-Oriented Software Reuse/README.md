# Readme

This dataset comprises the supplementary material for the paper "An Empirical Analysis of the Costs of Clone- and Platform-Oriented Software Reuse" accepted at ESEC/FSE 2020.

The dataset comprises:

* **bibFilesManualSearch:** The bib files for all venues analyzed, as provided by DBLP (cf. Section 2.4)
* **dataFromPapers:** The pdf file documents all included studies and the data extracted from these (cf. Section 2.4, 3.2, and 3.3)
* **interviewGuide:** The guide/questions for our semi-structured intreviews in the cost assessment phase (cf. Section 2.3)
* **anonymizedInterviewSummary:** The anonymized and summarized data from the cost-assessment interviews (cf. Section 3.2 and 3.3)


An example of how we used the data elicited from papers (**dataFromPapers**) in Figure 4:

* We assigned quantitative data to specific cost factors or activities, which is based on the descriptions in the referenced papers. For instance, Variant Development (VD) is part of development costs, and indicate din papers as an organization's ability to produce more products at reduced costs. In contrast, development costs can also refer to Feature Development (FD), if a paper states that what the costs of single components or assets in relation to before have been.
* We only considered quantitative data for which we found more than three instances of concretely measured or estimated (based on experiences of employing a platform, not only estimations as an investment justification).
* If we found ranges of values (e.g., -90-95% for VD), we averaged these values.
* We used the resulting values to plot Figure 4.