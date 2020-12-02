# Protocol for PCR amplifying COI and 12S DNA barcodes
### Rupert A. Collins :: December 2020

This protocol is for generating DNA barcodes for the standard COI DNA barcode marker and the 12S MiFish barcode, by Sanger sequencing. Choice of polymerase mastermix depends on if you want to sequence purified or unpurified products (use green mix for former, and colourless mix for latter). With Eurofins, unpurified products can only be sequenced in 96-well plates (PlateSeq Kit PCR) but purified products can be sequenced in 96-well plates (PlateSeq Kit Mix) or ad-hoc in individual tubes (Mix2Seq Kit). Sequencing unpurified products is the cheapest option and the least work, but requires very consistent PCR products.

### Before you start

#### Kit required (manufacturers and part numbers are presented in Table 1 at the bottom): 

* GoTaq green mastermix (for sequencing purified products)
* GoTaq colorless mastermix (for sequencing unpurified products)
* Molecular grade water (DNase/RNase free)
* A pre-paid sequencing kit (e.g. Mix2Seq)
* 1.5 mL microcentrifuge tubes
* 8-strip PCR tubes, or 96-well plate with 8-strip caps
* 10/20 &micro;L XL filter tips
* 200 &micro;L filter tips
* Gel electrophoresis tank and DNA ladder
* Bleach
* 70% ethanol
* Paper towels
* Disposible gloves

#### Things to do before you start:

* Work in the main lab, not the eDNA lab.
* Wipe down the bench with 70% ethanol followed by 10% bleach, followed by 70% ethanol (the "EBE" ethanol-bleach-ethanol clean).
* Ensure you have sufficient gloves, towels, tips, sweetie jars, tubes etc.
* Defrost reagents to room temperature.
* Make aliquots (subsamples) of the GoTaq PCR mastermix, e.g. 250 &micro;L, and return all but one to freezer. This helps prevent contaminating the mastermix stock and will reduce freeze-thaw damage to the polymerase.
* Make ~1 mL aliquots of molecular grade water. Pour the water into the tube from the bottle; never put pipette into the bottle. 
* Prepare stocks of primers at 10 &micro;M and 2 &micro;M. Prepare these in the eDNA lab using filter tips. To make 200 &micro;L of 10 &micro;M primer, add 20 &micro;L of 100 &micro;M stock to 180 &micro;L of water. To make 200 &micro;L of 2 &micro;M primer, add 40 &micro;L of 10 &micro;M stock to 160 &micro;L of water

### Preparing the PCR supermix:

1. In a 1.5 mL microcentrifuge tube, mix reagents sufficient for all of your samples, plus a negative control (water), a positive control (a sample that has worked previously in the lab), and roughly 10% extra to account for pipetting error (see Table 1). Total PCR reaction volume is 20 &micro;L.

### Table 1. A PCR supermix for 6 samples (total n=9 including negative control, positive control and ~10% extra) at 20 &micro;L total reaction volume.
Reagent | Volume n=1 | Volume n=9
--- | --- | ---
GoTaq mastermix | 10 &micro;L  | 90 &micro;L 
Primer Forward (2 &micro;M) | 2 &micro;L  | 18 &micro;L 
Primer Reverse (2 &micro;M) | 2 &micro;L  | 18 &micro;L 
Molecular grade water  | 5 &micro;L  | 45 &micro;L 

2. Vortex the supermix thoroughly. It does not need to be kept on ice, but do not leave it lying around at room temp for hours.
3. Normalise your DNA extracts (template) to 50 ng/&micro;L in a new 1.5 mL microcentrifuge tube (~10 &micro;L total). A handy resource for calculating DNA concentrations is [http://www.desiquintans.com/dilutioncalc](http://www.desiquintans.com/dilutioncalc). If your DNA extracts are less than 50 ng/&micro;L, then use them straight. Remember to vortex.
4. Using the same pipette tip, add 19 &micro;L of the supermix into the PCR strip tubes or plate wells. The strip tubes can be broken apart into smaller strips if needed.
5. Using a new tip each time, add 1 &micro;L of the normalised DNA template to the top of each well so the droplet remains visible on the side (so you can see that you've done it, in case you get distracted), and close the cap. Use 1 &micro;L of water for the negative control.
6. Once all have been added, number and write on the caps corresponding to your lab notes.
7. Spin down tubes in the salad spinner or the mini-centrifuge.
8. Take tube to the PCR machines (thermocyclers).
9. If using the Eppendorf machines, make sure when you add your tubes to the block, that they fit snugly in the *small* holes, not the big holes.
10. If using only a few tubes, it's a good idea to put one empty tube in each corner of the block to ensure that the lid does not damage the tube caps.
11. Program the machine as follows according to your gene target:

### Table 2. Thermocycling parameters.
Step | Cycles | Temperature | Time
--- | --- | --- | ---
Initial denaturation | 1 | 95&#176;C | 2 min
Denaturation | 40 | 95&#176;C | 30 sec
Annealing | 40 | see Table 3. | 30 sec
Extension | 40 | 72&#176;C | 45 sec
Final extension | 1 | 72&#176;C | 5 min

### Table 3. Primer sequences and annealing temperatures.
Primer | Gene | Direction | Sequence (5-3 prime) | Annealing temp
--- | --- | --- | --- | ---
Aa22-12SF | 12S | Forward | AGCATAACACTGAAGATRYTARGA | 53&#176;C
Aa633-12SR | 12S | Reverse | TTCTAGAACAGGCTCCTCTAG | 53&#176;C

12. In a new 50 mL centrifuge tube prepare a mastermix of buffer AL (pre-warmed) and ethanol. You will need 350 &micro;L of each for every sample, plus 10% extra. So, for 5 samples, add 1,925 &micro;L of buffer AL and 1,925 &micro;L of ethanol. Vortex to mix.
13. Add 700 &micro;L of this mastermix to your supernatant, and vortex each samples IMMEDIATELY (important).
14. Add 525 &micro;L of this mixture from step 13 to the DNeasy spin column. take care to pipette the contents gently and from the bottom of the column to prevent salt contamination around the rim. 
15. Centrifuge for 1.5 min at 13,000 g.
16. Remove the column from the collection tube and carefully pipette out the liquid from the collection tube and discard this liquid by ejecting the full pipette tip.
17. Repeat steps 12/13 to pass another 525 &micro;L through the column.
18. Discard collection tube and contents, and place column in new collection tube.
19. Add 600 &micro;L buffer AW1 to the spin column and centrifuge for 1.5 min at 13,000 g. Be sure to add the buffer gently from the bottom as before.
20. Discard collection tube and contents, and place column in new collection tube. Be careful to not let the liquid touch the bottom of the spin column.
21. Add 600 &micro;L buffer AW2 to the spin column and centrifuge for 1.5 min at 13,000 g. Be sure to add the buffer gently from the bottom as before.
22. Use a pipette to remove the liquid from the collection tube as before. Be careful to not let the liquid touch the bottom of the spin column.
23. Centrifuge the spin column and empty collection tube again, this time for 3 min at 20,000 g.
24. Transfer the column to a new 1.5 mL microcentrifuge tube with the cap cut off.
25. Open the spin column cap for 2 min to allow ethanol to evaporate.
26. Add 105 &micro;L of the pre-warmed AE elution buffer. 
27. Close caps and incubate in the oven at 56&#176;C for 5 mins. 
28. Centrifuge the spin column at 13,000 g for 1.5 mins to release the DNA.
29. If required for low yield samples, pipette the eluate back into the spin column and repeat step 28.

### Inhibitor removal, quantification, and storage

1. Pass the eluted DNA through a Zymo OneStep PCR Inhibitor removal column (following manufacturer's instrunctions), and into a 1.5 mL microcentrifuge tube with cap removed.
2. Transfer the eluate into a labelled 1.5 mL LoBind microcentrifuge tube for long term storage. For a tube labelling system, I write the date, and the extraction number from that day, e.g. 08.08.19/4 which would be the fourth sample done on the 8th of August 2019. Refer to the lab book to know which field event this corresponds to
3. Nanodrop 1 &micro;L and record DNA concentration (ng/&micro;L) as well as the 260/280 and 260/230 ratios.
4. Freeze in the eDNA freezer, in a well labelled box (name, date, project etc). Use tape or a piece of card for the labels instead of writing on the box directly with a marker pen.
5. Clean the lab again following steps at the beginning.


### Table 1. Parts and prices
Item | Type | Quantity | Cost (excl. VAT)| Company | Part no.
--- | --- | --- | --- | --- | ---
GoTaq G2 master mix (green) | consumable | 2 x 1,250 &micro;L | £56.25 | Promega UK | M7822
GoTaq G2 master mix (colorless) | consumable |2 x 1,250 &micro;L | £56.25 | Promega UK | M7832
UltraPure DNase/RNase free water | consumable | 500 mL | £10.96 | Thermo Fisher Scientific | 10977035
10/20 &micro;L XL filter tip | consumable | 10 boxes | £36.98 | Starlab UK | S1120-3710
200 &micro;L filter tip | consumable | 10 boxes | £36.98 | Starlab UK | S1120-8710
1.5 mL microcentrifuge tube | consumable | 500 | £14.28 | Starlab UK | S1615-5510
96-well PCR plate | consumable | 20 | £34.68 | Starlab UK | E1403-0200
8-strip PCR caps | consumable | 125 | £10.11 | Starlab UK | I1400-0800
8-Strip PCR tubes | consumable | 120 | £51.70 | Starlab UK | I1402-2900
Ladder III | consumable | 5 x 500 &micro;L | £149.6 | PCR Biosystems | PB40.13-05
PlateSeq Kit PCR | consumable | 96 reactions | £270.00 | Eurofins Genomics | NA
PlateSeq Kit Mix | consumable | 96 reactions | £250.75 | Eurofins Genomics | NA
Mix2Seq Kit | consumable | 96 reactions | £290.00 | Eurofins Genomics | NA
