# BIOMD0000000376: Bertram2007_IsletCell_Oscillations

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000376.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000376.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000376 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is the model described in the article:  
**Interaction of glycolysis and mitochondrial respiration in metabolic oscillations of pancreatic islets. **   
Bertram R, Satin LS, Pedersen MG, Luciani DS, Sherman A. _Biophys J. _ 2007
Mar 1;92(5):1544-55. Pubmed ID:
[17172305](http://www.ncbi.nlm.nih.gov/pubmed/17172305), doi:
[10.1529/biophysj.106.097154](http://dx.doi.org/10.1529/biophysj.106.097154).  
**Abstract:**   
Insulin secretion from pancreatic beta-cells is oscillatory, with a typical
period of 2-7 min, reflecting oscillations in membrane potential and the
cytosolic Ca(2+) concentration. Our central hypothesis is that the slow 2-7
min oscillations are due to glycolytic oscillations, whereas faster
oscillations that are superimposed are due to Ca(2+) feedback onto metabolism
or ion channels. We extend a previous mathematical model based on this
hypothesis to include a more detailed description of mitochondrial metabolism.
We demonstrate that this model can account for typical oscillatory patterns of
membrane potential and Ca(2+) concentration in islets. It also accounts for
temporal data on oxygen consumption in islets. A recent challenge to the
notion that glycolytic oscillations drive slow Ca(2+) oscillations in islets
are data showing that oscillations in Ca(2+), mitochondrial oxygen
consumption, and NAD(P)H levels are all terminated by membrane
hyperpolarization. We demonstrate that these data are in fact compatible with
a model in which glycolytic oscillations are the key player in rhythmic islet
activity. Finally, we use the model to address the recent finding that the
activity of islets from some mice is uniformly fast, whereas that from islets
of other mice is slow. We propose a mechanism for this dichotomy.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Bertram, Satin, Pedersen, Luciani, Sherman, 2007
version 02** ](http://www.cellml.org/models/bertram_satin_pedersen_luciani_she
rman_2007_version02)  
The original CellML model was created and curated by:  
**Catherine May Lloyd**   
c.lloyd(at)auckland.ac.nz  
The University of Auckland, Bioengineering Institute

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


