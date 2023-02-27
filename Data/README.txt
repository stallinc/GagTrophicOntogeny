# Trophic ontogeny of a generalist predator is conserved across space
Consumers can influence ecological patterns and processes through their trophic roles and contributions to the flow of energy through ecosystems. However, the diet and associated trophic roles of consumers commonly changes during ontogeny. Despite the prevalence of ontogenetic variation in trophic roles of most animals, we lack an understanding of whether they change consistently across local populations and broad geographic gradients. We examined how the diet and trophic position of a generalist marine predator varied with ontogeny across seven broadly separated locations (~750km). We observed a high degree of heterogeneity in prey consumed without evidence of spatial structuring in this variability. However, compound specific isotope analysis of amino acids revealed remarkably consistent patterns of increasing trophic position through ontogeny across local populations, suggesting that the roles of this generalist predator scaled with its body size across space. Given the high degree of diet heterogeneity we observed, this finding suggests that even though the dietary patterns differed, the underlying food web architecture transcended variation in prey species across locations for this generalist consumer. Our research addresses a gap in empirical field work regarding the interplay between stage-structured populations and food webs, and suggests ontogenetic changes in trophic position can be consistent in generalist consumers.

These data are asscoiated with the following publication:
Stallings, C.D., J.A. Nelson, E.B. Peebles, G. Ellis, E.A. Goddard, N.K. Jue, A. Mickle, O.E. Tzadik, and C.C. Koenig. 2023. Trophic ontogeny of a generalist predator is conserved across space. Oecologia. DOI: 10.1007/s00442-023-05337-6

## Description of the data and file structure
We collected juvenile gag (mycteroperca microlepis) from seven seagrass systems that spanned over 750km of the Florida, USA coastline in the eastern Gulf of Mexico. We processed the fish in three ways to examine how the diet and trophic position of this generalist marine predator varied with otogeney across the seven local populations. These methods included: 1) stomach contents analysis, 2) 2) bulk-tissue stable-isotope analysis of δ15N (SIA), and 3) compound-specific amino-acid stable-isotope analysis of δ15N (CSIA-AA). The associated data files correspond to each of these three methods and are explained below.

Stomach Contents (file: dat_diet.csv)
region: identifier for the seagrass system where the gag was collected; Saint Andrews Bay (SAB), St. Joseph Bay (SJB), Turkey Point Shoal (TPS), Big Bend Region (BBR), Tampa Bay (TAM), Sarasota Bay (SAR), and Pine Island Sound (PIS).
fishID: unique identifier for each gag
total.length: total length of each gag in centimeters.
prey.type: broad definitions of prey consumed, including empty (no prey in stomach), Fish, large crustaceans (LS), and small crustaceans (SS).
prey.family: family of identified prey consumed.
prey.genus: genus of identified prey consumed.
prey.species: species of identified prey consumed.
prey.no: number of identified prey consumed corresponding to each prey species.
prey.mass: mass (in grams) of identified prey consumed corresponding to each prey species.
prey.vol: volume (in ml) of identified prey consumed corresponding to each prey species. Volume was measured using the water displacement method.

Bulk Stable Isotopes (file: dat_bulk.csv)
region: identifier for the seagrass system where the gag was collected; Saint Andrews Bay (SAB), St. Joseph Bay (SJB), Turkey Point Shoal (TPS), Big Bend Region (BBR), Tampa Bay (TAM), Sarasota Bay (SAR), and Pine Island Sound (PIS).
fishID: unique identifier for each gag
total.length: total length of each gag in centimeters.
dN:  values of δ15N from bulk-tissue stable-isotope analysis.
dC: values of δ13C from bulk-tissue stable-isotope analysis.

Compound-Specific Amino-Acid Isotopes (file: dat_csaa.csv)
region: identifier for the seagrass system where the gag was collected; Saint Andrews Bay (SAB), St. Joseph Bay (SJB), Turkey Point Shoal (TPS), Big Bend Region (BBR), Tampa Bay (TAM), Sarasota Bay (SAR), and Pine Island Sound (PIS).
fishID: unique identifier for each gag
total.length: total length of each gag in centimeters.
asx: values of δ15N of aspartic acid from compound-specific amino-acid stable-isotope analysis.
glx: values of δ15N of glutamic acid from compound-specific amino-acid stable-isotope analysis.
phe: values of δ15N of phenylalanine from compound-specific amino-acid stable-isotope analysis.
glx.phe: calculated values of glumatic acid minus phenylalanine.
asx.phe: calculated values of aspartic acid minus phenylalanine.
tp.glx.phe: estimated trophic position of gag based on the equation TPGlu/Phe = (δ15NGlu – δ15NPhe – 3.4)/7.6 + 1

