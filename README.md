# PHYS Labs

Upper year undergraduate physics labs. Data collected and Python/Jupyter data analytics scripts. The folder contents are a bit of a mess, since each project was closer to a physics experiment than rigourous software development. Here, GitHub is being used as an additional storage backup solution.  

These labs are unmodified from when they were retrieved, with the exception of the names of collaborators have been removed for privacy's sake. Since these labs were of the form of an investigation rather than questions and answers, unscrupulous students hoping to skip their lab duties won't find much use here, other than as a reference - always cite your sources!  

Between years three and four, there are a total of four physics labs: [Wireless Power Transfer](#wireless-power-transfer), [Gravitational Constant](#gravitational-constant), [Faraday Rotation](#faraday-rotation), and [Muon Lifetime](#muon-lifetime). There is also a report and graphs from a second year lab, [Stirling Cycle](#stirling-cycle), but unfortunately most of the code was lost when my student account was terminated upon graduation.  

Each experiment's folder will contain four types of items: Jupyter Notebooks data processing scripts (`*.ipynb`), data files (`*.txt` or `*.csv`), output graphs (`*.png`), and a formal lab report (`*.pdf`).  

Data files will be difficult to parse on inspection, mainly because they often lack header; most data was acquired from bread-board circuits through DAQs, so sufficiently barebones where adding a header becomes a pain. Sometimes, but not always, this is remedied in the Jupyter Notebook where when the file is read, it specifies the column name and its units. Similarly, the output graphs may not make sense in isolation, as they were intended to be accompanied by a figure caption in their lab report.  


## Stirling Cycle

A second year lab where we investigated the work done by a simple stirling cycle engine. In the first portion of the experiemnt, the engine sat upon a mug of hot water and used the heat energy to produce work. Pressure readings were taken from within the mug and volume changes from the spinning of the wheel (thus displacement of the piston); this measured work produced by heat. In the second portion, the engine was enclosed in styrofoam and a drill was used to spin the engine in reverse. Temperature readings from both sides of the plate were taken; this measured heat produced by work.


## Wireless Power Transfer

Using a pair of inductively coupled loop gap resonators (LGRs), power can be transmitted wirelessly. Peak power transmittance as a function of seperation distance between the LGRs was measured. This experiments was performed in air, deionised water, and salt water to determine to what extent each dissapated power.


## Gravitational Constant

This experiment replicated the famous (Cavendish experiment)[https://en.wikipedia.org/wiki/Cavendish_experiment], using modern equipment, to determine the gravitational constant, `G`. Additional testing was performed to ensure that the apparatus was well isolated from the ambient vibrations present within the building.


## Faraday Rotation

Light undergoes rotation when it travels parallel to a magnetic field. The amount of rotation, characterised by the Verdet constant, depends on the field strength, the material the light traverses, and the distance through the material the light traverses. This experiment characterised the Verdet constant through several media, with several wavelengths of light, and using several different methods of measurement.


## Muon Lifetime

According to classical mechanics, muons that created in the upper atmosphere should not reach the surface before they decay as their half-like is extremely short (to read more, see [Wikipedia/Muon](https://en.wikipedia.org/wiki/Muon)). However, due to special relativity, we are able to observe them here on the surface. This experiment counted events percieved and simple data analytics allowed these events to be characterised as either a muon entering the device (a capture) or as a muon decaying in the device (a decay). By creating a histogram of capture-decay pairs, the mean muon lifetime can be deduced.

