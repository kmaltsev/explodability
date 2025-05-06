# explodability

This repository contains two user-friendly Jupyter Notebooks (written in Python) with the code related to the paper [Maltsev et al. (2025)]([https://arxiv.org/abs/2503.23856]).

The first notebook "**Explodability_and_Fallback_criteria.ipynb**" entails the explodability criteria for the neutrino-driven supernova (SN) mechanism. These address the progenitor problem: which stars will succeed and which will fail to explode when their iron core collapses? The criteria predict the final fate (*failed* or *successful SN*) and constrain the remnant type (*neutron star* or *fallback black hole*) left behind a successful SN explosion based on pre-SN stellar structure variables at the onset of iron-core infall.

The second notebook "**CCSN_recipe_for_BPS.ipynb**" presents the core collapse supernova (CCSN) recipe for binapy population synthesis. It predicts the final fate (*failed* or *successful SN*) and remnant type (neutron star or black hole) of massive single and binary-stripped stars that undergo iron-core collapse at the end of their evolution. As input, the recipe requires the carbon-oxygen core mass $M_\mathrm{CO}$, metallicity $Z$ and information on binary mass transfer history of the star.  Since the predictions can be made already at the end of core helium burning and the recipe is fast-to-evaluate, it is applicable for rapid binary population synthesis and other studies at scale.

In the Jupyter Notebooks, you will find many comments explaining the essential steps and methods, and the most important plotting routines.
