# MODEL1202170000: Nazaret2008_Dynnik1980_CarbohydrateEnergyMetabolism

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1202170000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1202170000.git@20140916`

## Usage

Importing the model package.

`import MODEL1202170000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**An old paper revisited: ‘‘A mathematical model of carbohydrate energy metabolism. Interaction between glycolysis, the Krebs cycle and the H-transporting shuttles at varying ATPases load’’ by V.V. Dynnik, R. Heinrich and E.E. Sel’kov**   
Nazaret C, Mazat JP. _J Theor Biol_ 2008 Jun;252(3):520-9.
[18304584](http://www.ncbi.nlm.nih.gov/pubmed/18304584) ,  
**Abstract:**   
We revisit an old Russian paper by V.V. Dynnik, R. Heinrich and E.E. Sel’kov
(1980a, b) describing: ‘‘A mathematical model of carbohydrate energy
metabolism. Interaction between glycolysis, the Krebs cycle and the
H-transporting shuttles at varying ATPases load’’. We analyse the model
mathematically and calculate the control coefficients as a function of ATPase
loads. We also evaluate the structure of the metabolic network in terms of
elementary flux modes. We show how this model can respond to an ATPase load as
well as to the glucose supply. We also show how this simple model can help in
understanding the articulation between the major blocks of energetic
metabolism, i.e. glycolysis, the Krebs cycle and the H-transporting shuttles.

**Note:** "dynnik_v1.xml": 

  * created directly from "heinrich.sci" model file provided by Christine Nazaret
  * IDs changed to as per the paper
  * initial conditions set to steady state
  * results of Fig. 3 may be reproduced by running a a parameter scan over b15 in [COPASI](http://www.copasi.org/)

"dynnik_v2.xml":

  * rescaled species such as `s2_e1 = s2 * e1` are introduced whose evolution may be described through reaction participation, rather than via ODEs 
  * original variables are retained as global parameters

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


