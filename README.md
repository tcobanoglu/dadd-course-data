# Data Analysis in Drug Discovery course data

## Week 2 · Comparing DPP-4 inhibitors

The practical asks students to select three drugs whose molecular structures they would like to compare in complexes with human dipeptidyl peptidase 4 (DPP-4). The files below provide the compound collection, two representations of sitagliptin and the experimental protein–ligand complex.

| Course file | Contents | Original source |
|---|---|---|
| [dpp4_compounds.csv](data/week2/dpp4_compounds.csv) | 28 selected ligands. Each row gives the course ID, compound name or ligand code, SMILES, associated PDB entry and reference-drug flag. D01–D06 are the six reference medicines. | Curated course table using [PubChem](https://pubchem.ncbi.nlm.nih.gov/) and the [wwPDB Chemical Component Dictionary](https://www.wwpdb.org/data/ccd). To inspect an associated complex, enter its `pdb_id` at [RCSB PDB](https://www.rcsb.org/). |
| [sitagliptin_2d.sdf](data/week2/sitagliptin_2d.sdf) | 2D drawing of sitagliptin, PubChem CID 4369359. | [PubChem compound record](https://pubchem.ncbi.nlm.nih.gov/compound/4369359) · [PUG REST download](https://pubchem.ncbi.nlm.nih.gov/rest/pug/compound/cid/4369359/SDF?record_type=2d) |
| [sitagliptin_bound.sdf](data/week2/sitagliptin_bound.sdf) | Coordinates of the bound ligand from PDB entry 1X70, author chain A, component 715. | [RCSB ligand record](https://www.rcsb.org/ligand/715) · [RCSB ModelServer download](https://models.rcsb.org/v1/1x70/ligand?auth_asym_id=A&label_comp_id=715&encoding=sdf) |
| [1X70.pdb](data/week2/1X70.pdb) | Full experimental model of DPP-4 bound to sitagliptin. Protein and ligand atoms share a coordinate frame for distance measurements. | [RCSB entry 1X70](https://www.rcsb.org/structure/1X70) · [PDB file download](https://files.rcsb.org/download/1X70.pdb) |

The structure files are copies of the source exports retrieved on 25 November 2026. The compound IDs beginning with D are course identifiers. Similarity distributions in the practical describe this selected collection.
