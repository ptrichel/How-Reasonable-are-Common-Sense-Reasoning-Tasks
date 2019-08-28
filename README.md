# How Reasonable are Common-Sense Reasoning Tasks?


This repository contains two datasets : the original WSC with the switched version of each sentence whenever the process does not obscure the sentence or affect the rationale used to resolve the target pronoun and the original WSC sentences labeled as associative or non-associative.
It also contains the code to reproduce the results on WSC using GPT2 and on SWAG using BERT (see README.md in folder code). We also include the appendix that contains additional material. 

### Files

* WSC_associative_label.json contains the original sentence *sentence*, a binary label which indicates if the two candidates in the sentence can be switched *is_switchable*, and the switched version of the sentence *sentence_switched*. 

* WSC_associative_label.json contains the orginal sentence *sentence* and a binary label *is_associative* which indicates if one candidate antecedent associates strongly with the clause containing the pronoun.
