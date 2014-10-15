# MODEL0912180000: calzone_etal_2010_cellfate_master_model

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL0912180000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL0912180000.git@20140916`


# Model Notes


**Attention:** As this model cannot be encoded in SBML at this time, the SBML file contains the whole model in [GINML](http://gin.univ-mrs.fr/GINsim/ginml.html) , a different XML model description language, in its main annotation element. Still, the model can be loaded by [GINsim](http://gin.univ-mrs.fr/GINsim/) as it is by just ignoring the error messages. Alternatively, you can remove the surrounding SBML elements in a text editor and save the remaining GINsim file with the suffix _.ginml_ . To do this keep the first line with the xml declaration and all lines starting from `<gxl xmlns="http://gin.univ-mrs.fr/GINsim/" xmlns:xlink="http://www.w3.org/1999/xlink">` until `</glx>` and delete or comment out all others.   

This is the master model described in: **Mathematical Modelling of Cell-Fate
Decision in Response to Death Receptor Engagement**  
Calzone L, Tournier L, Fourquet S, Thieffry D, Zhivotovsky B, Barillot E and
Zinovyev A.; _PLoS Comput Biol._ 2010 Mar 5; **6(3)** :e1000702. PubmedID:
[20221256](http://www.ncbi.nlm.nih.gov/pubmed/20221256) ; doi:
[10.1371/journal.pcbi.1000702](http://dx.doi.org/10.1371/journal.pcbi.1000702)
;  
**Abstract:**   
Cytokines such as TNF and FASL can trigger death or survival depending on cell
lines and cellular conditions. The mechanistic details of how a cell chooses
among these cell fates are still unclear. The understanding of these processes
is important since they are altered in many diseases, including cancer and
AIDS. Using a discrete modelling formalism, we present a mathematical model of
cell fate decision recapitulating and integrating the most consistent facts
extracted from the literature. This model provides a generic high-level view
of the interplays between NFkappaB pro-survival pathway, RIP1-dependent
necrosis, and the apoptosis pathway in response to death receptor-mediated
signals. Wild type simulations demonstrate robust segregation of cellular
responses to receptor engagement. Model simulations recapitulate documented
phenotypes of protein knockdowns and enable the prediction of the effects of
novel knockdowns. In silico experiments simulate the outcomes following ligand
removal at different stages, and suggest experimental approaches to further
validate and specialise the model for particular cell types. We also propose a
reduced conceptual model implementing the logic of the decision process. This
analysis gives specific predictions regarding cross-talks between the three
pathways, as well as the transient role of RIP1 protein in necrosis, and
confirms the phenotypes of novel perturbations. Our wild type and mutant
simulations provide novel insights to restore apoptosis in defective cells.
The model analysis expands our understanding of how cell fate decision is
made. Moreover, our current model can be used to assess contradictory or
controversial data from the literature. Ultimately, it constitutes a valuable
reasoning tool to delineate novel experiments.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


