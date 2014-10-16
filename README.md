# BIOMD0000000258: Ortega2006_bistability_doublePhosphorylation

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000258.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000258.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000258 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Bistability from double phosphorylation in signal transduction. Kinetic and structural requirements.**   
Ortega F, Garcés JL, Mas F, Kholodenko BN, Cascante M. _FEBS J._ 2006
Sep;273(17):3915-26. [16934033](http://www.ncbi.nlm.nih.gov/pubmed/16934033) ,  
**Abstract:**   
Previous studies have suggested that positive feedback loops and
ultrasensitivity are prerequisites for bistability in covalent modification
cascades. However, it was recently shown that bistability and hysteresis can
also arise solely from multisite phosphorylation. Here we analytically
demonstrate that double phosphorylation of a protein (or other covalent
modification) generates bistability only if: (a) the two phosphorylation (or
the two dephosphorylation) reactions are catalyzed by the same enzyme; (b) the
kinetics operate at least partly in the zero-order region; and (c) the ratio
of the catalytic constants of the phosphorylation and dephosphorylation steps
in the first modification cycle is less than this ratio in the second cycle.
We also show that multisite phosphorylation enlarges the region of kinetic
parameter values in which bistability appears, but does not generate
multistability. In addition, we conclude that a cascade of
phosphorylation/dephosphorylation cycles generates multiple steady states in
the absence of feedback or feedforward loops. Our results show that bistable
behavior in covalent modification cascades relies not only on the structure
and regulatory pattern of feedback/feedforward loops, but also on the kinetic
characteristics of their component proteins.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2010 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


