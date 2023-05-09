# EnzymeStability

In this repository there are all files associated to our manuscript "Enzyme stability-activity trade-off: new insights from protein stability weaknesses and evolutionary conservation". Here their list:

• ListPDB551.dat: List of PDB codes corresponding to all 551 enzymes included in the DCSA dataset.

• ListCatalyticsites.dat: List of all catalytic sites for the 551 enzymes in the DCSA dataset (from Catalytic Site Atlas). 

• PDBNEW: Folder containing all the PDB structures of the enzymes included in the DCSA dataset.

• EnzymeStability.zip: File containing the plots for each enzyme in our dataset of the per-site folding free energy contribution ∆Gi (in kcal/mol) of residue i as a function of its distance d_i (in Ångström) from the closest catalytic residue, averaged over bins of 1.5 Ångström. 

• EnzymeValues.zip: File contining all data used to create the plots in our manuscript. For all enzymes in DCSA dataset the following information for each residue are provided : 

ChainID-ResidueNumber-ResidueType, Solvent accessibility, DG_i(tor), DG_i(dis), DG_i(acc), Consurf_i, ClassConsurf_i, d_i 

where DG_i are the per-site folding free energy or residue i, Consurf_i and ClassConsurf_i are the evolutionary score and class of residue i, respectively. These data are obtained by running the SWOTein webserver (babylone.ulb.ac.be/SWOTein/) to compute DG_i value  and Consurf (consurf.tau.ac.il) to compute the evolutionary score using as input data the PDB structures provided in the folder PDBNEW.  


