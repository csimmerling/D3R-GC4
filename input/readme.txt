Note
Amber18 GTI doesn't allow each timask to have more than 100 atoms. For ligands with more than 100 atoms, exclude some atoms from timerge and timask.
For the following ligands, timask should be:
00400A timask1=':1 & !@H3,H4,H5,C5,S2,O1,O2,N3,C6,C7' , timask2=':2 & !@H3,H4,H5,C5,S2,O1,O2,N3,C6,C7'   (004 doesn't have more than 100 atoms but some atoms were excluded)
00900A timask1=':1 & !@H3,H4,H5,C5,S2,O1,O2,N3,C6,C7' , timask2=':2 & !@H3,H4,H5,C5,S2,O1,O2,N3,C6,C7'
05200A timask1=':1 & !@H3,H4,H5,C5,S2,O1,O2,N3,C6,C7' , timask2=':2 & !@H3,H4,H5,C5,S2,O1,O2,N3,C6,C7'
16500D timask1=':1 & !@C14,C22' , timask2=':2 & !@C14,C22'
18100C timask1=':1 & !@O1,O2,S2' , timask2=':2 & !@O1,O2,S2'
18500C timask1=':1 & !@C10,C14' , timask2=':2 & !@C10,C14'
