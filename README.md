**Genome Assembly** 
##################


This is a training project proposal for students

**Data sets** 
##############

Ecoli or salmon fish. 


**Assemblers** 
#############

1. IDBA 
2. SPAdes 
3. Velvet 


**Steps**
##########

1. Download data sets. 
2. Trim adaptors and do a quality check 
3. The pipeline is divided here. Run each assembler to assemble the data directly or apply digitial normalization to study the effect of digital normalization on genome assembly. 
4. Evaluate the assembled genome using quast. Per assembler evaluation and also with digital normalization versus without normalization 


**More Details** 
###################


Install trimgalore for adaptors and quality filtering:: 

.. codeblock:: Install trimgalore
	
       conda install -c bioconda trim-galore 



.. codeblock:: Install IDBA 
	
	conda install -c bioconda idba 




   

