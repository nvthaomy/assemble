Notes on generating PDB with connectivity:
Connectivity is enable only when all monomer PDBs have CONECT flags
Monomer PDBs, including end monomers,  must have all four limit sections (LIMIT HEAD, LIMIT TAIL, LIMIT HEAD_HOOK, LIMIT TAIL_HOOK)
	e.g.: for a CH3 group in an end monomer, add dummy H atom to an H on the CH3 group	      in this case, the dummy H is the HOOK and the H bonded to it is the TAIL (or HEAD)
