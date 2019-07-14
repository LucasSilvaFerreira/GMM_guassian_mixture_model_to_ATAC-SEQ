# GMM_guassian_mixture_model_to_ATAC-SEQ
Using a GMM model to separate reads from ATAC-seq experiment in diferent categories.  

<img src='atac_seq_lucas.png'>
ATAC-seq data can present reads with diferent lenghts. This variance between the lenghts has different biological implications. 

Given the lengh of all reads obtained in the ATAC-seq experiment, this model fits a gmm representing 4 types of nucleosome states:  
- Nucleosome free regions (<100 nucleotides)
- MonoNucleosome (~ 200 nucleotides)
- Diunucleosome (~ 400 nucleotides)
- Trinucleosome (~ 600 nucleotides)


-This model receives as an input is a BAM aligment file.   
