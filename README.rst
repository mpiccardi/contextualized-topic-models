Contextualized Regressive Topic Model (CRTM)
--------------------------------------------

This repository contains a fork of the Contextualized Topic Model (CTM) of Bianchi et al. (https://github.com/MilaNLProc/contextualized-topic-models).
It proposes a variant -- nicknamed the Contextualized Regressive Topic Model (CRTM) -- that uses the contextualized representation (i.e., a BERT embedding) also in the model's training objective.

A paper is under review by Elsevier and a preprint should be available soon.

The code can be invoked as:
main.py --epsilon value
where value is any positive number that scales the new, regressive term in the training objective.

All the (small) changes in the code have been highlighted with comments. The only files modified are: main.py, preprocessing.py, ctm.py, and decoding_network.py.
We have also made a few, notional edits to the code to fix deprecation warnings.
