# P02-Biological-terms-review
A collaborative project to review and streamline biological codes in the SDN Parameter Discovery Vocab P02.

Rationale
---------
The list of P02 discovery parameter terms linked (via P03) to the P08 category “Biological oceanography” is cluttered with terms specifying some degree of “taxonomic dependency”. For example: {BNUC	for Bacteria generic abundance in sediment} and {BAUC	for Bacteria taxonomic abundance in sediment}. This distinction between taxonomic/non-taxonomic or generic criteria was made when BODC started mapping its biological codes to the ITIS species registry and before P02 became a key vocabulary for data discovery as adopted by SeaDataNet/SeaDataCloud in Europe. The need for this distinction at the P02 level has become obsolete and confusing. It is proposed to address this as part of our review the P02 Parameter Discovery vocabulary. 


First step: Rationalise abundance and biomass codes
----------------------------------------------------

Option #1	(see and edit XL file abundance_and_biomass) - this proposal assumes that we will keep some degree of distinction between broad organisms' type (prokaryotes, phytopankton, zooplankton etc.) at the P02 level at least for the abundance and biomass codes. These have been kept close to what was already in place but the distinction taxonomic/non-taxonomic has been removed. Also I have tended to group abundance and counts and kept biomass separate. Abundance and/or counts or densities are typically associated with field surveys while biomass would be more often associated with environmental modelling and ecological budgeting. 

Feedback needed and ideas and alternative approaches welcome.

Option #2 would be going completely generic with, for example, codes for: Biota abundance in water bodies, Biota abundance on the bed or in sediments, Biota biomass in water bodies, Biota biomass on the bed or in sediments, Biota counts in water bodies, Biota counts on the bed or in sediments, etc.

All would map to P03 B070. However with option#2 users would no longer be able to target specific groups of organisms via the P02 marking unless we allow P01 to P02 to move from a many-2-1 to a many-2-many relationship. If we stay with the many-2-1 then dataset markup via CDIs or dataset discovery via EDMED would no longer be able to target specific group of organisms using P02. If we allow many P02 for one P01 the management of the relationships becomes more complexe.

Second step: look at other P02 codes linked to P03 codes under P08 "Biological Oceanography"
--------------------------------------------------------------------------------------------
List candidates for deprecation, broadening and new terms. I propose to start working on this once we've reached a consensus on the abundance and biomass codes.
