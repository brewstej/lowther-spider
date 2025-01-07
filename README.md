# lowther-spider

This readme file was initially generated on 2025-01-07 by Jamie Brewster.

This is version 1 dated 2025-01-07.

GENERAL INFORMATION

Title of dataset:
Epigeal spider (Araneae) diversity in early-stage wood-pasture.

Author information:
Name: Jamie Brewster
ORCID: 0000-0001-8091-2752
Institution: Edge Hill University
Address: Derpartment of Biology, Edge Hill University, St Helens Road, Ormskirk, Lancashire, L39 4QP, UK.

Email: brewstej@edgehill.ac.uk, jamie.daniel.brewster@gmail.com

Principle investigator:
Name: Anne Oxbrough
Email: Oxbrouga@edgehill.ac.uk
Role: Head of Department and PhD supervisor

Date of data collection: 2023-05-09 to 2023-09-01

Geographic location of data collection (within ~2km radius of given coordinates):
Latitude: 54.58748668, Longitude: -2.74257201 (Whale, Westmorland and Furness, Cumbria, UK)

Funding sources:
This research is not externally funded (Graduate Teaching Assistant scheme, Edge Hill University).

SHARING/ACCESS INFORMATION:

Licences/restrictions placed on the data:
TBC

Links to publications that cite or use the data:
None to date

Links to other publicly accessible locations of the data:
Data repository link: https://github.com/brewstej/lowther-spider

Links/relationships to ancillary data sets:
None to date

Was data derived from another source?: No

Recommended citation for this dataset:
Brewster, J. (2025). Epigeal spider diversity in early-stage wood-pasture.  

DATA & FILE OVERVIEW

File List:
	1. Spider_MASTER - species x site matrix from pitfall trap collections
	2. Etc

Relationship between files:
Note any fields that tie files together (i.e numeric codes or trap numbers)

Additional related data collected that was not included:
Beetle specimens (unidentified)
Other invertebrate specimens (unidentified)
Woodland pitfall collections from 8 plots (spiders, beetles, other, all unidentified)

Are there multiple versions of the dataset? YES/NO

METHODOLOGICAL INFORMATION

Description of methods used for collection/generation of data:
Spider data were collected using pitfall traps to the following specification - 
	- Clear plastic containers (VWR Sample Container 400ml, height 100ml, top diameter 85mm bottom diameter 72mm - product code 216-2651P)
	- 5 traps per plot at corners and centre of square with a side of 16m
	- Traps filled with ~100ml 50:50 propylene glycol:water (no detergent used)
	- 5 x two-week sample rounds from 2023-05-09 to 2023-09-01
	- Traps covered with ~15cm2 green corriflute suspended ~3cm above opening to reduce influx of rainwater
	- Mesh ladder (2.5cm mesh size) added to all traps to aid small mammal escape and reduce bycatch.
	- Trap, cover and ladder surrounded by wire cage using same mesh as ladder (specs below).  Minimises effects of animal trampling and interference, as used by Lyons et al. (2018)

Wire mesh: Easipet Galvanised Welded Wire Mesh for Aviary Fencing Bird Coop Hutch Mesh 1in x 1in x 48in x 15m (16g)
Product code : 5060164214496.  Sold by B&Q in UK.

Spiders sorted and stored in 70% IMS.  All beetles separated during sorting phase and remaining 'other'.  All assigned unique 'code' identifier.

Methods for processing the data:
Spiders identified using Roberts (Vol 1 and 2).  Names verified against World Spider Catalogue.
Analyses performed with R (v...).

Instrument- or software-specific information needed to interpret the data: 
None

Standards and calibration information:
None

Environmental/experimental conditions:
Traps open for 2-week periods.  1-2 weeks closed in between each of the 5 sample rounds to reduce local depletion.

Quality-assurance procedures:
None

People involved with sample collection, processing, analysis and submission:
	- Jamie Brewster
	- Dr. Anne Oxbrough
	- Dr. Ashley Lyons

DATA-SPECIFIC INFORMATION FOR: Spider_MASTER.csv

Number of variables: X

Number of cases/rows: X

Variable list:

	1. code: unique identifier for contents of each pitfall trap
	2. trap.date: date trap collected 
	3. id.date: date identified
	4. plot: plot code referring to site, treatment type and replicate number
		- WW = Widewath, OG = Outgang, SE = Setterah, WH = Whale
		- M = matrix (open to cattle grazing, sparsely planted), C = clump (exclosure, more densely planted)
		- 1-4 replicate number
	5. treatment:  matrix, clump or control
	6. trap: trap number, 1-5
	7. round: sample round, 1-5
	8. family: spider family name
	9. genus: spider genus name
	10. species: spider species name
	11. full.name: joining of previous two fields for use in graphing
	12. notes: any pertinent notes	
	13. male: number of male individuals recorded
	14. m_vouch: if any individuals are taken to form a voucher/reference collection then numbers are noted here.
	15. female: number of female inviduals recorded 
	16. f_vouch: if any individuals are taken to form a voucher/reference collection then numbers are noted here.
	17. immature: number of immature individuals.  Immature spiders are not reliably identifable to species and are therefore doscounted from later analysis.
	18. unknown: any unidentifable individuals.  This field was created at the beginning of ID process.  May delete.
	19. total: total individuals (sum of male + female + immature)

Missing data codes: (include any used and their meaning)

Specialised formats of other abbreviations used: None


REFERENCES

Lyons, A., et al. (2018). "Epigeal spider assemblage responses to vegetation structure under contrasting grazing management in upland calcareous grasslands." Insect Conservation and Diversity 11(4): 383-395.
	
