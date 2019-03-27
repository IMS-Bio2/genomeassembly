**Genome Assembly** 
------------------------


This is a training project proposal for students

**Data sets** 
----------------

Ecoli or salmon fish. 


**Assemblers** 
----------------

1. IDBA 
2. SPAdes 
3. Velvet 


**Steps**
-----------

1. Download data sets. 
2. Trim adaptors and do a quality check 
3. The pipeline is divided here. Run each assembler to assemble the data directly or apply digitial normalization to study the effect of digital normalization on genome assembly. 
4. Evaluate the assembled genome using quast. Per assembler evaluation and also with digital normalization versus without normalization 


**More Details** 
------------------------



For adapter trimming and quality check, install trimgalore:: 


    conda install -c bioconda trim-galore 


Lets Install Assemblers. 


IDBA::


    conda install -c bioconda idba 


SPAdes::

 
    conda install -c bioconda spades 

Velvet::


    conda install -c bioconda velvet 




`Read this paper for more details about digital normalization: <http://arxiv.org/abs/1203.4802>`_


You will need to install khmer for diginorm :: 

    
   
    conda install -c bioconda khmer 

