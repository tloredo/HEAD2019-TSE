# Exploring time series data in high energy astrophysics
This repository hosts resources supporting the  Special Session, *Exploring time series data in high energy astrophysics*, held at the AAS High Energy Astrophysics Division 17th Divisional Meeting, Monterey CA, 18 March 2019, organized by Tom Loredo and Jeff Scargle.

To copy the material to your computer, we suggest you use **Download ZIP** (on GitHub) rather than clone the repo. This will spare you from downloading old versions of the PDF files that Git unfortunately does note efficiently handle in the repo history.

## Overview

The session included three presentations (slides are availabe here as PDF files):

* *Session introduction/Time series exploration in Python & MATLAB* (Tom Loredo & Jeff Scargle)
* *Time series exploration with Stingray: New tools for spectral-timing analysis of X-ray data* (Abigail Stevens)
* *Modeling time variability of AGN with the CARMA models* (Malgorzata Sobolewska)

Full abstracts for the presentations appear below.

Links to content for the session not included in this repo:

* R Shiny apps demonstrating new Bayesian Blocks algorithms (Jeff Scargle and Ryan Shiroma):
  * [Bayesian Blocks for BATSE GRBs](https://rshiroma.shinyapps.io/bayesian_blocks/)
  * [Bayesian Blocks with flat and linear block shapes](https://rshiroma.shinyapps.io/bayesianblocks/)
* [carma_pack tutorial](https://github.com/malgosias/carma_tutorial)

Some of the slide documents include links to other supporting material.



## Abstracts

### Time series exploration in Python and MATLAB: Bayesian blocks, periodograms, and all that

Tom Loredo (Cornell Center for Astrophysics and Planetary Science)
Jeffrey D. Scargle (NASA Ames Research Center)

This talk will open a Special Session, "Exploring time series data in high energy astrophysics," beginning with a brief survey of emerging software aiming to help astronomers explore and model diverse time series data.  We will then describe work from our Time Series Explorer (TSE) project, producing new algorithms and software in Python and MATLAB for exploratory analysis and statistical modeling of time series data. This talk will focus on software for parametric modeling via least squares/maximum likelihood/Bayesian approaches, and some specialized time series tools for handling unevenly sampled and point process data. We will also discuss some persistent misunderstandings about periodograms and Fourier power spectra, which can play multiple roles in parametric and nonparametric analyses of astronomical time series. Additional talks in the session will cover modeling AGN time series with stochastic process models, and modeling periodic, quasiperiodic and aperiodic variability in multichannel spectro-temporal data from X-ray binaries using cospectra and other tools.



### Time series exploration with Stingray: New tools for spectral-timing analysis of X-ray data

A. Stevens (Michigan State University & University of Michigan, Ann Arbor)

New ideas about how to analyze time-domain X-ray astronomy data have initiated the “spectral-timing revolution,” leading to a surge in developments of analysis techniques. Many individual tools and libraries exist, and some are even publicly available, but what has been lacking is a coherent set for a complete analysis. Stingray is a new community-developed, open-source software package in Python for spectraltiming analysis of astrophysical data. This software package provides the basis for developing spectral-timing analysis tools, while following the Astropy guidelines for modern open-source scientific programming. Our goal is to provide the community with a package that eases the learning curve for state-of-the-art spectral-timing techniques, with a correct statistical framework, to make maximal use of data from NuSTAR, NICER, and potentially STROBE-X and eXTP. In this talk, I will highlight the quasi-periodic oscillation (QPO) modeling and the cospectrum tools in the Stingray library using new NICER and NuSTAR data, respectively. For more information on Stingray, see: http://stingraysoftware.github.io/.



### Modeling time variability of AGN with the CARMA models

M. Sobolewska (Smithsonian Astrophysical Observatory)
A. Siemiginowska (Smithsonian Astrophysical Observatory)
J. Ryan (UCLA)

AGN emission is variable in all energy bands, from radio to X/gamma-rays. There is evidence that this variability is stochastic in nature. I will present a class of continuous-time autoregressive moving average models (CARMA; Kelly et al. 2014) as a tool to characterize the variability features of AGN light curves across the electromagnetic spectrum. The power spectral density (PSD) of a CARMA model can be expressed as a sum of Lorentzian functions, which makes the method extremely flexible and able to model a broad range of PSDs. The CARMA code is designed to deal with non-uniformly sampled, gappy data sets, and thus it is a perfect tool to quantify the time variability of astronomical time series. It has statistically rigorous foundation as it provides the likelihood function for light curves sampled from CARMA processes and relies on a Bayesian method to infer the probability distribution of the PSD given the measured light curve. In particular, CARMA modeling allows us to infer the PSD frequencies of spectral breaks and/or quasi periodic oscillations, if present. These PSD features are importants imprints of the physical processes generating the variability and/or the physical properties of the regions emitting the variable radiation, such as the region's size and location. I will discuss our most recent results on the time variability of the gamma-ray lightcurves of Fermi/LAT blazars and multiband light curves of the BL Lac object, OJ 287, obtained by utilizing the CARMA models.
