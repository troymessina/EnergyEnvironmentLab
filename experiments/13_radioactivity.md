(lab13)=
# Lab 13 - Half-life and Radioactive Waste Storage

In southeast New Mexico, more than 650 meters beneath the surface, is the Department of Energyʹs Waste Isolation Pilot Plant (WIPP). Carved out of the ancient salt beds, the WIPP is the model for safe and environmentally sound radioactive waste disposal. It is designed to be a permanent disposal facility for only low‐level radioactive waste. Here, plutonium‐contaminated clothes, gloves, tools, rags, glassware, and other debris will be harbored until its radioactivity dwindles to safe levels. Congress specified that the WIPP should remain undisturbed for 10,000 years. This period was chosen to allow sufficient time to pass for the radioactivity of the debris to drop to safe levels ‐‐ 239Pu has a half‐life of 24,000 years, and 240Pu has a half‐life of 6500 years. The problem is warning future generations of the danger. No human‐made monument has lasted for 10,000 years. The Egyptian pyramids are only half that old. Those pyramids that survived were plundered, and their inscriptions remained unreadable for centuries. Archaeologists and linguists were consulted to devise ways for the WIPP to warn future generations over the next ten millennia. Their final plan includes immense earthworks, granite perimeter monuments, hundreds of buried warning markers, subterranean rooms, a central information structure, and information about the WIPP in archives around the world. Visit the WIPP website at http://www.wipp.energy.gov/ for more information about the project.

Unfortunately, not all nuclear waste is ʹlow‐levelʹ. The waste from nuclear power plants as well as from some military operations cannot be safely stored at WIPP and is currently in various temporary repositories in the US. The general plan is to store this high level waste in a repository in Yucca Mountain, Nevada, although planning and controversy around this repository have continued for almost 20 years and it has still not accepted any waste for storage. One aspect of the controversy concerns the length of time for which the facility should be designed to safely store waste. [](#fig:lab13:halflife) is a plot of one mole ($6.02\times 10^{23}$) atoms of 240Pu decaying over one million years. The graph on the left is a linear scale, and it appears that all of the 240Pu decays before one million years.  However, you will see that radioactivity will continue for up to a million years in the graph on the right (log scale). After one million years, there is still $10^{12}$ atoms of 240Pu remaining. One million years is also of the order of the half life of 237Np which is one of the longest‐lived nuclide known. The target life time for the facility was originally set at 10,000 years, but a court recently ruled that this was too short a time. It is very unclear whether engineers can reliably design a facility to last even 10,000 years.
```{figure} ../figures/lab13/halflife.svg
:label: fig:lab13:halflife
:width: 100%
:align: center
:alt: A graph of the half life of 240Pu. On the left is a linear scale. On the right is a logarithmic scale.
A graph of the half life of 240Pu. On the left is a linear scale. On the right is a logarithmic scale.
```

Not all low‐level waste is produced by the defense industry and power industries.. Nuclear medicine uses radioactive isotopes to diagnose and treat cancers and other diseases. Because certain radioisotopes are attracted to specific organs, their emissions can provide information about a particular disease or cancer. Nuclear techniques can provide data about the function of organs, not just their structure. One consequence of nuclear medicine is a plethora of contaminated waste: syringes, glass, gloves, and vials of radioactive pharmaceuticals. Unlike defense‐related waste, most refuse from nuclear medicine wonʹt be radioactive for millennia. For example, one radioactive isotope of indium, 111In, is used as a ʺtracerʺ to identify tumors and has a half‐life of 2.8 days, much shorter than that of plutonium. In this exercise, you and your partners will find the half‐life of Ba‐137m, a very short lived isotope.

## Pre‐lab reading

Textbook section 7.6

## Equipment

- 1 Radiation Monitor; contains a Geiger‐Mueller tube (GM tube)
- 1 LabPro data collection interface
- 1 Isotope Generator Kit (Barium‐137 m)
- 1 wooden block or other device (for keeping the radiation source in the correct location)

This Cs‐137/Ba‐137m Isotope Generator is used to demonstrate the properties of radioactive decay. Based on the original Union Carbide patented design, it offers exceptional performance, ease‐of‐use and safe operation.

Each generator contains 10 μCi of Cs‐137, which represents one Exempt Quantity, making it free from specific State and Federal licensing. The generator can produce up to 1000 small aliquotes of the short lived Ba‐137m isotope with a half‐life of 2.6 minutes.

Each generator is supplied with 250 mL of eluting solution (0.9% NaCl). The parent isotope Cs‐137 with a half‐life of 30.1 years beta decays (94.6%) to the metastable state of Ba‐137m. This further decays by gamma emission (662 keV) with a half‐life of 2.6 min. to the stable Ba‐137 element. During elution, the Ba‐137m is selectively ʺmilkedʺ from the generator, leaving behind the Cs‐137 parent. Regeneration of the Ba‐137m occurs as the Cs‐137 continues to decay, re‐establishing equilibrium in less than 1 hour.

Approximately 30 minutes after elution, the residual activity of the Ba‐137m sample has decayed to less than one thousandth of its initial activity, making it safe for disposal.

## Procedure

You will use a radiation monitor. The monitor contains a Geiger‐Mueller tube (GM tube) that detects the radiation. The GM tube consists of a cylindrical tube held at a negative potential and a middle wire held at a positive potential. The tube is filled with methane and argon gas that become ionized when radiation passes through the tube. Ionization is the removal of electrons from the gas molecules. These electrons, having a negative charge, are attracted to the positive central wire. These electrons are rapidly accelerated, and the result is a pulse of current that can be detected to indicate a radioactive event. The radioactive events are indicated by a blinking light, an audio sound (if you set it on "audio"), and the scale on the monitor.

1. The radiation monitor is battery powered and will operate without being attached to anything. (For taking data we will connect it to the computer for ease of use.) Turn on the monitor before it is attached to anything and do a little exploring to check on background radiation. You might need to use the "x 10" scale for most of your measurements but if the meter starts to go "off scale" use the "x 100" setting. (The "x1" setting is an option if radioactivity level is not very high.) After checking out the radiation monitor you can make the necessary connections and investigate the half life of the Barium isotope.
2. Connect the LabPro interface to the computer using the USB connector. Plug the interface transformer into the power strip. Connect the cable from the radiation monitor to the "dig/sonic 1" digital channel on the LabPro interface.
3. On the computer open Capstone software. Under file, click "open"; open the folder "probes and sensors" next open the folder "radiation monitor", next open "counts vs time"
4. After opening "counts vs time" you may get a "sensor confirmation" dialog box. Just click OK. Next you need to make some "setting" adjustments. On the menu, near the top of the screen, under experiment choose 'data collection.' In the dialog box make the settings: Mode: Time based; Length: 20 minutes; sampling rate: 1 samples/minute; then click done.
5. When you are ready to take data click on the green "collect" button near the top of the screen. 1st you should take a set of readings to determine the background radiation. It is OK to take about three to six minutes of readings. (The computer should give you the time and the radiation count for each minute. Find the average for one minute so you can subtract the background from the radiation due to the barium sample.) Press the red "stop" button near the top of the screen when you have enough data. After your measurements of background radiation, you and your partners are ready to measure the decay of the generated isotope. The instructor will use the kit to create your sample.
6. Place the barium sample as close to the screen of the radiation monitor as possible. Do not move the sample until you have completed taking data.
7. When you and your partners have finished taking measurements, you must ascertain how many radioactive events occurred in each one‐minute interval. To do this, subtract the background radioactivity in the lab for each one‐minute interval.

## Analysis

1. Plot your results on a graph of counts vs. time. Using Microsoft Excel for these graphs is recommended. (See Appendix II.) You should discover that, as you took your measurements, the radioactivity of the indium decreased. Also make a graph of ($\ln$ counts) vs. time. You and your lab partners should find that the data points form a fairly straight line. The slope of this line is the decay constant, usually represented by the letter $k$. Record this value. Is the value of this slope positive or negative?
2. Radioactive decay is an exponential process. The exponential decay equation is:

$$
N=N_{o}\,e^{-kt}
$$

in which  is $N_{o}$ the initial number present, $N$ is the number present at time $t$, $k$ is still the decay constant and $e$ is the number 2.7182818.. Remember that the half‐life is the time required for half of the nuclei present to decay. If the above equation is solved for the time at which $N$ is one half of $N_{o}$, the result is:

$$
\tau = \frac{\ln 2}{k} \quad \text{or} \quad \tau = \frac{0.693}{k}
$$

You and your partners can use the above equation to calculate the half‐life of 116In by substituting the slope of your natural‐log graph in the place of $k$.

## Conclusions

Report the value for the half‐life of Barium‐137 m. How certain are you of the result? What is the uncertainty in your measurements and analysis? How does the half‐life of this isotope of barium compare to radioisotopes of indium in the table below?

| Isotope of Indium | Half-Life |
|------------|----------------|
| indium‐110 | 1.15 hours     |
| indium‐111 | 2.8 days       |
| indium‐112 | 14.4 minutes   |
| indium‐114 | 1.12 minutes   |
| indium‐115 | 6 x 1014 years |
| indium‐116 | 5 minutes      |
| indium‐117 | 43 minutes     |
| indium‐118 | 5 seconds      |
| indium‐119 | 2.4 minutes    |
| indium‐120 | 44 seconds     |
| indium‐121 | 23 seconds     |

What does the half‐life of Barium‐137m imply for its disposal?

Some environmentalists have objected that research facilities, such as Lawrence Berkeley National Laboratory, contribute too much to the amount of radioactive waste produced in this country. Most of the waste from Lawrence Berkeley Laboratory, for instance, comes from the chemical science and life science branches of the lab. The waste consists largely of radioactive pharmaceuticals and tracers, such as indium‐116. Based on your results in this exercise, what would you say to those environmentalists who contend that Lawrence Berkeley National Laboratory, by storing such waste, is "creating an unsafe environment for Berkeley citizens and the region" (Janice Thomas, the Committee to Minimize Toxic Waste, "Lab Plans Waste Storage Expansion," *The Daily Californian,* 12 Oct 95)? There is no "correct" answer; however, you must support your arguments with your results from this exercise and information from your textbook.