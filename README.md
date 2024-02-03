*** Dataset that is used for this fine tuning - https://huggingface.co/datasets/conll2003 ***

*** Sample - ***

id                                     Tokens                                                                           NER tags
-------------------------------------------------------------------------------------------------------------------------------------------------
0	               [ "EU", "rejects", "German", "call", "to", "boycott", "British", "lamb", "." ]	             [ 3, 0, 7, 0, 0, 0, 7, 0, 0 ]
-------------------------------------------------------------------------------------------------------------------------------------------------
1	                           [ "Peter", "Blackburn" ]		                                                                   [ 1, 2 ]
-------------------------------------------------------------------------------------------------------------------------------------------------

**Total Tags - 9**

**Tags - {'O': 0, 'B-PER': 1, 'I-PER': 2, 'B-ORG': 3, 'I-ORG': 4, 'B-LOC': 5, 'I-LOC': 6, 'B-MISC': 7, 'I-MISC': 8}**


*** Tags Meaning - ***

- O means the word doesn’t correspond to any entity.
- B-PER/I-PER means the word corresponds to the beginning of/is inside a person entity.
- B-ORG/I-ORG means the word corresponds to the beginning of/is inside an organization entity.
- B-LOC/I-LOC means the word corresponds to the beginning of/is inside a location entity.
- B-MISC/I-MISC means the word corresponds to the beginning of/is inside a miscellaneous entit
