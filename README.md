# bioinformatics-internship
Mission: To learn and acquire bioinformatics and research skills. 
Vision: To be able to use programing and computational skills to analyse genomics data to find health related solutions and start a career in bioinformatics. 


# Tables of Content
1. [Introduction](#Introduction to bioinformatics)
2. [Unix Shell](#The Unix Shell)
4. [Molecular Biology Concepts](#Molecular Biology Concepts)
5.
6. 
7.

# Introduction to bioinformatics    
  ## Omics
Collectich tech explore role and actions of chemicals that make up an organism.    
  * Transcriptomics
  * Proteo
  * Geno
  * Metabolo
  * Metageno
  * Microbiom

  ## Types of data
 * Genomics
 * Protein seq data, 
 * Gene expression data    
  ## Databases
 * Primary- archival data-non curated e.g Genbank,PDB
 * Secondary, from primary, curated, e.g Refseq, PFAM, un. 
 * Composite, (metadatabases,  
  ## GO
Cellular process
Functions
Components, gene located    

 # The Unix Shell

Absolute path- indicates from the root to the current directory,   
Relative path, shows just the current directory alone    
 ## Cd 
cd .. *previous directory*    
cd *home directory*    
cd - *alternate from current directory backwards, then forth stepwise*    

 ## Ls
ls     
 ## Create a file    
touch    
cp copy file
cp -r copies directory    
rm delete
rm -r directory     
nano edit file    
# View file content    
* cat -allow file view sequentially    
* head 10 first lines of the file, default    
* tail, as head, the last bit    
* less, outlines everything    

  ## Moving files into directories    
mv, rename files and directories    
mv, moves    
   ## Wild cards    
'*' anything, many characters     
'?' one character,     

 ## Pipes and filters    
wc, word count.  
wc -m,c charactes. -l, line couint    
redirect command >    
Append >>    

 ## **NO SPACES**    
Echo command, print on screen.    
Cut, remove, cut out sections of line in  a file    
Uniq, removes duplicates    

 ## Variables    

  * Ctrl A, takes you back to the begining of the command    
  * Ctrl E, end of the command   
  * !$, retrieve last word of last code   
  * !!, Retrieve immediate preceeding command.    
  * Ctrl R, history search in a reverse order, matches letter input next. Most recent to the last. 
  * !(number), repeats commands by number.
  * 
  ## Loops
for loop    

# Molecular Biology Concepts
Basic concepts of molecular biology


# This is a basic introduction to the central dogma of molecular biology.    

**It is the flow of genetic information within a biological system.**    


It can be illustrated as;  

![Central dogma](https://upload.wikimedia.org/wikipedia/commons/thumb/6/68/Central_Dogma_of_Molecular_Biochemistry_with_Enzymes.jpg/256px-Central_Dogma_of_Molecular_Biochemistry_with_Enzymes.jpg)    

Generally comprises the following steps:    

    * Replication 
    * Transcription
    * Translation    
    
    
    
    
# DNA    
Deoxyribonucleic acid.    
Made up of;   
  * A phosphate group    
  
  * Sugar group, Deoxyribose or 2-deoxy-D-ribose sugar (OH replaced with H atom) eg Deoribose, fucose 6-deoxy-L-galactose component of fucoidan of brown algae,   Rhamnose 6-deoxy-L-mannose in plant glycosides....    
  
  * Nucleotides, A,C,T,G.  
  
  * A and G are called Purines, which contains a sinx membered nitrogen containing ring fused with an imidazole.
  
  * A, C, U for RNA are the Pyrimidines which contains only a six membered nitrogen containing ring.   
  
  * Phosphate backbone is formed by the linkage between the 5th phosphate group of one nucleotide and the 3rd OH group of the other. 
     
  * Nucleoside, made up of a purine or a pyrimidine and a 5 carbon ribose sugar.  
   
  * Nuleotide, a nucleoside with an additional phosphate group(s).    
  
  * A chain of nucleotides (polynucleotides) with the sugar-Ribonucleotides eg RNA.    
  
  * Polynucleotides with 2' OH group removed, forms DNA.    
  
  # Organizational structure of DNA
 ![](https://media.springernature.com/lw685/springer-static/image/art%3A10.1186%2F2046-1682-4-8/MediaObjects/13628_2011_Article_8_Fig2_HTML.jpg?as=webp)    
 
  * The dsDNA in eukaryotes is wound 1.7 times around histone proteins to form chromatins.This helps in; 
      * Compressing the DNA to fit the cell
      * Makes the DNA accessible for transcription, regulation of expression, repair and recombination.
  * The chromatins are further packaged together to form chromosomes which are stored in the nucleus of the cell.

 # DNA and RNA    
An illustration of both DNA and RNA.    

![](https://cdn.technologynetworks.com/tn/images/body/dnavsrna-final-final1516884024461.jpg)    

   
DNA | RNA
----|----|
Double  stranded| Single stranded
Longer polynucleotide chains| Relatively shorter polynucleotide chain
Made up of deoxyribose sugars| Made up of ribose sugars
Stable under alkaline condition| Not stable
Found in the nucleus and mitochondria and chloroplast| Formed in the nucleus and transported into the cytoplasm
Vulnerable too UV degredation| Stable under UV
A-T C-G| A-U C-G
Deoxyribonucleic acid| Ribonucleic acid    

 # Amino acids  

Amino acid | 3 letter code | 1 letter code
----|----|----
Alarnine |ala|A
Asparagine |Asn | N
Aspartic acid |Asp | D
Cysteine |Cys | C
Glutamic acid |Glu | E
Glutamine | Gln | Q|
Glycine |Gly | G|
Histidine |His | H|
Isoleucine |ile | I|
Leucine | leu | L|
Lysine |lys | K
Methionine |met | M
Phenylalanine |phe | F
Proline |pro | P
Serine |ser | S
Threonine |thr | T 
Tryptophan |trp| W
Valine |val | V
Tyrosine |tyr | Y
Asparagine or aspartic acid |asx | Z




 # Mutation
-It is the random alterations in the geetic material or the genetic sequence of an organism.     
-They are the sole reason for genetic diversity.    
-Could occur as a result of accidents during the normal chemical transactions of DNA, often during replication.       
-In addition, it might occur due to exposFullscreenure to high-energy electromagnetic radiation such as UV radiations an X-rays, particle radiation or to highly reactive chemicals in the environment.     
-Mutations that occur solely in the body cells are classified as *Somatic mutations* and are often passed on to successive offprings during DNA replication.    
-Mutations in the reproductive cells are classified as *Germline mutations* and are the common causes of severe genetic disorders in most organisms such as Cystic Fibrosis in human. They are inherited to offsprings whose entire germline cells are affected by or carry the mutation. 

Mutations are broadly categorized into;     
     * Point mutation
     * Frameshift mutations 
     
## Types of mutation    

 * Silent mutation, which are changes in the DNA (gene sequence) that do not result in the significant change in the resultatnt amino acid sequence, poses no effect.   
 *  Miscence mutation, causes changes in the codon resulting in a different amino acid, can result in the final protein being non functional. Commonly associated with diseases such as Sickle cell anaemie.
 *  Nonesnece mutation, alteration in the codon resulting into a premature stop codon. Also renders the protein non functional. Has been associated with congenital adrenal hyperplesia.
 *  Deletion, irreversible removal of one or more nucleotides resulting in the change of the reading frame. Results in a completely altered non-functional protein.
 *  Insertion, the addition of one or more amino acids in the sequence of DNA mainly by transposable elements and during replication of repeating elements. Can be reversed by excision of the transposons. Can as well result in a non-functional protein, a mulfunctioning protein and the protein may as well be destroyed by the mechanisms of the body.    


### The concept of an open reading frame    

* It can be described as a pan of DNA sequence between the statrt with a start codon and ends with a stop codon. 
* The start codon is ATG for DNA and AUG for RNA while the stop codons are TAA, TAG, TGA for DNA and UAA, UGA, UAG for RNA.   
* The stop codons signals the biging of mRNA translation while the stop codon signals for termination of translation.
* Also, it can be described as the DNA sequence which is capable of being transcribed without a stop codon. 
* Open reading frames helps in gene prediction.   
* Part of the DNA that has the ability of being translated.    
* Longer ORFs are used in the identification of candidate protein coding regions of a functional protein.    


