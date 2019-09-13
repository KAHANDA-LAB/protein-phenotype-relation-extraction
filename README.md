# PPPred Dataset
The file dataset.csv contains the dataset that we used for relation extraction. Proteins and phenotypes has been replaced by PROT and PHENO in the sentences and ProteinName and PhenotypeName can be used as the original terms used. UniProtId and HPOId columns also contain the mapping between the recognized proteins and phenotypes in text.

# Columns
* Sentence: The original sentence in which a protein and a phenotype are replaced by PROT and PHENO

* ProteinName: The protein name that is replaced by PROT in the original sentence

* UniProtId: The UniProtId associated with the recognized protein in the sentence

* PhenotypeName: The phenotype name that is replaced by PHENO in the original sentence

* HPOId: The HPOId associated with the recognized protein in the sentence

* type: Where the sentence extracted from, abstracts or full-text articles

* Label: The label of the sentence, i.e. Good-CoM or Bad-CoM

# Citation

Please cite the following paper:

Morteza Pourreza Shahri, Gillian Reynolds, Mandi Marie Roe, and Indika Kahanda. 2019. PPPred: Classifying Protein-phenotype Co-mentions Extracted from Biomedical Literature. In Proceedings of the 10th ACM International Conference on Bioinformatics, Computational Biology and Health Informatics (BCB '19). ACM, New York, NY, USA, 414-422. DOI: https://doi.org/10.1145/3307339.3342167
