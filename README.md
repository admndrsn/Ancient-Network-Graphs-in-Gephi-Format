# Gephi
Network graphs in Gephi
## The following files are the early results of my dissertation research (please cite accordingly): Adam G. Anderson, "The Old Assyrian Social Network: an analysis of the texts from Kültepe-Kaneš (1950-1750 B.C.E.)" Harvard University, 2018.
- AttestationNetwork : Generated from historical cuneiform texts (6k "Cappadocian" texts 1950-1750 BC) dataset courtesy of the Old Assyrian Text Project (OATP).
- OASN 1.2 : an epistolary network (c. 3k nodes) via unsupervised disambiguation (@dbamman), generated from the "Cappadocian" texts (2k letters 1950-1750 BC), dataset courtesy of the Old Assyrian Text Project (OATP). This network has been tested at multiple points to be 80% accurate.
- Salim-AssurArchive (2.5) : an attestation network via supervised disambiguation (@admndrsn). This network is incomplete, but shared openly for scholarly collaboration.
- comentionNetwork : a subset of the epistolary network, in which nodes are connected retained if >10 co-mentions (@dbamman).
## The Drehem graph files are the preliminary results of network analysis used as a prosopographical disambiguation method for the ca. 15,000 Sumerian Ur III texts (ca. 2100-2004 bce), which have been attributed to the province of Drehem, ancient Puzriš-Dagan. The source files and code is maintained at the GitHub @niekveldhuis)
- Drehem_01 : the first iteration of the network of merged personal names from the texts, a dynamic network, in two file formats. Directionality was determined by explicit markers for the roles in the texts. 
- Drehem_082t : includes the eighth+ iteration of the merged network, a static network, with a time interval. (Ongoing iterations can be found @niekveldhuis)
