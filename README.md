# COVID
Rapid and cheap PCR-free COVID-19 detection assay for sharing with the community
Edward Oakeley, 26th March 2020

This idea is proposed as something that should be made available to the global community for investigation by the community under exceptional circumstances for the common good.
	1.	This idea was freely released under the NIBR/Novartis OAK agreement number 42580. 
		a.	It should be noted that the ideas outlined do not relate to his employment activities at Novartis
	2.	It would be the responsibility of anyone acting on the information shared in this repository to ensure that they have all licences necessary to commercialise the work.
	3.	This assay has not been tested nor has Novartis Pharma AG or any of its affiliates sponsored this idea
Basic design
	1.	Make a series of di-nucleotide DNA oligo pairs each pair should be complementary to adjoining regions on the viral genome. To gain sensitivity, having multiple pairs would enable the detection of more than one COVID-19 variant in the same assay
	2.	Sequence-1 should be labelled at the 5’-end with a FRET donor such as Alexa-568
	3.	Sequence-2 should be labelled at the 3’-end with a FRET acceptor such as Alexa-647 (note, Thermofisher does not offer 3’ dye labelled probes. A plan-B might involve a biotin at the 3’ end followed by streptavidin-alexa labelling. A custom order may be possible
	4.	Oligonucleotides may be ordered from: https://www.thermofisher.com/ch/en/home/life-science/oligonucleotides-primers-probes-genes/custom-dna-oligos/oligo-configuration-options.html?open=modification-options#modificationoptions
	5.	When hybridised to the viral genome sequence, Sequence-1 and -2 should have their dyes attached to adjoining bases on the sequence to ensure the dye-dye distance is as small as possible when hybridised
	6.	To ensure equimolarity of hybridisation, sequence-1 and -2 should either be manufactured on the same synthetic oligonucleotide with a poly-A spacer of at least 30 nt or (better) be linked by a non-nucleic acid linker such as polyethylene glycol spacer.
	7.	Multiple probe pairs could be mixed together to increase the variety of COVID-19 genomes detected
	8.	It is proposed that the plate be illuminated between 540-575nm and emission detected between 650-700nm with this dye pair
Assay format
	1.	Dispense oligonucleotide probes (dissolved in water) into a 384 well plate, speed-vac dry to deposit probes, seal plate, enclose plate in foil wrapper to protect from light, ship at room temperature to assay lab. Store in lab at room temperature
	2.	Assay lab removes plate from foil and removes plate seal. Saliva or other non-fluorescent biopsy material is dispensed into plate together with a non-fluorescent detergent and triplet state quencher
	3.	Heat sample to 94C for 30 seconds, cool plate to 22C in a thermocycler as quickly as possible
	4.	Place plate on a platereader such as: https://www.horiba.com/us/en/scientific/products/fluorescence-spectroscopy/accessories/details/micromax-384-microwell-plate-reader-542/ 
	5.	Compare negative control and positive control signals to sample intensity
  
Alternative considerations
	1.	Use Peptidyl-Nucleic Acid for the oligo sequences with a peptide linker backbone
		a.	Dissolve the PNA tags in non-ionic detergent
		b.	Mix the saliva sample with the PNA-detergent mix (detergent should disrupt the viral capsid without the need of heat)
		c.	This might provide an even simpler assay (just add samples to plate, mix and scan)
	2.	Do not use a linker, just add two oligos in excess and assume that both will hybridise independently
	3.	Non-FRET assay
		a.	Instead of a FRET oligo pair use a 3’-biotin tag for oligo-2 and an ALEXA 5’ tag for oligo-1
		b.	Mix sample and oligos then dispense onto a streptavidin/neutravidin-coated plate
		c.	Use evanescent wave illumination to detect ALEXA fluorescence from the molecules bound to the surface
	4.	Signal amplification
		a.	Multiple oligo probes? Multiple fluorophores per oligo (especially for the non-FRET assay
