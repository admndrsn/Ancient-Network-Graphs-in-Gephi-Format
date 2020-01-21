# Gephi
Network graphs in Gephi
## The following 5 files are the early results of my dissertation research (please cite accordingly): Adam G. Anderson, "The Old Assyrian Social Network: an analysis of the texts from Kültepe-Kaneš (1950-1750 B.C.E.)" Harvard University, 2018.
- AttestationNetwork (2018) : Generated from historical cuneiform texts (6k "Cappadocian" texts 1950-1750 BC) dataset courtesy of the Old Assyrian Text Project (OATP).
- OASN 1.2 (2018): an epistolary network (ca. 3k nodes) via unsupervised disambiguation (@dbamman), generated from the "Cappadocian" texts (2k letters 1950-1750 BC), dataset courtesy of the Old Assyrian Text Project (OATP). 
- Salim-AssurArchive (2.5 2018) : an attestation network via supervised disambiguation and close readings. This network is incomplete, but shared openly for scholarly collaboration.
- comentionNetwork (2018): a subset of the graph OASN 1.2 network, in which nodes are retained if >10 co-mentions (@dbamman).
- OASN 2.6gf (2020) : a multi-modal network derived from the AttestationNetwork, which includes geocoordinates for ca. 40 geographical names, and attributes for documented females. 

## These three Drehem graph files are the preliminary results of network analysis used as a prosopographical disambiguation method for the ca. 15,000 Sumerian Ur III texts (ca. 2100-2004 bce), which have been attributed to the province of Drehem, ancient Puzriš-Dagan. The source files are courtesy of BDTNS (http://bdtns.filol.csic.es/) and ORACC () the code is maintained at the GitHub of Niek Veldhuis @niekveldhuis under Sumerian-network repository. (Cite these files as GitHub @admndrsn/Gephi/Drehem_#).
- Drehem_01 : the first iteration (2017) of the network of merged personal names from the texts, a dynamic network, in two file formats. Directionality was determined by explicit markers for the roles in the texts. 
- Drehem_082t : includes the eighth+ iteration (2018) of the merged network, a static network, with a time interval. (Ongoing iterations of jupyter noteboks can be found @niekveldhuis).
- Drehem_08GN : the eighth iteration (2018-2019) includes a geographical network, with ca. 350 nodes representing attested Geographic Names (GN). The geo-coordinates are taken from Pedersen (http://ancientworldonline.blogspot.com/2011/07/ane-placemarks-for-google-earth.html).
