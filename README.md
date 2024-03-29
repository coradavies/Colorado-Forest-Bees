# Colorado-Forest-Bees
Data files associated with Forest restoration treatments indirectly diversify pollination networks via floral- and temperature-mediated effects.

__________
DATA FILES
__________
The following provides information for column designations in all data files included in this repository.   
_____________________________________________________________________________________
Basal_area.csv - Contains plot-level tree data

	Site - plot designation
	Treatment - Control or Thinned  
	Sample - sample number (10 taken at each site)  
	Trees - total number of trees counted using angle gauge  
	Live - total number of live trees counted using angle gauge  
	BAF - basal area factor (10)  
	Live.PIPO - live Pinus ponderosa  
	Dead.PIPO - dead Pinus ponderosa
	Live.PSME - live Pseudotsuga menziesii  
	Dead.PSME - dead Pseudotsuga menziesii  
	Live.PICO - live Pinus contorta  
	Dead.PICO - dead Pinus contorta  
	Live.JUSC - live Juniperus scopulorum  
	Dead.JUSC - dead Juniperus scopulorum  
	BA.all - basal area, including dead and alive trees  
	BA.live - basal area, live trees only  
_____________________________________________________________________________________
BeeIdentification.csv - Contains all bee species ID's

	Number - specimen number (all specimens are labeled and stored at Colorado State University or Utah State University.   
	Date - date specimen was captured  
	Site - plot designation  
	SiteMonth - month captured and site number  
	Treatment - thinned or control (non-thinned)  
	Flower - flower species bee was captured on (if applicable)  
	Flower_status - native or invasive floral species  
	Method - capture method: Net, Blue vane, Pan trap  
	Sex - female (F) or male (M)  
	Genus - genus of identified bee  
	Species - species of identified bee  
	GenusSpecies - genus and species of identified bee   
	Family - family of identified bee  
_____________________________________________________________________________________
CanopyOpenness.csv - Contains measurements for canopy openness

	Site - plot designation  
	Treatment - thinned or control (non-thinned)  
	Photo - photo number  
	Sky - measure of canopy openness calculated from photos with Gap Light Analyzer software  
_____________________________________________________________________________________
CWD.csv - Course Woody Debris fuel load measurements

	Treatment - thinned or control (non-thinned)  
	Site - plot designation   
	Transect - transect number  
	Log_number - number of log within each site  
	Diameter - diameter of log (in inches)  
	Decay - rotten (R) or solid (S)  
_____________________________________________________________________________________
Dataset_1_floral_abundances.csv - Contains data on floral abundances in thinned and non-thinned stands

	Species - floral species
	Control - abundance of floral species 'x' in non-treated control stands 
	Thinned - abundance of floral species 'x' in thinned stands
_____________________________________________________________________________________
Dataset_2_bee_abundance.csv - Contains data on bee abundances in thinned and non-thinned stands

	Family - bee family 
	Genus - bee genus
	(Subgenera) species - species, and if appropriate, morphospecies and/or subgenus 
	Treatment_control - abundance of bee species 'x' in non-treated control stands
	Treatment_thinned - abundance of bee species 'x' in thinned stands 
_____________________________________________________________________________________
Flower_Quadrats.csv - Contains plot-level data on floral density

	Site - plot designation   
	Treatment - thinned or control (non-thinned)  
	Date - date measurements were taken  
	Month - month measurements were taken  
	Quadrat - quadrat number   
	Species - floral species recorded  
	Count - count of floral species recorded  
_____________________________________________________________________________________
GenusTraits.csv - Contains trait designations for bee taxa

	Genus - bee genera  
	Size - size of bee: small, mid, large (relative to Apis mellifera)  
	Nest1 - nesting location  
		above = above ground  
		below = below ground  
		klepto = kleptoparasitic behavior  
	Nest2 - nesting strategy/construction  
		excavate = excavate  
		rent = rent  
		klepto = kleptoparasitic behavior  
	Sociality - sociality of bee genus  
		multiple = varies between species within the genus   
		solitary = solitary behavior  
		social = social behavior  
		klepto = kleptoparasitic behavior  
	Lecty - diet breadth  
		multiple = varies between species within the genus  
		poly = polylectic (wide diet breadth)  
		oligo = oligolectic (narrow diet breadth)  
		klepto = kleptoparasitic behavior  
	Season - phenology of bee species   
		late = peak in August   
		mid = peak in July  
		early = peak in June  
_____________________________________________________________________________________
Ground_Cover.csv - Contains plot-level transect data for ground cover

	Site - plot designation   
	Treatment - thinned or control (non-thinned)  
	Transect - transect number (1-5); 25m transects  
	Point - point number (1 - 20); sampled every 1m  
	Cover_type - category of ground cover  
		Bare = bare ground  
		Litter = litter layer  
		Rock = rock  
		Shrub = shrub of flowering plant  
		Tree = non-flowering shrubs and trees  
		Wood = wood   
		Grass = Grass  
		Forb = Forb  
		Moss = moss  
_____________________________________________________________________________________
SEMvars.csv - Combined data from all other spreadsheets used for construction of Structural Equation Models

	Site - plot designation   
	Treatment - thinned or control (non-thinned)  
	Trees_ha - trees per hectare  
	BA - basal area  
	QMD - quadratic mean diameter  
	Sky - canopy openness (%)  
	floralab - floral abundance  
	floralrich - floral species richness  
	beeab - bee abundance  
	beerich - bee species richness  
	Shannon - Shannon diversity index  
	Simpson - Simpson diversity index  
	Bare - bare ground cover (%)  
	Forb - forb cover (%)  
	Grass - grass cover (%)  
	Litter - litter cover (%)  
	Rock - rock cover (%)  
	Shrub - flowering shrub cover (%)  
	Tree - tree cover (%)  
	Wood - wood cover (%)  
	Volume - CWD volume  
	MeanTemp - mean temperature (C)  
	MaxTemp - maximum temperature (C)  
	MinTemp - minimum temperature (C)  
	interactionab - bee-flower interaction abundance  
	interactionrich - bee-flower interaction richness  
_____________________________________________________________________________________
SiteInformation.csv - Contains plot-level metadata

	NAME - plot designation   
	SITE - site number  
	TREATMENT - treatment: untreated, thinned  
	PROJECT_NAME - CFLRP project name  
	NATIONAL_FOREST - National forest (ARP = Arapahoe Roosevelt National Forest; PSI = Pike San Isabel National Forest)  
	LATITUDE - latitude of site center (decimal degrees)  
	LONGITUDE - longitude of site center (decimal degrees)  
	RESIDUAL_BA - average BA within the CFLRP treatment area  
	YEAR_COMPLETED - year treatment (thinning) was completed  
	TREATED_AREA_HA - size of treatment area (hectares)  
	ELEVATION - elevation of site (feet)  
	ASPECT - aspect of site  
	SLOPE - slope of site   
_____________________________________________________________________________________
TempData - folder of .csv files containing temperature data recorded every 30minutes for each site  
_____________________________________________________________________________________
Tree_Density.csv - Contains information on tree densities, summarized to plot-level

	Site - plot designation   
	Treatment - thinned or control (non-thinned stands)  
	Total_Trees - count of trees within 0.1ha site  
	Saplings - count of saplings within 0.1ha site  
	Dead - count of dead trees within 0.1ha site   
