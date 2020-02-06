## CRISPR-CAS9 construct construction.

### Primer-dimer synthesis

Mix : 	
  - 1μl 	primer1 (100mM)
  - 1  μl	primer2 (100mM)
  - 98 μl	TE  (10mM TRIS(pH 8.0), 1mM EDTA)

In 1 l beaker containing ±200ml water.
Boil 30 sec and cool to air in about an hour.

### Restriction/ligation reaction:
Mix:	
  - 1 μl	primer-dimer
  - 1-2 μl	V308_AtU3b (target 1) or V307_AtU6-1(target 2) (±100 ng)
  - 10 U	Bsa1
  - 10 U	T4 DNA-ligase(HC)
  - 2 μl	ligation buffer(10* concentrated)
  - ±14 μl	H2O (final volume of 20μl)

Incubated in a thermocycler for 5 hours at 37°C, 5 min at 50°C and 10 min at 80°C.


### PCR amplification U6/U3 promoter sgRNA fragment:

#### Target1
Mix:	
  - 1 μl	Restriction/ligation reaction
  - 2.5 μl	primer FW(8410_Uctcg-B1’) 10mM
  - 2.5 μl	primer REV(8411_gRctga-B2)  10mM
#### Target2
Mix:	
  - 1 μl	Restriction/ligation reaction
  - 2.5μl	primer FW(8412_Uctga-B2’) 10mM
  - 2.5μl	primer REV(8413_gRcggt-BL)  10mM

Should give a pcr-product of approximately 500 bp in length.


### Restriction/ligation reaction:
Mix:	
  - 1 μl	pcr product of target
  - 1 μl	pcr product of target 2
  - 1-2 μl	V304(kan) or V305(hyg) or V306(basta)
  - 10 U	Bsa1
  - 10 U	T4 DNA-ligase(HC)
  - 2 μl	ligation buffer(10* concentrated)
  - ±13μl	H2O (final volume of 20μl)

Transform to E.coli., Check positive colonies with pcr. (8765_PYL-CAS9-sgRNA-seq-FW + 8411_gRctga-B2)
	PCR should again be approximately 500 bp

Isolate positive plasmid and sequence to be sure it’s all right.

Good luck!
