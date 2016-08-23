- - - 
## A Curated Database of **An**aerobic **Hy**drocarbon **Deg**radation Genes (AnHyDeg)

### _Amy V. Callaghan<sup>*</sup> and Boris Wawrik_
- - - 
**<sup>*</sup> Corresponding Author**

University of Oklahoma

Department of Microbiology and Plant Biology, 770 Van Vleet Oval, Norman OK 73019

Email: acallaghan@ou.edu
- - - 
Please cite by including the following DOI: **Zenodo.doi.XXXXXXXXX** (badge goes here; to be determined)
- - - 


Anaerobic transformation of hydrocarbons by microorganisms contributes to biogeochemical cycling in anoxic ecosystems and to the bioremediation of contaminated environments.  During the past twenty-five years, a great deal has been learned about anaerobic biodegradation processes and the genetic machinery involved in the requisite biochemical pathways.  Functional genes are frequently used as biomarkers in environmental assessments of anaerobic hydrocarbon metabolism, and metagenomic techniques have vastly enhanced our ability to interrogate consortia and environmental systems for these gene markers. However, the accrued lack of manual curation of ‘omic’ datasets has led to the misannotation of these gene and protein sequences in several public databases.  _**The GitHub database herein was designed to provide a starting point for building a highly curated database of sequences associated with anaerobic hydrocarbon degradation processes. The sequences included here are for genes/proteins that are mainly involved in the anaerobic activation of hydrocarbons and that have been described for well characterized isolates or consortia**_. This database will continue to be updated to include information for additional substrates and sequences from other isolates/consortia. The long-term objective will be to include data for downstream pathway steps.  

NOTE: The following are only brief summaries of proposed activation steps for different hydrocarbon classes. However, we  encourage the users of this GitHub entry to refer to a recent 2016 issue of the Journal of Molecular Microbiology and Biotechnology focusing on anaerobic hydrocarbon degradation [Volume 26(1-3), pages 1-244] for the complete descriptions of the requisite pathways and proteins. 


# Degradation Pathways

* [Alkanes](https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/README.md#alkanes)
* [BTEX & Related Compounds] (https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/README.md#btex--related-compounds) 
  * [Benzene] (https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/README.md#benzene)
  * [Toluene] (https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/README.md#toluene)
  * [Xylene Isomers] (https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/README.md#xylene-isomers)
  * [Ethylbenzene] (https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/README.md#ethylbenzene)
  * [_p_-Cymene] (https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/README.md#p-cymene)
* [Naphthalene and other PAHs] (https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/README.md#naphthalene-and-other-pahs)
* [Hydroxylated Hydrocarbons] (https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/README.md#hydroxylated-hydrocarbons)
  * [Phenol] (https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/README.md#phenol)
  * [_p_-Cresol] (https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/README.md#p-cresol)

##Non-Methane Linear Alkanes and Branched Alkanes

To date, there is one, well-characterized, oxygen-independent mechanism of anaerobic alkane activation, which is alkane addition to fumarate. This process has been described for a diverse range of bacteria utilizing linear and branched alkanes (for review see (Wilkes et al., 2016)).   The mechanism is catalyzed by the glycyl radical enzyme, alkylsuccinate synthase (ASS) (Callaghan et al., 2008a; Herath et al., 2016) (also known as methylalkylsuccinate synthase, MAS) (Grundmann et al., 2008; Webner, 2012). Typically, alkane addition occurs at the C2 carbon to form 2-methylalkylsuccinic acids (for review see (Callaghan, 2013)). However some studies have shown terminal (C1) (Kniemeyer et al., 2007; Jaekel et al., 2014) or C3 (Rabus et al., 2001) addition to fumarate.  Interestingly, a recent study of thermophilic strain TD3 suggests that in some systems the detection of _n_-alkylsuccinates may in fact be indicative of transformation of short-chain fatty acids via carboxylation and C-skeleton rearrangement rather than terminal addition of alkanes to fumarate (Jarling et al., 2015). 

Anaerobic hydroxylation has also been proposed as a putative mechanism for anaerobic alkane transformation. Initial metabolite profiling studies of _Desulfococcus oleovorans_ Hxd3 suggested that the  activation step may be direct carboxylation at C3, followed by oxidation releasing the terminal and subterminal carbons (So et al., 2003), resulting in a fatty acid that is one carbon shorter than the parent alkane. However, the requisite metabolite, 2-ethylpentadecanoic acid, was never identified in Hxd3 cultures or others that had demonstrated similar fatty acid profiles (Callaghan et al., 2006; Callaghan et al., 2009). Subsequently, a genome survey of Hxd3 revealed a protein complex related to ethylbenzene dehydrogenase (Callaghan et al., 2008b), and it has been hypothesized that this protein may be a putative alkane C2-methylene hydroxylase complex (AHY), wherein anaerobic hydroxylation at C2, followed by formation of a subsequent ketone and carboxylation at C3 may occur, with oxidation to produce a fatty acid that is one carbon shorter than the parent alkane (Heider and Schühle, 2013).  Although not substantiated by metabolite analysis, substrate-dependent induction of the respective gene during growth on alkanes suggests that this mechanism may occur (Sunwoldt and Heider, unpublished data). 

![Non-Methane Alkane Pathways](https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/images/non_methane_alkanes.jpg)


####Alkylsuccinate Synthase (ASS) / (Methyl)alkylsuccinate Synthase (MAS)

 ASS/MAS | GenBank Annotation Info |
 :--- | :---------- |
| [Alpha subunit](fasta_files/AssA_list.md) | Glycyl radical enzyme, PFL2/glycerol dehydratase family; TIGR01774 |
| [Beta subunit](fasta_files/AssB_list.md) |  |
| [Gamma subunit](fasta_files/AssC_list.md) | BssC/TutF protein-like protein; pfam08201 |
| [MasE and MasE-like proteins](fasta_files/MasE_like_list.md) | Includes uncharacterized proteins similar to MasE |
| [Activase](fasta_files/AssD_list.md) | Radical SAM superfamily. cl18962 TIGR04003 |

####Putative Alkane C2-Methylene Hydroxylase

 AHY | GenBank Annotation Info |
 :--- | :--- |
| [Alpha subunit](fasta_files/alkane_C2_methylene_hydroxylase_alpha_list.md) | DMSO reductase family type II enzyme, molybdopterin subunit; TIGR03479 | 
| [Beta subunit](fasta_files/alkane_C2_methylene_hydroxylase_beta_list.md) | Respiratory nitrate reductase / 4Fe-4S ferredoxin iron-sulfur binding domain protein; TIGR03478 | 
| [Gamma subunit](fasta_files/alkane_C2_methylene_hydroxylase_gamma_list.md) | Heme-binding | 
| [Delta subunit](fasta_files/alkane_C2_methylene_hydroxylase_delta_list.md) | Chaperone | 

##BTEX & Related Compounds 

###Benzene

Several mechanisms of anaerobic benzene activation have been proposed, including hydroxylation, methylation followed by toluene addition to fumarate, and carboxylation (for review see (Meckenstock and Mouttaki, 2011)). The carboxylation of benzene appears to be catalyzed by a putative benzene carboxylase (ABC). The number of subunits is still debated. To date, subunits AbcA and AbcD were detected in an anaerobic, iron-reducing, enrichment culture (Abu Laban et al., 2010), whereas only AbcA was detected in the genome of benzene-degrading archaeon, _Ferroglobus placidus_ (Holmes et al., 2011). 

![Benzene pathways](https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/images/benzene.jpg)


#####Putative Benzene Carboxylase

 ABC | GenBank Annotation Info |
 :--- | :---------- |
| [Putative benzene carboxylase](fasta_files/AbcA_list.md) | 3-Octaprenyl-4-hydroxybenzoate carboxy-lyase; cl00311 |
| [Gamma subunit](fasta_files/AbcD_list.md) | Phenylphosphate carboxylase, gamma subunit; TIGR02725 |


### Toluene

The anaerobic activation of toluene proceeds by methyl addition to fumarate to yield benzylsuccinate (Evans et al., 1992; Biegert et al., 1996; Beller and Spormann, 1997a, b).   This reaction is catalyzed by the glycyl radical enzyme, benzylsuccinate synthase (BSS) (Leuthner et al., 1998; Beller and Spormann, 1999).  Note – In _Thauera aromatica_ T1, this enzyme is referred to as TUT (toluene-utilizing) (Coschigano et al., 1998). 

![Toluene pathway](https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/images/toluene.jpg)


###Xylene Isomers

The isomers of xylene (o-, m-, and p-xylene) are activated under anaerobic conditions via addition of a methyl group to fumarate to yield 2-methylbenzylsuccinate, 3-methylbenzylsuccinate, and 4-methylbenzylsuccinate, respectively (Evans et al., 1992; Beller and Spormann, 1997b; Krieger et al., 1999; Verfürth et al., 2004; Morasch and Meckenstock, 2005).  To date, these reactions are catalyzed by BSS orthologs in different species (for review see (Heider et al., 2016b).  

![Xylene pathway](https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/images/xylene.jpg)


#####Benzylsuccinate Synthase

 BSS | GenBank Annotation Info |
 :--- | :---------- |
| [Alpha subunit](fasta_files/BssA_list.md) | Glycyl radical enzyme, PFL2/glycerol dehydratase family; TIGR01774 |
| [Beta subunit](fasta_files/BssB_list.md) |  |
| [Gamma subunit](fasta_files/BssC_list.md) | BssC/TutF protein; pfam08201 |
| [Activase](fasta_files/BssD_list.md) | Radical SAM superfamily. cl18962 |
| []() |  |


###Ethylbenzene

There are two mechanisms of anaerobic activation of ethylbenzene : 1) anaerobic hydroxylation via ethylbenzene dehydrogenase (EBDH), wherein water serves as the source of the hydroxyl group (for review see (Heider et al., 2016) and addition to fumarate  (Kniemeyer et al., 2003), presumably by a homolog of benzylsuccinate synthase. Of the two enzymes, EBDH is well described and has been identified and/or purified in betaproteobacterial strains EB1 (Ball et al., 1996; Johnson et al., 2001), EbN1 (Rabus and Widdel, 1995; Kniemeyer and Heider, 2001b), and PbN1 (Rabus and Widdel, 1995).  Hydroxylation of ethylbenzene yields (_S_)-1-phenylethanol, which is further oxidized to acetophenone by (_S_)-1-phenylethanol dehydrogenase (PEDH) (Kniemeyer and Heider, 2001a; Höffken et al., 2006); acetophenone is then carboxylated to benzoylacetate by acetophenone carboxylase (ACP) (Jobst et al., 2010).  

![Ethylbenzene pathway](https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/images/ethylbenzene.jpg)


#####Ethylbenzene Dehydrogenase

 EBDH | GenBank Annotation Info |
 :--- | :--- |
| [Alpha subunit](fasta_files/EbdA_list.md) | DMSO reductase family type II enzyme, molybdopterin subunit; TIGR03479 | 
| [Beta subunit](fasta_files/EbdB_list.md) | Respiratory nitrate reductase / 4Fe-4S ferredoxin iron-sulfur binding domain protein | 
| [Gamma subunit](fasta_files/EbdC_list.md) | Heme-binding | 
| [Delta subunit](fasta_files/EbdD_list.md) | Chaperone | 

#####Phenylethanol Dehydrogenase

 PEDH | GenBank Annotation Info |
 :--- | :---------- |
| [Phenylethanol dehydrogenase](fasta_files/PhenylethanolDehydrogenase_list.md) | 3-Ketoacyl-(acyl-carrier-protein) reductase; PRK0555 |

#####Acetophenone Carboxylase

 APC | GenBank Annotation Info |
 :--- | :---------- |
| [Alpha subunit](fasta_files/ApcA_list.md) | N-Methylhydantoinase A/oxoprolinase/acetone carboxylase, beta subunit [Amino acid transport and metabolism, aecondary metabolites biosynthesis, transport and catabolism]; COG0145 |
| [Beta subunit](fasta_files/ApcB_list.md) | Acetone carboxylase gamma subunit; pfam08882 |
| [Gamma subunit](fasta_files/ApcC_list.md) | N-Methylhydantoinase A/oxoprolinase/acetone carboxylase, beta subunit [Amino acid transport and metabolism, aecondary metabolites biosynthesis, transport and catabolism]; COG0145 |
| [Delta subunit](fasta_files/ApcD_list.md) | Hydantoinase B/oxoprolinase; cl19816 |
| [Epsilon subunit](fasta_files/ApcE_list.md) | The URO-D_CIMS_like protein; cl00464 |


###_p_-Cymene (4-Isopropyltoluene)

Anaerobic _p_-cymene degradation proceeds either by: 1) hydroxylation of the benzylic methyl group via cymene dehydrogenase (CDH) (Strijkstra et al., 2014), or 2) addition of the benzylic methyl group to fumarate (Harms et al., 1999; Strijkstra et al., 2014), which is catalyzed by (4-isopropylbenzyl)succinate synthase (IBS) (Strijkstra et al., 2014). These enzymes were identified in denitrifying organisms _'Aromatoleum’ aromaticum_ pCyN1 and _Thauera_ sp. Strain pCyN2, respectively (for review see (Rabus et al., 2016)

![_p_-Cymene pathway](https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/images/cymene.jpg)


#####_p_-Cymene Dehydrogenase

 CMD | GenBank Annotation Info |
 :--- | :---------- |
| [Alpha subunit](fasta_files/CmdA_list.md) |DMSO reductase family type II enzyme, molybdopterin subunit; TIGR03479  |
| [Beta subunit](fasta_files/CmdB_list.md) | DMSO reductase family type II enzyme, iron-sulfur subunit; TIGR03478 |
| [Gamma subunit](fasta_files/CmdC_list.md) | Domon-like ligand-binding domains; cl14783 |  
| [Chaperone assembly protein](fasta_files/CmdD_list.md) | Nitrate reductase delta subunit; cl00958 |

#####(4-Isopropylbenzyl)succinate Synthase

 IBS | GenBank Annotation Info |
 :--- | :---------- |
| [Alpha subunit](fasta_files/IbsA_list.md) | Glycyl radical enzyme, PFL2/glycerol dehydratase family; TIGR01774 |
| [Beta subunit](fasta_files/IbsB_list.md) |  |
| [Gamma subunit](fasta_files/IbsC_list.md) | BssC/TutF protein-like protein; pfam08201 |
| [Activase](fasta_files/IbsD_list.md) | Radical SAM superfamily. cl18962 TIGR04003 |
| []() |  |


##Naphthalene and other PAHs

To date, there are two, well-described mechanisms of anaerobic naphthalene activation: 1) direct carboxylation (Zhang and Young, 1997; Meckenstock et al., 2000), catalyzed by naphthalene carboxylase (DiDonato et al., 2010; Bergmann et al., 2011a; Bergmann et al., 2011b; Mouttaki et al., 2012) and 2) and methylation followed by fumarate addition (Annweiler et al., 2000; Annweiler et al., 2001, 2002; Safinowski and Meckenstock, 2004; Safinowski et al., 2006; Safinowski and Meckenstock, 2006), the latter being catalyzed by the glycyl radical enzyme, naphthyl-2-methylsuccinate synthase (NMS) (Annweiler et al., 2000; Safinowski and Meckenstock, 2004, 2006; Selesi et al., 2010).  Although most studies addressing anaerobic PAH degradation have focused on naphthalene, there is evidence that the above mechanisms may be applicable to other PAHs such as 2-methylnaphthalene (Sullivan et al., 2001; Musat et al., 2009), 1-methylnaphthalene (Safinowski et al., 2006; Musat et al., 2009), phenanthrene (Zhang and Young, 1997; Davidova et al., 2007), biphenyl (Selesi and Meckenstock, 2009), and acenaphthene (Safinowski et al., 2006; Jobelius et al., 2011; Morasch et al., 2011).

NOTE:  An initial survey of the Desulfobacterium sp. N47 revealed four putative beta subunits of naphthalene carboxylase (Locus tags: N47_K27500, N47_K27480, N47_K27460, and N47_K27390) (Bergmann et al., 2011a), three of which were found to be expressed when N47 was grown on naphthalene (N47_K27500, N47_K27480, N47_K27460) (Bergmann et al., 2011b). The latter are included in this database.  Similarly, a gene cluster homologous to that in N47 was described for Deltaproteobacterium Naph S2 (DiDonato et al., 2010).
 

![PAH pathway](https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/images/PAH.jpg)


#####2-Napthylmethylsuccinate Synthase

 NMS | GenBank Annotation Info |
 :--- | :---------- |
| [Alpha subunit](fasta_files/NmsA_list.md) | Glycyl radical enzyme, PFL2/glycerol dehydratase family; TIGR01774 |
| [Beta subunit](fasta_files/NmsB_list.md) | |
| [Gamma subunit](fasta_files/NmsC_list.md) | BssC/TutF protein; pfam08201 |
| [Activase](fasta_files/NmsD_list.md) | Radical SAM superfamily; 4Fe-4S dicluster domain; pfam13183|
| []() |  |

#####Naphthalene Carboxylase

Nap Carboxylase | GenBank Annotation Info |
 :--- | :---------- |
| [Alpha subunit](fasta_files/Nap_Carboxylase_alpha_list.md) | match to protein family HMM PF01977; match to protein family HMM TIGR00148 |
| [Beta subunit](fasta_files/Nap_Carboxylase_beta_list.md) | hypothetical protein; match to protein family HMM PF01977 |
| | |


##Hydroxylated Hydrocarbons 


###Phenol

Anaerobic phenol degradation proceeds via activation to phenylphosphate by phenylphosphate synthase, and then carboxylation of phenylphosphate to form 4-hydroxybenzoate by phenylphosphate carboxylase (Lack et al., 1991; Lack and Fuchs, 1992, 1994; Schühle and Fuchs, 2004; Wöhlbrand et al., 2007; Schleinitz et al., 2009; Abu Laban et al., 2010). 

![Phenol Pathway](https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/images/phenol.jpg)


#####Phenylphosphate Synthase

 PPS | GenBank Annotation Info |
 :--- | :---------- |
| [Alpha subunit](fasta_files/PhenylphosphateSynthaseSubunitA.md) | PEP-utilizing enzyme, mobile domain; pfam00391 |
| [Beta subunit](fasta_files/PhenylphosphateSynthaseSubunitB.md) | Pyruvate phosphate dikinase, PEP/pyruvate binding domain; pfam01326 |

#####Phenylphosphate Carboxylase

 PPC | GenBank Annotation Info |
 :--- | :---------- |
| [Alpha subunit](fasta_files/PpcA_list.md) | Phenylphosphate carboxylase, alpha subunit; TIGR02723 |
| [Beta subunit](fasta_files/PpcB_list.md) | 3-Octaprenyl-4-hydroxybenzoate carboxy-lyase; cl00311 |
| [Gamma subunit](fasta_files/PpcC_list.md) | Haloacid dehalogenase-like hydrolase; pfam00702 |
| [Delta subunit](fasta_files/PpcD_list.md) | Phenylphosphate carboxylase, gamma subunit; TIGR02725 |


###_p_-Cresol

Anaerobic biodegradation of p-cresol proceeds via: 1) methyl addition to fumarate by hydroxybenzylsuccinate synthase (HBS) (Müller et al., 2001; Wöhlbrand et al., 2013), or 2) anaerobic hydroxylation by _p_-cresol methylhydroxylase (PCMH) (Keat and Hopper, 1978; Hopper et al., 1991; Peters et al., 2007).   

![_p_-Cresol pathway](https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/images/pCresol.jpg)


#####Hydroxybenzylsuccinate Synthase

 HBS | GenBank Annotation Info |
 :--- | :---------- |
| [Alpha subunit](fasta_files/HbsA_list.md) | Glycyl radical enzyme, PFL2/glycerol dehydratase family; TIGR01774 |
| [Beta subunit](fasta_files/HbsB_list.md) |  |
| [Gamma subunit](fasta_files/HbsC_list.md) | BssC/TutF protein-like protein; pfam08201 |
| [Activase](fasta_files/HbsD_list.md) | Radical SAM superfamily. cl18962 TIGR04003 |
| []() |  |

#####_p_-Cresol Methylhydroxylase

 PCMH | GenBank Annotation Info |
 :--- | :---------- |
| [PcmI/J Alpha subunit isoforms](fasta_files/PcmIJ_list.md) | FAD linked oxidases, C-terminal domain; pfam02913; COG0277 |
| [PcmG cytochrome C Beta Subunit](fasta_files/PcmG_list.md) | Cytochrome c, mono- and diheme variants; COG2010; pfam13442 |
| | |


- - - 
##References

[Abu Laban N, Selesi D, Rattei T, Tischler P & Meckenstock RU (2010) Identification of enzymes involved in anaerobic benzene degradation by a strictly anaerobic iron-reducing enrichment culture. Environ Microbiol 12: 2783-2796.](http://onlinelibrary.wiley.com/doi/10.1111/j.1462-2920.2010.02248.x/epdf)

[Annweiler E, Michaelis W & Meckenstock RU (2001) Anaerobic cometabolic conversion of benzothiophene by a sulfate-reducing enrichment culture and in a tar-oil- contaminated aquifer. Appl Environ Microbiol 67: 5077-5083.] (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC93274/pdf/am1101005077.pdf.)

[Annweiler E, Michaelis W & Meckenstock RU (2002) Identical ring cleavage products during anaerobic degradation of naphthalene, 2-methylnaphthalene, and tetralin indicate a new metabolic pathway. Appl Environ Microbiol 68: 852-858.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC126706/pdf/1266.pdf)

[Annweiler E, Materna A, Safinowski M, Kappler A, Richnow HH, Michaelis W & Meckenstock RU (2000) Anaerobic degradation of 2-methylnaphthalene by a sulfate-reducing enrichment culture. Appl Environ Microbiol 66: 5329-5333.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC92464/pdf/am005329.pdf)

[Ball HA, Johnson HA, Reinhard M & Spormann AM (1996) Initial reactions in anaerobic ethylbenzene oxidation by a denitrifying bacterium, strain EB1. J Bacteriol 178: 5755-5761.](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC178416/pdf/1785755.pdf)

[Beller HR & Spormann AM (1997) Benzylsuccinate formation as a means of anaerobic toluene activation by sulfate-reducing strain PRTOL1. Appl Environ Microbiol 63: 3729-3731.](http://aem.asm.org/content/63/9/3729.full.pdf)

[Beller HR & Spormann AM (1997) Anaerobic activation of toluene and _o_-xylene by addition to fumarate in denitrifying strain T. J Bacteriol 179: 670-676.](http://jb.asm.org/content/179/3/670.full.pdf)

[Beller HR & Spormann AM (1999) Substrate range of benzylsuccinate synthase from _Azoarcus_ sp. strain T. FEMS Microbiol Lett 178: 147-153.](http://femsle.oxfordjournals.org/content/femsle/178/1/147.full.pdf)

[Bergmann F, Selesi D, Weinmaier T, Tischler P, Rattei T & Meckenstock RU (2011) Genomic insights into the metabolic potential of the polycyclic aromatic hydrocarbon degrading sulfate-reducing Deltaproteobacterium N47. Environ Microbiol 13: 1125-1137.](http://www.ncbi.nlm.nih.gov/pubmed/21176053)

[Bergmann FD, Selesi D & Meckenstock RU (2011) Identification of new enzymes potentially involved in anaerobic naphthalene degradation by the sulfate-reducing enrichment culture N47. Arch Microbiol 193: 241-250](http://download.springer.com/static/pdf/877/art%253A10.1007%252Fs00203-010-0667-4.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Farticle%2F10.1007%2Fs00203-010-0667-4&token2=exp=1471976388~acl=%2Fstatic%2Fpdf%2F877%2Fart%25253A10.1007%25252Fs00203-010-0667-4.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Farticle%252F10.1007%252Fs00203-010-0667-4*~hmac=9c61b454cfecfb516b8c89400440ac1a451a0a86d03d14986fefee97f7750304)

[Biegert T, Fuchs G & Heider F (1996) Evidence that anaerobic oxidation of toluene in the denitrifying bacterium _Thauera aromatica_ is initiated by formation of benzylsuccinate from toluene and fumarate. Eur J Biochem 238: 661-668.](http://onlinelibrary.wiley.com/doi/10.1111/j.1432-1033.1996.0661w.x/epdf)

[Callaghan AV (2013) Enzymes involved in the anaerobic oxidation of _n_-alkanes: from methane to long-chain paraffins. Front Microbiol 4.](http://journal.frontiersin.org/article/10.3389/fmicb.2013.00089/full)

[Callaghan AV, Tierney M, Phelps CD & Young LY (2009) Anaerobic biodegradation of _n_-hexadecane by a nitrate-reducing consortium. Appl Environ Microbiol 75: 1339-1344.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2648152/pdf/2491-08.pdf)

[Callaghan AV, Gieg LM, Kropp KG, Suflita JM & Young LY (2006) Comparison of mechanisms of alkane metabolism under sulfate-reducing conditions among two bacterial isolates and a bacterial consortium. Appl Environ Microbiol 72: 4274-4282.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1489600/pdf/2896-05.pdf)

[Callaghan AV, Wawrik B, Ní Chadhain SM, Young LY & Zylstra GJ (2008) Anaerobic alkane-degrading strain AK-01 contains two alkylsuccinate synthase genes. Biochem Bioph Res Comm 366: 142-148.](http://ac.els-cdn.com/S0006291X07025259/1-s2.0-S0006291X07025259-main.pdf?_tid=67703d7a-695b-11e6-9f45-00000aacb360&acdnat=1471975378_b11acbf88b218b368c82f78ac9431fd7)

Callaghan, A.V., Austin, R.N., Groves, J.T., Kukor, J.J., Rabus, R., Widdel, F. et al. (2008) The Complete Genome Sequence of _Desulfococcus oleovorans_ Hxd3, a Sulfate-Reducing, Alkane-Degrading Bacterium. In American Society for Microbiology 108th General Meeting. Boston, MA.

[Coschigano PW, Wehrman TS & Young LY (1998) Identification and analysis of genes involved in anaerobic toluene metabolism by strain T1: putative role of a glycine free radical. Appl Environ Microbiol 64:1650-1656.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC106210/pdf/am001650.pdf)

[Davidova IA, Gieg LM, Duncan KE & Suflita JM (2007) Anaerobic phenanthrene mineralization by a carboxylating sulfate-reducing bacterial enrichment. ISME J 1: 436-442.](http://www.nature.com/ismej/journal/v1/n5/pdf/ismej200748a.pdf)

[DiDonato RJ, Young ND, Butler JE, Chin KJ, Hixson KK, Mouser P, Lipton MS, DeBoy R & Methe BA (2010) Genome sequence of the deltaproteobacterial strain NaphS2 and analysis of differential gene expression during anaerobic growth on naphthalene. PLoS One 5:11.](http://journals.plos.org/plosone/article/asset?id=10.1371/journal.pone.0014072.PDF)

[Evans PJ, Ling W, Goldschmidt B, Ritter ER & Young LY (1992) Metabolites formed during anaerobic transformation of toluene and _o_-xylene and their proposed relationship to the initial steps of toluene mneralization. Appl Environ Microbiol 58: 496-501.](http://aem.asm.org/content/58/2/496.full.pdf)

[Grundmann O, Behrends A, Rabus R, Amann J, Halder T, Heider J & Widdel F (2008) Genes encoding the candidate enzyme for anaerobic activation of _n_-alkanes in the denitrifying bacterium, strain HxN1. Environ Microbiol 10: 376-385.](http://onlinelibrary.wiley.com/doi/10.1111/j.1462-2920.2007.01458.x/epdf)

[Harms G, Rabus R & Widdel F (1999) Anaerobic oxidation of the aromatic plant hydrocarbon _p_-cymene by newly isolated denitrifying bacteria. Arch Microbiol 172:303-312.](http://download.springer.com/static/pdf/276/art%253A10.1007%252Fs002030050784.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Farticle%2F10.1007%2Fs002030050784&token2=exp=1471983534~acl=%2Fstatic%2Fpdf%2F276%2Fart%25253A10.1007%25252Fs002030050784.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Farticle%252F10.1007%252Fs002030050784*~hmac=bb9ef45a9e05ee2dc8a7485dca620b04ef30e5ce18d67d2f26ae22af4fb8b52f)

[Heider J & Schühle K (2013) Anaerobic Biodegradation of Hydrocarbons Including Methane. In _The Prokaryotes_, (Rosenberg E, DeLong EF, Lory S, Stackebrandt E & Thompson F, eds)  605-634. Springer-Verlag, Berlin Heidelberg.](http://download.springer.com/static/pdf/102/chp%253A10.1007%252F978-3-642-30141-4_80.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Freferenceworkentry%2F10.1007%2F978-3-642-30141-4_80&token2=exp=1471983445~acl=%2Fstatic%2Fpdf%2F102%2Fchp%25253A10.1007%25252F978-3-642-30141-4_80.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Freferenceworkentry%252F10.1007%252F978-3-642-30141-4_80*~hmac=e4dc42225aea1df370a70f6077dde2724470a761afca8f416029f7b5087789fb)

[Heider J, Szaleniec M, Sünwoldt K & Boll M (2016) Ethylbenzene dehydrogenase and related molybdenum enzymes involved in oxygen-independent alkyl chain hydroxylation. J Mol Microbiol Biotechnol 26: 45-62.](http://www.karger.com/Article/Abstract/441357)

[Heider J, Szaleniec M, Martins BM, Seyhan D, Buckel W & Golding BT (2016) Structure and function of benzylsuccinate synthase and related fumarate-adding glycyl radical enzymes. J Mol Microbiol Biotechnol 26: 29-44.](http://www.karger.com/Article/Abstract/441656)

[Herath A, Wawrik B, Qin Y, Zhou JZ & Callaghan AV (2016) Transcriptional response of _Desulfatibacillum alkenivorans_ AK-01 to growth on alkanes: insights from RT-qPCR and microarray analyses. FEMS Microbiol Ecol 92(5):fiw062.](http://femsec.oxfordjournals.org/content/femsec/92/5/fiw062.full.pdf)

[Höffken HW, Duong M, Friedrich T, Breuer M, Hauer B, Reinhardt R, Rabus R & Heider J (2006) Crystal structure and enzyme kinetics of the (_S_)-specific 1-phenylethanol dehydrogenase of the denitrifying bacterium strain EbN1. Biochemistry-Us 45: 82-93.](http://pubs.acs.org/doi/pdfplus/10.1021/bi051596b)

[Holmes DE, Risso C, Smith JA & Lovley DR (2011) Anaerobic oxidation of benzene by the hyperthermophilic archaeon _Ferroglobus placidus_. Appl Environ Microbiol 77: 5926-5933.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3165377/pdf/zam5926.pdf)

[Hopper DJ, Bossert ID & Rhodes-Roberts ME (1991) _p_-Cresol methylhydroxylase from a denitrifying bacterium involved in anaerobic degradation of _p_-cresol. J Bacteriol 173: 1298-1301.](http://jb.asm.org/content/173/3/1298.full.pdf)

[Jaekel U, Vogt C, Fischer A, Richnow HH & Musat F (2014) Carbon and hydrogen stable isotope fractionation associated with the anaerobic degradation of propane and butane by marine sulfate-reducing bacteria. Environ Microbiol 16: 130-140.](http://onlinelibrary.wiley.com/doi/10.1111/1462-2920.12251/epdf)

[Jarling R, Kühner S, Basílio Janke E, Gruner A, Drozdowska M, Golding BT, Rabus R & Wilkes H (2015) Versatile transformations of hydrocarbons in anaerobic bacteria: substrate ranges and regio- and stereo-chemistry of activation reactions. Front Microbiol 6:](http://journal.frontiersin.org/article/10.3389/fmicb.2015.00880/full)

[Jobelius C, Ruth B, Griebler C, Meckenstock RU, Hollender J, Reineke A, Frimmel FH & Zwiener C (2011) Metabolites indicate hot spots of biodegradation and biogeochemical gradients in a high-resolution monitoring well. Environ Sci Technol 45: 474-481.](http://pubs.acs.org/doi/pdfplus/10.1021/es1030867)

[Jobst B, Schühle K, Linne U & Heider J (2010) ATP-dependent carboxylation of acetophenone by a novel type of carboxylase. J Bacteriol 192: 1387-1394.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2820866/pdf/1423-09.pdf)

[Johnson HA, Pelletier DA & Spormann AM (2001) Isolation and characterization of anaerobic ethylbenzene dehydrogenase, a novel Mo-Fe-S enzyme. J Bacteriol 183: 4536-4542.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC95348/pdf/jb004536.pdf)

[Keat MJ & Hopper DJ (1978) _p_-Cresol and 3,5-xylenol methylhydroxylases in _Pseudomonas putida_ NCIB 9869. Biochem J 175: 649-658.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1186115/pdf/biochemj00476-0296.pdf)

[Kniemeyer O & Heider J (2001) (_S_)-1-Phenylethanol dehydrogenase of _Azoarcus_ sp strain EbN1, an enzyme of anaerobic ethylbenzene catabolism. Arch Microbiol 176: 129-135.](http://download.springer.com/static/pdf/729/art%253A10.1007%252Fs002030100303.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Farticle%2F10.1007%2Fs002030100303&token2=exp=1471984280~acl=%2Fstatic%2Fpdf%2F729%2Fart%25253A10.1007%25252Fs002030100303.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Farticle%252F10.1007%252Fs002030100303*~hmac=b8aba15e0f8a938fdc88c88e54821c4e5fd36ddcc117eeeb55095319b9223f95)

[Kniemeyer O & Heider J (2001) Ethylbenzene dehydrogenase, a novel hydrocarbon-oxidizing molybdenum/iron-sulfur/heme enzyme. J Biol Chem 276: 21381-21386.](http://www.jbc.org/content/276/24/21381.full.pdf)

[Kniemeyer O, Fischer T, Wilkes H, Glöckner FO & Widdel F (2003) Anaerobic degradation of ethylbenzene by a new type of marine sulfate-reducing bacterium. Appl Environ Microbiol 69: 760-768.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC143655/pdf/1380.pdf)

[Kniemeyer O, Musat F, Sievert SM, Knittel K, Wilkes H, Blumenberg M, Michaelis W, Classen A, Bolm C, Joye SB & Widdel F (2007) Anaerobic oxidation of short-chain hydrocarbons by marine sulphate-reducing bacteria. Nature 449: 898-U810.](http://www.nature.com/nature/journal/v449/n7164/pdf/nature06200.pdf)

[Krieger CJ, Beller HR, Reinhard M & Spormann AM (1999) Initial reactions in anaerobic oxidation of _m_-xylene by the denitrifying bacterium _Azoarcus_ sp. strain T. J Bacteriol 181: 6403-6410.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC103776/pdf/jb006403.pdf)

[Lack A & Fuchs G (1992) Carboxylation of phenylphosphate by phenol carboxylase, an enzyme system of anaerobic phenol metabolism. J Bacteriol 174: 3629-3636.](http://jb.asm.org/content/174/11/3629.full.pdf)

[Lack A & Fuchs G (1994) Evidence that phenol phosphorylation to phenylphosphate is the first step in anaerobic phenol metabolism in a denitrifying _Pseudomonas_ sp. Arch Microbiol 161: 132-139.](http://download.springer.com/static/pdf/959/art%253A10.1007%252FBF00276473.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Farticle%2F10.1007%2FBF00276473&token2=exp=1471985091~acl=%2Fstatic%2Fpdf%2F959%2Fart%25253A10.1007%25252FBF00276473.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Farticle%252F10.1007%252FBF00276473*~hmac=43bec0aa098d908e33558b4054adb9f931dc0191d1b7eb631459f1efbd896d22)

[Lack A, Tommasi I, Aresta M & Fuchs G (1991) Catalytic properties of phenol carboxylase - _In vitro_ study of CO<sub>2</sub>: 4-hydroxybenzoate isotope exchange reaction. Eur J Biochem 197: 473-479.](http://onlinelibrary.wiley.com/doi/10.1111/j.1432-1033.1991.tb15934.x/epdf)

[Leuthner B, Leutwein C, Schulz H, Horth P, Haehnel W, Schiltz E, Schägger H & Heider J (1998) Biochemical and genetic characterization of benzylsuccinate synthase from _Thauera aromatica_: a new glycyl radical enzyme catalysing the first step in anaerobic toluene metabolism. Mol Microbiol 28: 615-628.](http://onlinelibrary.wiley.com/store/10.1046/j.1365-2958.1998.00826.x/asset/j.1365-2958.1998.00826.x.pdf?v=1&t=is7s29on&s=bf501450d1b64bbc59d1482acd603a37cbbae6d2)

[Meckenstock RU & Mouttaki H (2011) Anaerobic degradation of non-substituted aromatic hydrocarbons. Curr Opin Biotechnol 22: 406-414.](http://ac.els-cdn.com/S095816691100036X/1-s2.0-S095816691100036X-main.pdf?_tid=8a5fa2ee-695b-11e6-b333-00000aacb360&acdnat=1471975436_a900450afddd6f58981328bd8691df4b)

[Meckenstock RU, Annweiler E, Michaelis W, Richnow HH & Schink B (2000) Anaerobic naphthalene degradation by a sulfate-reducing enrichment culture. Appl Environ Microbiol 66: 2743-2747.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC92068/pdf/am002743.pdf)

[Morasch B & Meckenstock RU (2005) Anaerobic degradation of _p_-xylene by a sulfate-reducing enrichment culture. Curr Microbiol 51: 127-130.](http://download.springer.com/static/pdf/993/art%253A10.1007%252Fs00284-005-4518-5.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Farticle%2F10.1007%2Fs00284-005-4518-5&token2=exp=1471976460~acl=%2Fstatic%2Fpdf%2F993%2Fart%25253A10.1007%25252Fs00284-005-4518-5.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Farticle%252F10.1007%252Fs00284-005-4518-5*~hmac=f71813abaf11cfbe2212fb5a19cd195c239a3f3a5f0bc574159530cf57036282)

[Morasch B, Hunkeler D, Zopfi J, Temime B & Höhener P (2011) Intrinsic biodegradation potential of aromatic hydrocarbons in an alluvial aquifer - potentials and limits of signature metabolite analysis and two stable isotope-based techniques. Water Res 45: 4459-4469.](http://ac.els-cdn.com/S0043135411003137/1-s2.0-S0043135411003137-main.pdf?_tid=8cf51de0-695b-11e6-8665-00000aab0f27&acdnat=1471975441_204ba3759061fbc9746683c7a361a4ef)

[Mouttaki H, Johannes J & Meckenstock RU (2012) Identification of naphthalene carboxylase as a prototype for the anaerobic activation of non-substituted aromatic hydrocarbons. Environ Microbiol 14: 2770-2774.](http://onlinelibrary.wiley.com/store/10.1111/j.1462-2920.2012.02768.x/asset/emi2768.pdf?v=1&t=is7s2dtd&s=143131d9e65322bd98aec0fe70aacedf0c5aeb23)

[Müller JA, Galushko AS, Kappler A & Schink B (2001) Initiation of anaerobic degradation of _p_-cresol by formation of 4-hydroxybenzylsuccinate in _Desulfobacterium cetonicum_. J Bacteriol 183: 752-757.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC94933/pdf/jb000752.pdf)

[Musat F, Galushko A, Jacob J, Widdel F, Kube M, Reinhardt R, Wilkes H, Schink B & Rabus R (2009) Anaerobic degradation of naphthalene and 2-methylnaphthalene by strains of marine sulfate-reducing bacteria. Environ Microbiol 11: 209-219.](http://onlinelibrary.wiley.com/store/10.1111/j.1462-2920.2008.01756.x/asset/j.1462-2920.2008.01756.x.pdf?v=1&t=is7s2hi1&s=434467648147518db102e70a4414069f1afffd2d)

[Peters F, Heintz D, Johannes J, van Dorsselaer A & Boll M (2007) Genes, enzymes, and regulation of _p_-cresol metabolism in _Geobacter metallireducens_. J Bacteriol 189: 4729-4738.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1913446/pdf/0260-07.pdf)

[Rabus R & Widdel F (1995) Anaerobic degradation of ethylbenzene and other aromatic hydrocarbons by new denitrifying bacteria. Arch Microbiol 163: 96-103.](http://download.springer.com/static/pdf/329/art%253A10.1007%252FBF00381782.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Farticle%2F10.1007%2FBF00381782&token2=exp=1471976468~acl=%2Fstatic%2Fpdf%2F329%2Fart%25253A10.1007%25252FBF00381782.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Farticle%252F10.1007%252FBF00381782*~hmac=eb79356ca4bfcdb79ba2aa1bee2a05fd1d45bef588c6e62a5b3c158e7a14f895)

[Rabus R, Boll M, Golding B & Wilkes H (2016) Anaerobic degradation of _p_-alkylated benzoates and toluenes. J Mol Microbiol Biotechnol 26: 63-75.](http://www.karger.com/Article/Abstract/441144)

[Rabus R, Wilkes H, Behrends A, Armstroff A, Fischer T, Pierik AJ & Widdel F (2001) Anaerobic initial reaction of _n_-alkanes in a denitrifying bacterium: evidence for (1-methylpentyl)succinate as initial product and for involvement of an organic radical in _n_-hexane metabolism. J Bacteriol 183: 1707-1715.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC95056/pdf/jb001707.pdf)

[Safinowski M & Meckenstock RU (2004) Enzymatic reactions in anaerobic 2-methylnaphthalene degradation by the sulphate-reducing enrichment culture N47. FEMS Microbiol Lett 240: 99-104.](http://femsle.oxfordjournals.org/content/femsle/240/1/99.full.pdf)

[Safinowski M & Meckenstock RU (2006) Methylation is the initial reaction in anaerobic naphthalene degradation by a sulfate-reducing enrichment culture. Environ Microbiol 8: 347-352.](http://onlinelibrary.wiley.com/store/10.1111/j.1462-2920.2005.00900.x/asset/j.1462-2920.2005.00900.x.pdf?v=1&t=is7s3oie&s=1585552f8a34e8e49626b792d2c5bd298c536ff5)

[Safinowski M, Griebler C & Meckenstock RU (2006) Anaerobic cometabolic transformation of polycyclic and heterocyclic aromatic hydrocarbons: Evidence from laboratory and field studies. Environ Sci Technol 40: 4165-4173.](http://pubs.acs.org/doi/pdf/10.1021/es0525410)

[Schleinitz KM, Schmeling S, Jehmlich N, von Bergen M, Harms H, Kleinsteuber S, Vogt C & Fuchs G (2009) Phenol degradation in the strictly anaerobic iron-reducing bacterium _Geobacter metallireducens_ GS-15. Appl Environ Microbiol 75: 3912-3919.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2698347/pdf/1525-08.pdf)

[Schühle K & Fuchs G (2004) Phenylphosphate carboxylase: a new C-C lyase involved in anaerobic in phenol metabolism in _Thauera aromatica_. J Bacteriol 186: 4556-4567.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC438602/pdf/0273-04.pdf)

[Selesi D & Meckenstock RU (2009) Anaerobic degradation of the aromatic hydrocarbon biphenyl by a sulfate-reducing enrichment culture. FEMS Microbiol Ecol 68: 86-93.](http://femsec.oxfordjournals.org/content/femsec/68/1/86.full.pdf)

[Selesi D, Jehmlich N, von Bergen M, Schmidt F, Rattei T, Tischler P, Lueders T & Meckenstock RU (2010) Combined genomic and proteomic approaches identify gene clusters involved in anaerobic 2-methylnaphthalene degradation in the sulfate-reducing enrichment culture N47. J Bacteriol 192: 295-306.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2798259/pdf/0874-09.pdf)

[So CM, Phelps CD & Young LY (2003) Anaerobic transformation of alkanes to fatty acids by a sulfate-reducing bacterium, strain Hxd3. Appl Environ Microbiol 69: 3892-3900.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC165127/pdf/0048.pdf)

[Strijkstra A, Trautwein K, Jarling R, Wöhlbrand L, Dorries M, Reinhardt R, Drozdowska M, Golding BT, Wilkes H & Rabus R (2014) Anaerobic activation of _p_-cymene in denitrifying Betaproteobacteria: methyl group hydroxylation versus addition to fumarate. Appl Environ Microbiol 80: 7592-7603.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4249252/pdf/zam7592.pdf)

[Sullivan ER, Zhang XM, Phelps C & Young LY (2001) Anaerobic mineralization of stable-isotope-labeled 2-methylnaphthalene. Appl Environ Microbiol 67: 4353-4357.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC93170/pdf/am004353.pdf)

[Verfürth K, Pierik AJ, Leutwein C, Zorn S & Heider J (2004) Substrate specificities and electron paramagnetic resonance properties of benzylsuccinate synthases in anaerobic toluene and m-xylene metabolism. Arch Microbiol 181: 155-162.](http://download.springer.com/static/pdf/382/art%253A10.1007%252Fs00203-003-0642-4.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Farticle%2F10.1007%2Fs00203-003-0642-4&token2=exp=1471976506~acl=%2Fstatic%2Fpdf%2F382%2Fart%25253A10.1007%25252Fs00203-003-0642-4.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Farticle%252F10.1007%252Fs00203-003-0642-4*~hmac=e2aa3ff69bf544b0fc0ccf45a9e13142c4e821a7584bb015efb675cda993545f)

[Webner K (2012) Die Gene der (1-Methylalkyl)succinat-Synthase im anaeroben _n_-Alkanabbau des Betaproteobakteriums Stamm HxN1. Thesis, University of Bremen, Bremen, Germany.](http://elib.suub.uni-bremen.de/edocs/00102600-1.pdf)

[Wilkes H, Buckel W, Golding BT & Rabus R (2016) Metabolism of hydrocarbons in n-alkane-utilizing anaerobic bacteria. J Mol Microb Biotech 26: 138-151.](http://www.karger.com/Article/Abstract/442160)

[Wöhlbrand L, Kallerhoff B, Lange D, Hufnagel P, Thiermann J, Reinhardt R & Rabus R (2007) Functional proteomic view of metabolic regulation in _"Aromatoleum aromaticum"_ strain EbN1. Proteomics 7: 2222-2239.](http://onlinelibrary.wiley.com/store/10.1002/pmic.200600987/asset/2222_ftp.pdf?v=1&t=is7s3jo4&s=713b0b05d85289b691e8678308ce46a32aaaf975)

[Wöhlbrand L, Jacob JH, Kube M, Mussmann M, Jarling R, Beck A, Amann R, Wilkes H, Reinhardt R & Rabus R (2013) Complete genome, catabolic sub-proteomes and key metabolites of _Desulfobacula toluolica_ Tol2, a marine, aromatic compound-degrading, sulfate-reducing bacterium. Environ Microbiol 15: 1334-1355.](http://onlinelibrary.wiley.com/store/10.1111/j.1462-2920.2012.02885.x/asset/emi2885.pdf?v=1&t=is7s3f1r&s=898dabfce1e30c6b273f3e293ff343375500d2af)

[Zhang XM & Young LY (1997) Carboxylation as an initial reaction in the anaerobic metabolism of naphthalene and phenanthrene by sulfidogenic consortia. Appl Environ Microbiol 63: 4759-4764.](http://aem.asm.org/content/63/12/4759.full.pdf)

- - -
