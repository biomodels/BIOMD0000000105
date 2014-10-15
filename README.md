# BIOMD0000000105: BIOMD0000000105

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000105.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000105.git@20140916`


# Model Notes


Proctor2007 - Age related decline of proteolysis, ubiquitin-proteome system

This is a stochastic model of the ubiquitin-proteasome system for a generic
pool of native proteins (NatP), which have a half-life of about 10 hours under
normal conditions. It is assumed that these proteins are only degraded after
they have lost their native structure due to a damage event. This is
represented in the model by the misfolding reaction which depends on the level
of reactive oxygen species (ROS) in the cell. Misfolded proteins (MisP) are
first bound by an E3 ubiquitin ligase. Ubiquitin (Ub) is activated by E1
(ubiquitin-activating enzyme) and then passed to E2 (ubiquitin-conjugating
enzyme). The E2 enzyme then passes the ubiquitin molecule to the E3/MisP
complex with the net effect that the misfolded protein is monoubiquitinated
and both E2 and E3 are released. Further ubiquitin molecules are added in a
step-wise manner. When the chain of ubiquitin molecules is of length 4 or
more, the polyubiquitinated misfolded protein may bind to the proteasome. The
model also includes de-ubiquitinating enzymes (DUB) which cleave ubiquitin
molecules from the chain in a step-wise manner. They work on chains attached
to misfolded proteins both unbound and bound to the proteasomes. Misfolded
proteins bound to the proteasome may be degraded releasing ubiquitin.
Misfolded proteins including ubiquitinated proteins may also aggregate.
Aggregates (AggP) may be sequestered (Seq_AggP) which takes them out of harm's
way or they may bind to the proteasome (AggP_Proteasome). Proteasomes bound by
aggregates are no longer available for protein degradation.

Figure 2 and Figure 3 has been simulated using Gillespie2.

This model is described in the article:

[An in silico model of the ubiquitin-proteasome system that incorporates
normal homeostasis and age-related
decline.](http://identifiers.org/pubmed/17408507)

Proctor CJ, Tsirigotis M, Gray DA.

BMC Syst Biol 2007; 1: 17

Abstract:

BACKGROUND: The ubiquitin-proteasome system is responsible for homeostatic
degradation of intact protein substrates as well as the elimination of damaged
or misfolded proteins that might otherwise aggregate. During ageing there is a
decline in proteasome activity and an increase in aggregated proteins. Many
neurodegenerative diseases are characterised by the presence of distinctive
ubiquitin-positive inclusion bodies in affected regions of the brain. These
inclusions consist of insoluble, unfolded, ubiquitinated polypeptides that
fail to be targeted and degraded by the proteasome. We are using a systems
biology approach to try and determine the primary event in the decline in
proteolytic capacity with age and whether there is in fact a vicious cycle of
inhibition, with accumulating aggregates further inhibiting proteolysis,
prompting accumulation of aggregates and so on. A stochastic model of the
ubiquitin-proteasome system has been developed using the Systems Biology Mark-
up Language (SBML). Simulations are carried out on the BASIS (Biology of
Ageing e-Science Integration and Simulation) system and the model output is
compared to experimental data wherein levels of ubiquitin and ubiquitinated
substrates are monitored in cultured cells under various conditions. The model
can be used to predict the effects of different experimental procedures such
as inhibition of the proteasome or shutting down the enzyme cascade
responsible for ubiquitin conjugation. RESULTS: The model output shows good
agreement with experimental data under a number of different conditions.
However, our model predicts that monomeric ubiquitin pools are always depleted
under conditions of proteasome inhibition, whereas experimental data show that
monomeric pools were depleted in IMR-90 cells but not in ts20 cells,
suggesting that cell lines vary in their ability to replenish ubiquitin pools
and there is the need to incorporate ubiquitin turnover into the model.
Sensitivity analysis of the model revealed which parameters have an important
effect on protein turnover and aggregation kinetics. CONCLUSION: We have
developed a model of the ubiquitin-proteasome system using an iterative
approach of model building and validation against experimental data. Using
SBML to encode the model ensures that it can be easily modified and extended
as more data become available. Important aspects to be included in subsequent
models are details of ubiquitin turnover, models of autophagy, the inclusion
of a pool of short-lived proteins and further details of the aggregation
process.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000105](http://identifiers.org/biomodels.db/BIOMD0000000105).

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024).

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


