# PCR.PTML-project

# PCR.PTML Artificial Intelligence-Eperimental Microbiome Analysis: Applications to Ancient DNA and Tree Soil Metagenomics Cases of Study.

# Authors 
Jose L. Rodriguez.a#, Estefania Ascencio.b,c,d,e#, Jose M. Ageitos a, Lucia Feijoo a, Shan He b,c,e Amirreza Daghighi b,c, Gerardo Casanola b, Cristian R. Munteanu d, Santiago Rodriguez Yañezd*, Alejandro Pazosd, Harbil Bediagae Brenda Duran Ordialesf Raquel Estebanf,Ana-Maria Heres gh, Jorge Curiel Yusteg l, Lur Epeldei, Bakhtiyor Rasulev b,cTomas Gonzaleza ,Sonia Arrasate j, and Humberto  González j,k,,l *      



# Affiliations 
1Department of Microbiology and Parasitology, Faculty of Pharmacy, 
University of Santiago de Compostela, 15782, Santiago de Compostela, Spain.
2 Department of Coatings and Polymeric Materials, North Dakota State University, 
58102, Fargo, North Dakota, United States.
3 Biomedical Engineering Program, North Dakota State University, Fargo, ND 58102, USA.
4 RNASA-IMEDIR, Department of Information and Communication Technologies,
Computer Science Faculty, University of Coruña (UDC), 15071, A Coruña, Spain.
5 IKERDATA S.L., ZITEK, University of Basque Country UPVEHU, 
Rectorate Building, 48940 Leioa, Spain.
6 Department of Organic and Inorganic Chemistry and Basque Center for Biophysics;
University of Basque Country (UPV/EHU), 48940, Leioa, Basque Country, Spain.
7 BIOFISIKA Institute, Spanish National Research Council (CSIC) - 
University of the Basque Country (UPV/EHU), 48940, Leioa, Basque Country, Spain.
8 IKERBASQUE, Basque Foundation for Science, 48011, Bilbao, Biscay, Spain.
* Corresponding authors. humberto.gonzalezdiaz@ehu.es 


# Abstract. 

ABSTRACT. DNA/RNA processing and editing pathways may lead to different DNA/RNA biologically relevant variants. The detection/prediction of these DNA/RNA sequence variants (variant calling problem) in modern samples by using alignment algorithms like BLAST is well documented. However, developing new algorithms for discrimination of ancient nucleic acids (aDNA/aRNA) variants in bacteria is of the major importance. These algorithms for discriminating aDNA/aRNA from other sequences may be of the major interest to preventing contamination with modern materials, which is a primary concern. However, the low number of sequences available for comparison may limit the use of alignment algorithms. Recently, Artificial Intelligence/Machine Learning (AI/ML) approaches have emerged as promising alignment-free alternatives. However, most of these methods focus on analyzing specific eukaryotic aDNA/aRNA samples such as Mammoth or Neanderthal populations, overlooking the study of aDNA/aRNA from paleo-microbiomes. In this study, we report for the first time both new experimentally benchmark data on aDNA/aRNA from bacteria and a new AI/ML algorithm for their annotation. In so doing, we introduce the PCR.PTML methodology, which combines experimental Polymerase Chain Reaction (PCR) metagenomic analysis of aDNA/aRNA sequences with Perturbation Theory (PT) and Machine Learning (ML) predictive modeling. Initially, we conducted the extraction and PCR analysis of a new set of putative microbiomes 16S aDNA sequences from Miocene fossil amber. Subsequently, we developed both linear and non-linear models using a dataset comprising 100,000 sequence combinations to identify those capable of distinguishing Miocene 16S bacterial aDNA/aRNA sequences from modern bacterial sequences. The best-performing linear algorithms achieved Sp: 78.4 and Sn: 79.2 on the training set and Sp: 78.4 and Sn: 79.2 on the validation set. Similarly, the Gradient Boosting non-linear classification algorithm produced the most favorable results for non-linear models, with Sn: 85.94 and Sp: 98.67 on the training set and Sn: 98.48 and Sp: 84.11 on the validation set. Additionally, we provide a preliminary study of aRNA sequences. The PCR.PTML method holds promise for facilitating the experimental analysis and variant calling annotation of aDNA and potentially aRNA sequences of ancient microbiomes, without relying solely on sequence alignment.

# Keywords
Ancient DNA Sequences, Perturbation Theory, Machine Learning, Shannon’s Information Theory.

# Authors Contributions

José L.R. Rama, José Manuel Ageitos, Lucía Feijoo-Siota, and Tomás G. Villa: DNA isolation, sequencing, alignment, annotation, manuscript writing and figure preparation.
Estefanía Ascencio-Medina, Amirreza Daghighi, Shan He, Gerardo Casañola Martín, Bakhtiyor Rasulev, Cristian R. Munteanu, Harbil Bediaga-Bañeres, Brenda Durán Ordiales, and Santiago Rodríguez Yáñez: Python scripting, machine learning model development, data analysis, manuscript writing, and figure preparation.Brenda Durán Ordiales, Raquel Esteban, Ana María Heres, Jorge Curiel Yuste, and Lur Epelde: Design and execution of the experimental methodology for the generation of the metagenomic data used in the SODDNA/SOHDNA model.Sonia Arrasate, Humberto González-Díaz, Tomás G. Villa, Alejandro Pazos, and Bakhtiyor Rasulev: Conceptualization of the study, supervision, manuscript writing, and funding acquisition.

# Funding
This project was funded by grants INCITE07PXI203141ES (Conselleria de Industria, Xunta de Galicia, Spain) and BFU2009-07745 (MINECO, Spain).  Likewise, the authors recognize the support of the National Science Foundation under the NSF MRI award OAC-2019077, and support by the State of North Dakota. CCAST HPC System supercomputing support at NDSU is acknowledged. In addition, the work was partly supported by Basque Government / Eusko Jaurlaritza (IT1558-22) and (IT1648-22), SPRI ELKARTEK grants AIMOFGIF (KK-2022/00032), Ministry of Science and Innovation (PID2022-137365NB-I00), and LANBIDE, INVESTIGO, Eusko Jaurlaritza, Grants, IKERDATA 2022/IKER/000040, funded by NextGenerationEU funds of European Commission,  likewise UDC Inditex Artificial Intelligence in Green Algorithms, funded by the Ministry for Digital Transformation and the Civil Service and 'NextGenerationEU'/PRTR under grant TSI-100925-2023-1 and Xunta de Galicia Consolidated group, grand ED431C 2022/46. JCY and RE are members of the Spanish climate-induced forest decline (ReDec) funded by MCIN/AEI (grant RED2024-153822-T).
