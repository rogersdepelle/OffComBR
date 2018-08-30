# OffComBR
Here we provide a data set of web comments which have been annotated for hate speech.

To  measure  the  level  of  agreement  among  the  judges,   we  calculated  the  Fleiss Kappa measure which quantifies degree of agreement over that which would be expected by chance. For OFFCOMBR-2, the value was 0.71, which is considered substantial. 

Since OFFCOMBR-3 only contains instances for which the class has been agreed by all three judges, it made no sense to calculate Kappa. In OFFCOMBR-2, 419 (out of 1,250) comments were considered offensive by at least two judges, representing 32,5% of the total (we noticed that no comment was found offensive by only one judge). For O OFFCOMBR-3, there are 202 offensive comments (out of 1,033), amounting to 19,5% of the cases. As with other datasets for hate speech detection, both versions of OFFCOMBR-3 are unbalanced with negative examples outnumbering positive ones.

Regarding the categories (racism, sexism, homophobia, xenophobia, religious intolerance, or cursing), the results for each dataset are shown in Table 1. The most common category was by far cursing.  The other categories had few comments.  Religious intole rance was found in only one comment and it was not unanimous.

```
@article{Pelle2017,
  title={Offensive Comments in the Brazilian Web: a dataset and baseline results},
  author={Rogers P. de Pelle and Viviane P. Moreira},
  booktitle={6th Brazilian Workshop on Social Network Analysis and Mining (BraSNAM)},
  year={2017},
}
```
