Valico-README

# Summary
Manually corrected Treebank of Learner Italian drawn from the Valico corpus and correspondent corrected sentences.

# Introduction

UD Italian-Valico is a collection of 36 Italian as a Second Language texts (398 sentences and 6,777 tokens), in the Universal Dependencies formalism elicited from a comic strip. Each text is matched with a corrected version (TH) and both are automatically annotated and then manually corrected. The annotations follow the standard Italian UD guidelines, along with a set of supplementary guidelines for this particular treebank. The treebank represents English, French, German, and Spanish learners of Italian at three different levels (expressed in year of study). There are 9 texts for each native language and 3 texts per level.

The treebank is realised as test set. 

Each sentence id is structured as a-bb_xx-c, where:

	a is the number of the text (from 1 to 36);

	bb is the number of the sentence in the text;

	xx is the ISO code for the learner's native language;

	c is the learner's year of study of Italian.

For example:

1-01_fr-3 indicates the 1st sentence of the 1st text of the treebank which is written by a French learner at their 3rd year of study; and

35-27_en-1 indicates the 27th sentence of the 35th text of the treebank which is written by a English learner at their 1st year of study.

# Acknowledgements

The treebank development has also been possible thanks to Dr. Elisa Corino's (University of Turin) and Dr. Alessandro Mazzei's (University of Turin) valuable advice.

# Citation

You are encouraged to cite the following paper:

@inproceedings{dinuovo2019towards,
  title={Towards an Italian learner treebank in universal dependencies},
  author={Di Nuovo, Elisa and Bosco, Cristina and Mazzei, Alessandro and Sanguinetti, Manuela},
  booktitle={6th Italian Conference on Computational Linguistics, CLiC-it 2019},
  volume={2481},
  pages={1--6},
  year={2019},
  organization={CEUR-WS}
}

<pre>
=== Machine-readable metadata ================================
Data available since: UD v2.8
License: CC BY-SA 4.0
Includes text: yes
Genre: learner-essays
Lemmas: manual native
UPOS: manual native
XPOS: manual native
Features: manual native
Relations: manual native
Contributors: Di Nuovo, Elisa; Sanguinetti, Manuela; Bosco, Cristina
Contributing: elsewhere
Contact: elisa.dinuovo@unito.it
===============================================================================
</pre>