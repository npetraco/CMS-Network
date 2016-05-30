# CMS-Network 

A simple and practical model for computing posterior (mean)
probabilities or likelihood ratios corresponding to observed CMS configurations. The
graphical structure of the model was first described by Buckleton (as far as
we know) for use with computing likelihood ratios of CMS runs. The
specific "tweek" we make to the model is to compute CMS run-length
probabilities with a simple multinomial-Dirichlet conjugate model.

The data we use with the multinomial-Dirichlet conjugate model is
contained in the "Historical Data" section of the spreadsheet:
CMS-Network_multinomial-Dirichlet_workbook.xlsx. It consists of data
from:

* Neel, M and Wells M. “A Comprehensive Analysis of Striated Toolmark Examinations. Part 1: Comparing Known Matches to Known Non-Matches”, AFTE J 39(3):176-198 2007.

* N. D. K. Petraco, L. Kuo, H. Chan, E. Phelps, C. Gambino,
P. McLaughlin, Frani Kammerman,
P. Diaczuk, P. Shenkin, N. Petraco and J. Hamby, "Estimates of
Striation Pattern Identi cation Error Rates by Algorithmic Methods," AFTE J. 45(3), 235 (2013)

In order to use this Bayesian Network model:
* Download the CMS-NETWORK file (available in .xdsl or .net formats
which are readable by Genie, SamIam and Hugin).
* Obtain a copy of Genie, SamIam or Hugin Bayesian Network programs.
	* All have no-cost versions for non-commercial/demo use.

Personal laboratory study data can be added to the
CMS-Network_multinomial-Dirichlet_workbook.xlsx spreadsheet to further
update the posterior mean CMS run-length probabilities.
