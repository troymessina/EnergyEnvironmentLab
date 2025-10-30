(lab13)=
# Lab 13 - Half-life and Radioactive Waste Storage

In southeast New Mexico, more than 650 meters beneath the surface, is the Department of Energyʹs Waste Isolation Pilot Plant (WIPP). Carved out of the ancient salt beds, the WIPP is the model for safe and environmentally sound radioactive waste disposal. It is designed to be a permanent disposal facility for only low‐level radioactive waste. Here, plutonium‐contaminated clothes, gloves, tools, rags, glassware, and other debris will be harbored until its radioactivity dwindles to safe levels. Congress specified that the WIPP should remain undisturbed for 10,000 years. This period was chosen to allow sufficient time to pass for the radioactivity of the debris to drop to safe levels ‐‐ 239Pu has a half‐life of 24,000 years, and 240Pu has a half‐life of 6500 years. The problem is warning future generations of the danger. No human‐made monument has lasted for 10,000 years. The Egyptian pyramids are only half that old. Those pyramids that survived were plundered, and their inscriptions remained unreadable for centuries. Archaeologists and linguists were consulted to devise ways for the WIPP to warn future generations over the next ten millennia. Their final plan includes immense earthworks, granite perimeter monuments, hundreds of buried warning markers, subterranean rooms, a central information structure, and information about the WIPP in archives around the world. Visit the WIPP website at http://www.wipp.energy.gov/ for more information about the project.

Unfortunately, not all nuclear waste is ʹlow‐levelʹ. The waste from nuclear power plants as well as from some military operations cannot be safely stored at WIPP and is currently in various temporary repositories in the US. The general plan is to store this high level waste in a repository in Yucca Mountain, Nevada, although planning and controversy around this repository have continued for almost 20 years and it has still not accepted any waste for storage. One aspect of the controversy concerns the length of time for which the facility should be designed to safely store waste. [](#fig:lab13:halflife) is a plot of one mole ($6.02\times 10^{23}$) atoms of {sup}`240`Pu decaying over one million years. The graph on the left is a linear scale, and it appears that all of the {sup}`240`Pu decays before one million years.  However, you will see that radioactivity will continue for up to a million years in the graph on the right (log scale). After one million years, there is still $10^{12}$ atoms of {sup}`240`Pu remaining. One million years is also of the order of the half life of {sup}`237`Np which is one of the longest‐lived nuclide known. The target life time for the facility was originally set at 10,000 years, but a court recently ruled that this was too short a time. It is very unclear whether engineers can reliably design a facility to last even 10,000 years.
```{figure} ../figures/lab13/halflife.svg
:label: fig:lab13:halflife
:width: 100%
:align: center
:alt: A graph of the half life of 240Pu. On the left is a linear scale. On the right is a logarithmic scale.
A graph of the half life of 240Pu. On the left is a linear scale. On the right is a logarithmic scale.
```

Not all low‐level waste is produced by the defense industry and power industries.. Nuclear medicine uses radioactive isotopes to diagnose and treat cancers and other diseases. Because certain radioisotopes are attracted to specific organs, their emissions can provide information about a particular disease or cancer. Nuclear techniques can provide data about the function of organs, not just their structure. One consequence of nuclear medicine is a plethora of contaminated waste: syringes, glass, gloves, and vials of radioactive pharmaceuticals. Unlike defense‐related waste, most refuse from nuclear medicine wonʹt be radioactive for millennia. For example, one radioactive isotope of indium, {sup}`111`In, is used as a ʺtracerʺ to identify tumors and has a half‐life of 2.8 days, much shorter than that of plutonium. In this exercise, you and your partners will find the half‐life of {sup}`137`Ba{sub}`m`, a very short lived isotope.

## Pre‐lab reading

Textbook section 7.6

## Equipment

* 1 wireless Geiger‐Mueller tube (GM tube)
* 1 computer with Pasco Capstone software
* 2 long half-life radioactive isotopes, a beta + gamma decay isotope ({sup}`60`Co or {sup}`137`Cs) and a beta decay isotope ({sup}`90`Sr)
* 1 set of radiation blocking materials (plastic and lead)
* 1 isotope Generator Kit (Barium‐137 m from Cesium-137)
* 1 wooden block or other device (for keeping the radiation source in the correct location)

You will first look at two different types of long-lived decays. One decay is a beta, and the other is beta + gamma. Beta decay is when a neutron decays to a proton in the nucleus and an electron is released to conserve charge (a proton and an electron are neutral like the neutron). We call the released electron a beta particle. In gamma decay, a metastable nucleus releases a gamma ray (high energy light particle). This simply alleviates some instability without changing the type of nucleus. In [](#fig:lab13:sr90), the double beta decay of strontium-90 ({sup}`90`{sub}`38`Sr) is shown, which has a half-life of about 29 years for the first beta and 64 hours for the second beta. The first daughter nucleus is yttrium-90 ({sup}`90`{sub}`39`Y). The second, final, daughter nudleus is zirconium-90 ({sup}`90`{sub}`40`Zr). In [](#fig:lab13:co60), the beta decay of cobalt-60 ({sup}`60`{sub}`27`Co) is shown, which has a half-life of about 5 years. Cobalt-60 has two possible beta decays leading to two metastable states that emit gamma rays. The only daughter nucleus is nickel-60 ({sup}`60`{sub}`28`Ni). In [](#fig:lab13:cs137), the beta decay of cesium-137 ({sup}`137`{sub}`55`Cs) is shown, which has a half-life of about 30 years. Cesium,-137 has two possible beta decays leading to one metastable states that emits a gamma ray and the other to a stable barium-137 ({sup}`137`{sub}`56`Ba).
```{figure} ../figures/lab13/strontium90.svg
:label: fig:lab13:sr90
:width: 60%
:align: center
:alt: The double beta decay of strontium-90 ({sup}`90`{sub}`38`Sr) is shown, which has a half-life of about 29 years for the first beta and 64 hours for the second beta. The first daughter nucleus is yttrium-90 ({sup}`90`{sub}`39`Y). The second, final, daughter nudleus is zirconium-90 ({sup}`90`{sub}`40`Zr).
The double beta decay of strontium-90 ({sup}`90`{sub}`38`Sr) is shown, which has a half-life of about 29 years for the first beta and 64 hours for the second beta. The first daughter nucleus is yttrium-90 ({sup}`90`{sub}`39`Y). The second, final, daughter nudleus is zirconium-90 ({sup}`90`{sub}`40`Zr).
```

```{figure} ../figures/lab13/cobalt60.svg
:label: fig:lab13:co60
:width: 60%
:align: center
:alt: The beta decay of cobalt-60 ({sup}`60`{sub}`27`Co) is shown, which has a half-life of about 5 years. Cobalt-60 has two possible beta decays leading to two metastable states that emit gamma rays. The only daughter nucleus is nickel-60 ({sup}`60`{sub}`28`Ni).
The beta decay of cobalt-60 ({sup}`60`{sub}`27`Co) is shown, which has a half-life of about 5 years. Cobalt-60 has two possible beta decays leading to two metastable states that emit gamma rays. The only daughter nucleus is nickel-60 ({sup}`60`{sub}`28`Ni).
```

```{figure} ../figures/lab13/cesium137.svg
:label: fig:lab13:cs137
:width: 65%
:align: center
:alt: The beta decay of cesium-137 ({sup}`137`{sub}`55`Cs) is shown, which has a half-life of about 30 years. Cesium,-137 has two possible beta decays leading to one metastable states that emits a gamma ray and the other to a stable barium-137 ({sup}`137`{sub}`56`Ba).
The beta decay of cesium-137 ({sup}`137`{sub}`55`Cs) is shown, which has a half-life of about 30 years. Cesium,-137 has two possible beta decays leading to one metastable states that emits a gamma ray and the other to a stable barium-137 ({sup}`137`{sub}`56`Ba).
```

This {sup}`137`Cs{sup}`137`/Ba{sub}`m` Isotope Generator is used to demonstrate the properties of radioactive decay. Based on the original Union Carbide patented design, it offers exceptional performance, ease‐of‐use, and safe operation.

Each generator contains 10 μCi of {sup}`137`Cs, which represents one Exempt Quantity, making it free from specific State and Federal licensing. The generator can produce up to 1000 small aliquotes of the short lived {sup}`137`Ba{sub}`m` isotope with a half‐life of 2.6 minutes.

Each generator is supplied with 250 mL of eluting solution (0.9% NaCl). The parent isotope {sup}`137`Cs with a half‐life of 30.1 years beta decays (94.6%) to the metastable state of {sup}`137`Ba{sub}`m`. This further decays by gamma emission (662 keV) with a half‐life of 2.6 min. to the stable {sup}`137`Ba element. During elution, the {sup}`137`Ba{sub}`m` is selectively "milked" from the generator, leaving behind the {sup}`137`Cs parent. Regeneration of the {sup}`137`Ba{sub}`m` occurs as the {sup}`137`Cs continues to decay, re‐establishing equilibrium in less than 1 hour.

Approximately 30 minutes after elution, the residual activity of the {sup}`137`Ba{sub}`m` sample has decayed to less than one thousandth of its initial activity, making it safe for disposal.

## Procedure

You will use a radiation monitor. The monitor contains a Geiger‐Mueller tube (GM tube) that detects the radiation. The GM tube consists of a cylindrical tube held at a negative potential and a middle wire held at a positive potential. The tube is filled with methane and argon gas that become ionized when radiation passes through the tube. Ionization is the removal of electrons from the gas molecules. These electrons, having a negative charge, are attracted to the positive central wire. These electrons are rapidly accelerated, and the result is a pulse of current that can be detected to indicate a radioactive event. The radioactive events are indicated by a blinking light or an audio sound.

### Part 1 - Long-lived isotopes and radiation shielding
1. The radiation monitor is battery powered and will operate without being attached to anything. (It connects through bluetooth to Pasco Capstone software.) Turn on the monitor before it is attached to anything and do a little exploring to check on background radiation. After checking out the radiation monitor you can make the necessary connections and investigate the radioactivity and half life isotopes.
2. On the computer open Capstone software. In the Hardware Setup, find your radiation monitor and select it. Change the graph axes to Counts/sample on the y-axis and time on the x-axis.
3. At the bottom of the screen you can select the sample time. Start with 15 seconds for the first portion of the lab.
4. Place the radiation monitor about 3 inches from the table surface using a metal stand. 
5. With no radioactive source nearby, click on the red record near the bottom of the screen. The computer will graph the radiation count for each 15 seconds. Find the average and standard deviation for two minutes (8 data points). Your instructor or TA can help. This is the background radiation.
6. Next, place a beta + gamma source under the radioativity monitor and repeat the data collection for two minutes. Find the average and standard deviation for two minutes (8 data points). Record this as ${\rm average~\pm~standard~deviation}$
7. Repeat step 6 with 2 different thicknesses of plastic between the radiation monitor and the radioactive isotope. **Be careful not to change the height of the radiation monitor!**
8. Repeat step 6 with 2 different thicknesses of lead between the radiation monitor and the radioactive isotope. **Be careful not to change the height of the radiation monitor!**
9. Repeat steps 6-8 with the beta decay isotope.


### Part 2 - Radioactive Decay
The instructor will use the kit to create your barium sample.
1. Place the barium sample about 2 inches from the radiation monitor. Do not move the monitor until you have completed taking both sets of data.
2. Collect the radiation counts for samples of 5 seconds. Record for a minimum of 10 minutes. Fifteen minutes is better.
3. Fit the half-life equation {eq}`eq:lab13:halflife` to your data.
4. Repeat steps 3 and 4 with samples of 30 seconds.

## Analysis

### Part 1 - Long-lived isotopes and radiation shielding

1. How can you use your measurements to say whether a source is radioactive compared to the background?
2. Do your recordings of long-lived isotopes change over time? What does this say about the half-life of these isotopes?
3. Compare the recordings of the gamma + beta and the beta decay sources. Can you conclude anything about shielding the two kinds of radiation. For example, does plastic shield both kinds of radiation? Does lead? How do you use your results to draw these conclusions?

### Part 2 - Radioactive Decay

1. Did the sample length (5 seconds vs. 30 seconds) make a difference? Explain the differences.
2. Radioactive decay is an exponential process. Your instructor or TA will help you fit a model equation to your data. The exponential decay equation is:

```{math}
:label: eq:lab13:exponential
N=N_{o}\,e^{-kt}
```
where is $N_{o}$ the initial number of decayse present, $N$ is the number present at time $t$, $k$ is the decay constant and $e$ is the number 2.7182818.

We can also convert the base $e$ to base $1/2$.

```{math}
:label: eq:lab13:halflife
N = N_{o}\,0.5^{t/\tau}
```

where $\tau$ is the half-life. Half‐life is the time required for half of the nuclei present to decay. If equation {eq}`eq:lab13:exponential` is solved for the time at which $N$ is one half of $N_{o}$, the result is:

$$
\tau = \frac{\ln 2}{k} \quad \text{or} \quad \tau = \frac{0.693}{k}
$$

3. This makes it possible to calculate the half‐life $\tau$ of {sup}`137`Ba{sub}`m` by substituting the $k$ of an exponential graph. Show that this conversion works by fitting both equations to one of your graphs. 

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