# host-dynamics

This folder contains force fields parameters for the macrocyclic hosts investigated in our host-dynamics work.

For atomic charges, this folder includes AM1-BCC and two RESP charges in .mol2 format. The fitting targets of the two RESP charges are the traditional HF/6-31G* ESP and a more up-to-date but very costly selection PW6B95/def2-QZVPP. ESP analyses between the three charge sets and different ab initio references have been presented in the main article. 

The parameter files for macrocyclic hosts under refitting are provided. For bonded and vdW parameters, the GAFF, GAFF2 and refitted FM-B97-3c parameter sets are employed. Term-specific comparison for these host molecules under the two GAFF versions has been provided in the main article. The atomic charges in the prmtop files are from RESP fitting with the HF/6-31G* ESP, following the traition and being consistent with the main-stream practice. Due to the L2 regularization employed in refitting, the initial guess has some impacts. Thus, the refitting is repeated with both GAFF and GAFF2. 

The full text of the work can be accessed freely online at 
