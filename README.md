# Avian_Endocast_Validation
Data and analysis for validation of the use of surface areas of the whole, telencephalon and cerebellum regions of bird endocasts.
Aubrey R. Keirnan1, Felipe Cunha2, Sara Citron2, Gavin Prideaux1, Andrew N. Iwaniuk2*, Vera Weisbecker1*
1 College of Science and Engineering, Flinders University, Adelaide SA, Australia
2 Department of Neuroscience, University of Lethbridge, Lethbridge, Alberta, Canada

#Main data: Data_raw.csv
#column titles
type: Scan = CT scanned source. Wet = Histological source
ID	= Collection identifier
labelled as = source label
BirdTree	= Phylogeny label
Genus	= genus
species	= species
common_name	= common name
order = order
family = family
brVOL_telen = brain volume for histological source of telencephalon volume
brVOL_cere = brain volume for histological source of cerebellum volume
telenVOL = telencephalon volume for histological source
cereVOL	= cerebellum volume for histological source
endoSA	= endocast surface area from CT scanned specimen
telenSA	= telencephalon surface area from CT scanned specimen
cereSA	= cerebellum surface are from CT scanned specimen
endoVOL	= endocast volume
wet_source	= source for histological specimens
cite_as	= CT scan citation 
NOTES = specimen notes	
ark	= morphosource ARK ID
X	, Y ,	Z = voxels
![image](https://github.com/user-attachments/assets/f54ac939-ed4d-4425-9c48-28960cc75d1b)


#Data collection methods:
Data on whole brain, telencephalon and cerebellum volumes were compiled from the literature (Portmann 1947; Alama and Bee-dee-Speroni 1992; Boire and Baron 1994; Carezzano and Bee de Speroni 1995; Iwaniuk and Nelson 2003; Day et al. 2005; Iwaniuk and Hurd 2005; Kalisińska 2005; Corfield et al. 2011; Corfield et al. 2012; Krilow and Iwaniuk 2015; Barros da Cunha 2021; Cunha et al. 2021) and supplemented with previously unpublished data from a histological collection maintained by A.N.I (Iwaniuk 2011). These specimens were provided to A.N.I dead and were not euthanised for the purpose of this study. Further, all procedures were completed in accordance with the guidelines and policies of the Canada Council on Animal Care. All of these brains were gelatin-embedded and serially sectioned in the coronal plane at a thickness of 40µm. After mounting and staining with thionin acetate, the volumes were measured using unbiased stereology in StereoInvestigator (Microbrightfield Inc., VT, USA) by FC. For some species, the telencephalon and cerebellum volumes were measured from different individuals. In such cases, we included the brain volumes for both individuals to accurately calculate the relative size of brain regions. More details on the brain processing and volume measurement methods are described in (Barros da Cunha 2021). All data and their sources are provided in electronic supplementary material.


#Abstract:
For studies of the evolution of vertebrate brain anatomy and potentially associated behaviours, reconstructions of digital brain endocasts from computed tomography scans have revolutionised our capacity to collect neuroanatomical data. However, measurements from digital endocasts must be validated as reflecting actual brain anatomy, which is difficult because the collection of soft tissue information through histology is laborious and time consuming. In birds, the reliability of digital endocast measurements as volume proxies for the two largest brain regions – the telencephalon and cerebellum - remains to be validated despite their use as proxies e.g. of cognitive performance or flight ability. We here use the largest dataset of histology and digital endocasts to date, including 136 species from 25 avian orders, to compare digital endocast surface area measurements with actual brain volumes of the telencephalon, cerebellum, and whole-brain endocast. Using linear and phylogenetically informed regression analyses, we demonstrate that endocast surfaces are strongly correlated with their brain volume counterparts for both absolute and relative size. This provides empirical support for using endocast-derived cerebellar and telencephalic surface areas in existing and future studies of living and extinct birds, with potential to expand to the dinosaur-bird transition in the future.
