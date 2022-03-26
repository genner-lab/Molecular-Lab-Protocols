# Protocols for running species-specific qPCR assays for tilapia species
### Rupert Collins, Andy Saxon, Martin Genner :: March 2022

This protocol describes quantitative PCR (qPCR) assays to detect three species of tilapia cichlid present in Tanzanian aquaculture: _Oreochromis leucostictus_ (blue-spotted tilapia), _Oreochromis niloticus_ (Nile tilapia), and _Oreochromis urolepis_ (Wami tilapia). 

### Before you start

#### Equipment required (manufacturers and part numbers are presented in Table 1 at the bottom):

* Thermocycler (Chai Bio Open qPCR machine) 
* Laptop computer
* Pipettes and filtered pipette tips (10-20 &micro;L, 200 &micro;L, 1000 &micro;L)
* 1.5 mL microcentrifuge tubes
* Bench-top vortex
* Bench-top tube spinner
* Plastic tube racks
* Lab note book
* 10% bleach in squeezy wash bottle 
* 70% ethanol in squeezy wash bottle
* Paper towels
* Disposible gloves

#### Reagents and aliquots required (full details are presented in Table 2 at the bottom):

Note: These reagents need to stored frozen in dedicated boxes at -20&#176;C when not in use, and to avoid cross contamination the eDNA samples and amplification standards need to be stored in separate boxes to the assay reagents and from each other.

* Chai Bio Sahara Hot Start PCR Master Mix
* Nuclease free "ultrapure" water in 1 mL aliquots
* Premixed primer+probe (PPM) in 50 &micro;L aliquots
* Your eDNA sample template DNA
* qPCR assay amplification standards at a one billion copy/&micro;L stock solution

#### Before each experiment:

* Wipe down the bench surfaces with 70% ethanol followed by 10% bleach, followed by 70% ethanol (the "EBE" clean). Do NOT bleach the qPCR machine.
* Ensure you have sufficient gloves, tips, tip disposal jars, tubes etc.
* Ensure all reagent working stocks are sufficient and defrosted

### Connecting the qPCR machine:

Note: Calibration of Open qPCR machine may be necessary on initial installation. See machine manual found at [Open_qPCR_User_Manual.pdf](https://static.chaibio.com/spree/products/114/Open_qPCR_User_Manual.pdf).

1. Connect laptop to Open qPCR machine via USB cable. Start machine. it will take around 5 mins to complete the boot sequence.
2. All commands to operate the Open qPCR machine are interfaced via your web browser.
3. When the boot sequence has completed, open a web browser (e.g. Google Chrome) on the laptop and type "192.168.7.2" into the address bar. Log into the machine.

### Setting the thermocycling conditions

1. On the Welcome page, select "Create a new experiment" and name it with the date and any additional details
2. On the Edit Protocol page, now set up cycling conditions (Table 1; Figure 1) for the Chai Bio Sahara Master Mix (these conditions may not apply to other master mixes and assays).

#### Table 1. Cycling conditions
| PCR Step | Time | Temperature | Number cycles |
| :--- | :--- | :--- | :--- |
| Initial denaturation | 1 min | 95&#176;C | 1 (holding) |
| Denaturation | 15 s | 95&#176;C | 40 |
| Annealing | 30 s | 60&#176;C | 40 |

#### Figure 1. Cycling conditions
<img src="assets/cycling.png" width="500">

### Setting the samples and targets

1. On the Samples + Targets page (see Figure 2), add names of the samples and amplification standards used in the experiment.
2. Here, the standards are named with the number of copies, in thousands, from 100,000 (100k) to 100 copies (0.1k).
3. Our unknown field sample is simply called "Sample" in this example.

#### Figure 2. Samples
<img src="assets/samples.png" width="600">

4. Next add the target. This is the name of the species detection assay that we are using.
5. Here we named the target assay "leuco" as we used the _Oreochromis leucostictus_ assay, otherwise "nilo" or "uro".

<img src="assets/targets.png" width="600">

### Setting the well layout

1. Each standard or field sample should be performed in triplicate to reduce variation common among individual replicates.
2. Highlight all wells and set the target to "leuco" from the Target drop-down menu.
3. Now highlight three wells (A1, A2, A3) and choose a "100k" standard from the Sample drop-down menu.
4. Choose "S" (standard) from the Type menu, and manually enter "100000" into the set quantification to 100,000 copies.

<img src="assets/well-layout.png" width="600">

5. Repeat for all quantification standards down to 100 copies. Be sure to check they match with the names given and have the correct number of zeros.
6. For our field samples, assign these to wells A7, A8, B7, choose "Sample" and Type "U" (unknown).
7. Add an additional well (B8) as a negative control (Type "-").

<img src="assets/well-layout-full.png" width="600">

### Preparing the PCR reaction mix

1. In a clean 1.5 mL microcentrifuge tube prepare a PCR reaction mix sufficient for x16 10 &micro;L PCR reactions.
2. We prepare enough reagents for 17, to account for loss from pipetting error or evaporation.
3. Add the volume with the appropriate pipette for maximum accuracy.
4. The 

### Table XXX. A 10 &micro;L PCR reaction mix for x16 wells
Addition | Reagent | Volume x 1 (&micro;L) | Volume x17 (&micro;L) |
| :---| :--- | ---: | ---: |
| combined | Sahara Hot Start PCR Master Mix | 5 | 85 |
| combined | primer+probe mix | 0.5 | 8.5 |
| combined | ultrapure water | 3.5 | 59.5 |
| individual | sample/standard/control | 1 | NA |

5. Vortex to mix the reagents well
6. Add 9 &micro;L of this mixture to each 0.1 mL PCR tube well.
7. Put away all reagents stocks back in the freezer.

### Adding the standards and eDNA field samples

1. To negative control well B8, add 1 &micro;L of ultrapure water. This is to verify that the reagents are not contaminated with target DNA.
2. To sample wells A7, A8, B7, add 1 &micro;L of eDNA field sample
3. Dilute field sample!
3. To minimise risk of cross contamination, it is important to add the negative control water first, followed by eDNA field sample, followed by quantification standards.
4. Prepare the quantification standards on a seperate bench area and put away the 
4. Further, ensure that pipettes that are used for handling quantification standards are never used for preparing the PCR reactions or eDNA field samples.
5. ff

### Considerations

1. Run all without standards, and then repeat with standards for those positive.
2. 


### Table XXX. Parts and suppliers
| Type | Item | Supplier | Part no. |
| :--- | :--- | :--- | :--- |
| equipment | Open qPCR machine | Chai Bio | Single channel |
| equipment | Pipette starter pack (4x pipettes) | Starlab UK | STARTERPACK42.5 |
| equipment | Vortamix Mini Vortexer | SLS | ARG1878 |
| equipment | Mini Fuge tube spinner | SLS | N2631-0017 |
| equipment | 250 mL wash bottle | SLS | BOT9000 |
| equipment | 96-well 1.5 mL microcentrifuge tube rack | Starlab UK | I2396-5048 |
| equipment | 96-well 0.2 mL PCR tube rack | Starlab UK | E2396-5240 |
| equipment | 81-tube freezer storage box | Starlab UK | I2381-5040 |
| consumable (plastic) | 10/20 &micro;L pipette filter tips | Starlab UK | S1120-3710 |
| consumable (plastic) | 200 &micro;L pipette filter tips | Starlab UK | S1120-8710 |
| consumable (plastic) | 1000 &micro;L pipette filter tips | Starlab UK | S1122-1730 |
| consumable (plastic) | 1.5 mL microcentrifuge tube | Starlab UK | S1615-5510 |
| consumable (plastic) | 0.1 mL qPCR 8-well tube strips | Chai Bio | S02132B |
| consumable (reagent) | Chai Bio Sahara Hot Start PCR Master Mix | Chai Bio | R02151M |
| consumable (reagent) | Nuclease-free ultrapure water | Thermo Fisher Scientific | 10977035 |
| consumable (reagent) | qPCR assay primers and probes | Eurofins Genomics | as required |
