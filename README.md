# Anaerobic Hydrocarbon Degradation Genes


Anaerobic transformation of hydrocarbons by microorganisms contributes to biogeochemical cycling in anoxic ecosystems and to the bioremediation of contaminated environments.  During the past twenty-five years, a great deal has been learned about anaerobic biodegradation processes and the genetic machinery involved in the requisite biochemical pathways.  Functional genes are frequently used as biomarkers in environmental assessments of anaerobic hydrocarbon metabolism, and metagenomics techniques have vastly enhanced our ability to interrogate consortia and environmental systems for these gene markers. However, the accrued lack of manual curation of ‘omic’ datasets has led to the misannotation of these gene and protein sequences in several public databases.  _**The GitHub database herein was designed to provide a starting point for building a highly curated database of sequences associated with anaerobic hydrocarbon degradation processes. The sequences included here are for genes/proteins that are mainly involved in the anaerobic activation of hydrocarbons and that have been described for well characterized isolates or consortia**_. This database will continue to be updated to include information for additional substrates and sequences from other isolates/consortia. The long-term objective will be to include data for downstream pathway steps.  

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

Anaerobic hydroxylation has also been proposed as a putative mechanism for anaerobic alkane transformation. Initial metabolite profiling studies of _Desulfococcus oleovorans_ Hxd3 suggested that the  activation step may be direct carboxylation at C3, followed by oxidation releasing the terminal and subterminal carbons (So et al., 2003), resulting in a fatty acid that is one carbon shorter than the parent alkane. However, the requisite metabolite, 2-ethylpentadecanoic acid, was never identified in Hxd3 cultures or others that had demonstrated similar fatty acid profiles (Callaghan et al., 2006; Callaghan et al., 2009). Subsequently, a genome survey of Hxd3 revealed a protein complex related to ethylbenzene dehydrogenase (Callaghan et al., 2008b), and it has been hypothesized that this protein may be a putative alkane C-methylene hydroxylase complex (AHY), wherein anaerobic hydroxylation at C2, followed by formation of a subsequent ketone and carboxylation at C3 may occur, with oxidation to produce a fatty acid that is one carbon shorter than the parent alkane (Heider and Schühle, 2013).  Although not substantiated by metabolite analysis, substrate-dependent induction of the respective gene during growth on alkanes suggests that this mechanism may occur (Sunwoldt and Heider, unpublished data). 
 

####Alkylsuccinate Synthase (ASS) / (Methyl)alkylsuccinate Synthase (MAS)

 ASS/MAS | Description / Annotation Notes |
 :--- | :---------- |
| [Alpha subunit](fasta_files/AssA_list.md) | Glycyl radical enzyme, PFL2/glycerol dehydratase family; TIGR01774 |
| [Beta subunit](fasta_files/AssB_list.md) |  |
| [Gamma subunit](fasta_files/AssC_list.md) | BssC/TutF protein-like protein; pfam08201 |
| [MasE and MasE-like proteins](fasta_files/MasE_like_list.md) | Includes uncharacterized proteins similar to MasE |
| [Activase](fasta_files/AssD_list.md) | Radical SAM superfamily. cl18962 TIGR04003 |

####Putative Alkane C2-Methylene Hydroxylase

 AHY | Description / Annotation Notes |
 :--- | :--- |
| [Alpha subunit](fasta_files/alkane_C2_methylene_hydroxylase_alpha_list.md) | DMSO reductase family type II enzyme, molybdopterin subunit; TIGR03479 | 
| [Beta subunit](fasta_files/alkane_C2_methylene_hydroxylase_beta_list.md) | Respiratory nitrate reductase / 4Fe-4S ferredoxin iron-sulfur binding domain protein; TIGR03478 | 
| [Gamma subunit](fasta_files/alkane_C2_methylene_hydroxylase_gamma_list.md) | Heme-binding | 
| [Delta subunit](fasta_files/alkane_C2_methylene_hydroxylase_delta_list.md) | Chaperone | 

## BTEX & Related Compounds 

#### Benzene

Several mechanisms of anaerobic benzene activation have been proposed, including hydroxylation, methylation followed by toluene addition to fumarate, and carboxylation (for review see (Meckenstock and Mouttaki, 2011)). The carboxylation of benzene appears to be catalyzed by a putative benzene carboxylase (ABC). The number of subunits is still debated. To date, subunits AbcA and AbcD were detected in an anaerobic, iron-reducing, enrichment culture (Abu Laban et al., 2010), whereas only AbcA was detected in the genome of benzene-degrading archaeon, _Ferroglobus placidus_ (Holmes et al., 2011). 

![Benzene pathways](https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/images/benzene.jpg)

##### Putative Benzene Carboxylase

 ABC | Description / Annotation Notes |
 :--- | :---------- |
| [Putative benzene carboxylase](fasta_files/AbcA_list.md) | 3-Octaprenyl-4-hydroxybenzoate carboxy-lyase; cl00311 |
| [Gamma subunit](fasta_files/AbcD_list.md) | Phenylphosphate carboxylase, gamma subunit; TIGR02725 |

#### Toluene

The anaerobic activation of toluene proceeds by methyl addition to fumarate to yield benzylsuccinate (Evans et al., 1992; Biegert et al., 1996; Beller and Spormann, 1997a, b).   This reaction is catalyzed by the glycyl radical enzyme, benzylsuccinate synthase (BSS) (Leuthner et al., 1998; Beller and Spormann, 1999).  Note – In _Thauera aromatica_ T1, this enzyme is referred to as TUT (toluene-utilizing) (Coschigano et al., 1998). 

![Toluene pathway](https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/images/toluene.jpg)

#### Xylene Isomers

The isomers of xylene (o-, m-, and p-xylene) are activated under anaerobic conditions via addition of a methyl group to fumarate to yield 2-methylbenzylsuccinate, 3-methylbenzylsuccinate, and 4-methylbenzylsuccinate, respectively (Evans et al., 1992; Beller and Spormann, 1997b; Krieger et al., 1999; Verfürth et al., 2004; Morasch and Meckenstock, 2005).  To date, these reactions are catalyzed by BSS orthologs in different species (for review see (Heider et al., 2016b).  

![Xylene pathway](https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/images/xylene.jpg)

##### Benzylsuccinate Synthase

 BSS | Description / Annotation Notes |
 :--- | :---------- |
| [Alpha subunit](fasta_files/BssA_list.md) | Glycyl radical enzyme, PFL2/glycerol dehydratase family; TIGR01774 |
| [Beta subunit](fasta_files/BssB_list.md) |  |
| [Gamma subunit](fasta_files/BssC_list.md) | BssC/TutF protein; pfam08201 |
| [Activase](fasta_files/BssD_list.md) | Radical SAM superfamily. cl18962 |
| []() |  |

#### Ethylbenzene

There are two mechanisms of anaerobic activation ethylbenzene : 1) anaerobic hydroxylation via ethylbenzene dehydrogenase (EBDH), wherein water serves as the source of the hydroxyl group (for review see (Heider et al., 2016) and addition to fumarate  (Kniemeyer et al., 2003), presumably by a homolog of benzylsuccinate synthase. Of the two enzymes, EBDH is well described and has been identified and/or purified in betaproteobacterial strains EB1 (Ball et al., 1996; Johnson et al., 2001), EbN1 (Rabus and Widdel, 1995; Kniemeyer and Heider, 2001b), and PbN1 (Rabus and Widdel, 1995).  Hydroxylation of ethylbenzene yields (_S_)-1-phenylethanol, which is further oxidized to acetophenone by (_S_)-1-phenylethanol dehydrogenase (PEDH) (Kniemeyer and Heider, 2001a; Höffken et al., 2006); acetophenone is then carboxylated to benzoylacetate by acetophenone carboxylase (ACP) (Jobst et al., 2010).  

##### Ethylbenzene Dehydrogenase

 EBDH | Description / Annotation Notes |
 :--- | :--- |
| [Alpha subunit](fasta_files/EbdA_list.md) | DMSO reductase family type II enzyme, molybdopterin subunit; TIGR03479 | 
| [Beta subunit](fasta_files/EbdB_list.md) | Respiratory nitrate reductase / 4Fe-4S ferredoxin iron-sulfur binding domain protein | 
| [Gamma subunit](fasta_files/EbdC_list.md) | Heme-binding | 
| [Delta subunit](fasta_files/EbdD_list.md) | Chaperone | 

##### Phenylethanol Dehydrogenase

 PEDH | Description / Annotation Notes |
 :--- | :---------- |
| [Phenylethanol dehydrogenase](fasta_files/PhenylethanolDehydrogenase_list.md) | 3-Ketoacyl-(acyl-carrier-protein) reductase; PRK0555 |

##### Acetophenone Carboxylase

 APC | Description / Annotation Notes |
 :--- | :---------- |
| [Alpha subunit](fasta_files/ApcA_list.md) | N-Methylhydantoinase A/oxoprolinase/acetone carboxylase, beta subunit [Amino acid transport and metabolism, aecondary metabolites biosynthesis, transport and catabolism]; COG0145 |
| [Beta subunit](fasta_files/ApcB_list.md) | Acetone carboxylase gamma subunit; pfam08882 |
| [Gamma subunit](fasta_files/ApcC_list.md) | N-Methylhydantoinase A/oxoprolinase/acetone carboxylase, beta subunit [Amino acid transport and metabolism, aecondary metabolites biosynthesis, transport and catabolism]; COG0145 |
| [Delta subunit](fasta_files/ApcD_list.md) | Hydantoinase B/oxoprolinase; cl19816 |
| [Epsilon subunit](fasta_files/ApcE_list.md) | The URO-D_CIMS_like protein; cl00464 |


#### _p_-Cymene (4-Isopropyltoluene)

Anaerobic _p_-cymene degradation proceeds either by: 1) hydroxylation of the benzylic methyl group via cymene dehydrogenase (CDH) (Strijkstra et al., 2014), or 2) addition of the benzylic methyl group to fumarate (Harms et al., 1999; Strijkstra et al., 2014), which is catalyzed by (4-isopropylbenzyl)succinate synthase (IBS) (Strijkstra et al., 2014). These enzymes were identified in denitrifying organisms _'Aromatoleum’ aromaticum_ pCyN1 and _Thauera_ sp. Strain pCyN2, respectively (for review see (Rabus et al., 2016)

![_p_-Cymene pathway](https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/images/cymene.jpg)

#####_p_-Cymene Dehydrogenase

 CMD | Description / Annotation Notes |
 :--- | :---------- |
| [Alpha subunit](fasta_files/CmdA_list.md) |DMSO reductase family type II enzyme, molybdopterin subunit; TIGR03479  |
| [Beta subunit](fasta_files/CmdB_list.md) | DMSO reductase family type II enzyme, iron-sulfur subunit; TIGR03478 |
| [Gamma subunit](fasta_files/CmdC_list.md) | Domon-like ligand-binding domains; cl14783 |  
| [Chaperone assembly protein](fasta_files/CmdD_list.md) | Nitrate reductase delta subunit; cl00958 |

#####(4-Isopropylbenzyl)succinate Synthase

 IBS | Description / Annotation Notes |
 :--- | :---------- |
| [Alpha subunit](fasta_files/IbsA_list.md) | Glycyl radical enzyme, PFL2/glycerol dehydratase family; TIGR01774 |
| [Beta subunit](fasta_files/IbsB_list.md) |  |
| [Gamma subunit](fasta_files/IbsC_list.md) | BssC/TutF protein-like protein; pfam08201 |
| [Activase](fasta_files/IbsD_list.md) | Radical SAM superfamily. cl18962 TIGR04003 |
| []() |  |


## Naphthalene and other PAHs

To date, there are two, well-described mechanisms of anaerobic naphthalene activation: 1) direct carboxylation (Zhang and Young, 1997; Meckenstock et al., 2000), catalyzed by naphthalene carboxylase (DiDonato et al., 2010; Bergmann et al., 2011a; Bergmann et al., 2011b; Mouttaki et al., 2012) and 2) and methylation followed by fumarate addition (Annweiler et al., 2000; Annweiler et al., 2001, 2002; Safinowski and Meckenstock, 2004; Safinowski et al., 2006; Safinowski and Meckenstock, 2006), the latter being catalyzed by the glycyl radical enzyme, naphthyl-2-methylsuccinate synthase (NMS) (Annweiler et al., 2000; Safinowski and Meckenstock, 2004, 2006; Selesi et al., 2010).  Although most studies addressing anaerobic PAH degradation have focused on naphthalene, there is evidence that the above mechanisms may be applicable to other PAHs such as 2-methylnaphthalene (Sullivan et al., 2001; Musat et al., 2009), 1-methylnaphthalene (Safinowski et al., 2006; Musat et al., 2009), phenanthrene (Zhang and Young, 1997; Davidova et al., 2007), biphenyl (Selesi and Meckenstock, 2009), and acenaphthene (Safinowski et al., 2006; Jobelius et al., 2011; Morasch et al., 2011).

NOTE:  An initial survey of the Desulfobacterium sp. N47 revealed four putative beta subunits of naphthalene carboxylase (Locus tags: N47_K27500, N47_K27480, N47_K27460, and N47_K27390) (Bergmann et al., 2011a), three of which were found to be expressed when N47 was grown on naphthalene (N47_K27500, N47_K27480, N47_K27460) (Bergmann et al., 2011b). The latter are included in this database.  Similarly, a gene cluster homologous to that in N47 was described for Deltaproteobacterium Naph S2 (DiDonato et al., 2010).
 

![PAH pathway](https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/images/PAH.jpg)

##### 2-Napthylmethylsuccinate Synthase

 NMS | Description / Annotation Notes |
 :--- | :---------- |
| [Alpha subunit](fasta_files/NmsA_list.md) | Glycyl radical enzyme, PFL2/glycerol dehydratase family; TIGR01774 |
| []() |  |

##### Naphthalene Carboxylase

Nap Carboxylase | Description / Annotation Notes |
 :--- | :---------- |
| | |


## Hydroxylated Hydrocarbons 


#### Phenol

Anaerobic phenol degradation proceeds via activation to phenylphosphate by phenylphosphate synthase, and then carboxylation of phenylphosphate to form 4-hydroxybenzoate by phenylphosphate carboxylase (Lack et al., 1991; Lack and Fuchs, 1992, 1994; Schühle and Fuchs, 2004; Wöhlbrand et al., 2007; Schleinitz et al., 2009; Abu Laban et al., 2010). 

##### Phenylphosphate Synthase

 PPS | Description / Annotation Notes |
 :--- | :---------- |
| [Alpha subunit](fasta_files/PhenylphosphateSynthaseSubunitA.md) | PEP-utilizing enzyme, mobile domain; pfam00391 |
| [Beta subunit](fasta_files/PhenylphosphateSynthaseSubunitB.md) | Pyruvate phosphate dikinase, PEP/pyruvate binding domain; pfam01326 |

##### Phenylphosphate Carboxylase

 PPC | Description / Annotation Notes |
 :--- | :---------- |
| [Alpha subunit](fasta_files/PpcA_list.md) | Phenylphosphate carboxylase, alpha subunit; TIGR02723 |
| [Beta subunit](fasta_files/PpcB_list.md) | 3-Octaprenyl-4-hydroxybenzoate carboxy-lyase; cl00311 |
| [Gamma subunit](fasta_files/PpcC_list.md) | Haloacid dehalogenase-like hydrolase; pfam00702 |
| [Delta subunit](fasta_files/PpcD_list.md) | Phenylphosphate carboxylase, gamma subunit; TIGR02725 |

#### _p_-cresol

Anaerobic biodegradation of p-cresol proceeds via: 1) methyl addition to fumarate by hydroxybenzylsuccinate synthase (HBS) (Müller et al., 2001; Wöhlbrand et al., 2013), or 2) anaerobic hydroxylation by p-cresol methylhydroxylase (PCMH) (Keat and Hopper, 1978; Hopper et al., 1991; Peters et al., 2007).   

![_p_-Cresol pathway](https://github.com/OUGenomics/AnaerobicHydrocarbonDegradationGenes/blob/master/images/pCresol.jpg)

#####Hydroxybenzylsuccinate Synthase

 HBS | Description / Annotation Notes |
 :--- | :---------- |
| [Alpha subunit](fasta_files/HbsA_list.md) | Glycyl radical enzyme, PFL2/glycerol dehydratase family; TIGR01774 |
| [Beta subunit](fasta_files/HbsB_list.md) |  |
| [Gamma subunit](fasta_files/HbsC_list.md) | BssC/TutF protein-like protein; pfam08201 |
| [Activase](fasta_files/HbsD_list.md) | Radical SAM superfamily. cl18962 TIGR04003 |
| []() |  |

#####_p_-Cresol Methylhydroxylase

 PCMH | Description / Annotation Notes |
 :--- | :---------- |
| | |













