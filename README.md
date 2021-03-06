# Gammapy tutorial, Vaxjo, January 2020 - B. Khelifi, APC
Repository of the materials used for the gammapy tutorials made in Vaxjo, Sweden, in January 2020

## Table of contents
1. [Documentations](#doc)
2. [Analysis Overview](#ana)
    1. [Data format](#DL)
    2. [Data processing](#process)
    3. [TeV Background estimation](#bkg)
3. [Installation](#install)
4. [Astropy tutorial](#astropy)
5. [My first H.E.S.S. Crab analysis](#firstCrab)
6. [High Level Interface: an other way to analyse data](#HLI)
7. [Multi-wavelength analysis of the Crab](#jointCrab)
8. [An AGN analysis](#agn)
    1. [Making maps and get the position](#pos)
    2. [Spectra Extraction](#sp)
    3. [Light Curve](#lc)
9. [To contact the gammapy team](#contact)

## 1. Gammapy documentation and GitHub <a id="doc"></a>
* gammapy project webpage: https://gammapy.org/
* Github project: https://github.com/gammapy/gammapy

## 2. Analysis overview <a id="doc"></a>

### 2.1 Data format <a id="DL"></a>

![Data levels](figures/data_flow_full.png)

### 2.2 Data processing <a id="process"></a>

<img src="figures/data_flow_gammapy.png" width="50%">

### 2.3 TeV Background estimation <a id="bkg"></a>

<p float="left">
  <img src="figures/RadialAcceptance.png" width="30%">
  <img src="figures/BkgMaker.png" width="55%">
</p>
Caption: Acceptance of the residual hadronic background (left), Ring Background estimation (center), Reflected Background estimation (right) - Berge, Funk, Hinton, 2006, 
[arXiv:astro-ph/0610959](https://arxiv.org/abs/astro-ph/0610959v1)

## 3. Installation <a id="instal"></a>
* [Installation step (V0.15)](https://docs.gammapy.org/0.15/install/index.html)
* [Tutorials and their data](https://docs.gammapy.org/0.15/getting-started.html#download-tutorials)

## 4. Astropy tutorial <a id="astropy"></a>
[Units, Coordinates, Tables, FITS and WCS](https://github.com/Asterics2020-Obelics/School2019/blob/master/astropy/astropy_hands_on.ipynb)

## 5. My first H.E.S.S. Crab analysis <a id="firstCrab"></a>
[Link towards the notebook](notebooks/FirstCrab.ipynb)

Link towards the documentation notebook: https://docs.gammapy.org/0.15/notebooks/analysis_2.html

## 6. High Level Interface: an other way to analyse data <a id="HLI"></a>
The HLI is a supplementary interface allowing:
* configuration of an analysis from a YAML file, which allows the setup of analysis pipelines
* stable interface for the users, whatever the evolution of the low-level APIs
* usable via notebooks, python scripts (or [click](https://docs.gammapy.org/0.15/scripts/index.html?highlight=click) command lines)

API documentation of the HLI: [Link](https://docs.gammapy.org/0.15/analysis/index.html)

[Link towards the notebook](notebooks/HLI.ipynb)

Link towards the documentation notebook: https://docs.gammapy.org/0.15/notebooks/analysis_1.html

## 7. Multi-wavelength analysis of the Crab <a id="jointCrab"></a>

[Link towards the notebook](notebooks/analysis_mwl.ipynb)

Link towards the documentation notebook: https://docs.gammapy.org/0.15/notebooks/analysis_mwl.html?highlight=joint%20crab

## 8. An AGN analysis <a id="AGN"></a>
### 8.1 Making maps and get the position <a id="pos"></a>
[BkgModel vs RingBkg](https://docs.gammapy.org/0.15/notebooks/image_analysis.html)

### 8.2 Spectra Extraction <a id="sp"></a>
[1D analysis](https://docs.gammapy.org/0.15/notebooks/spectrum_analysis.html)

[3D analysis](https://docs.gammapy.org/0.15/notebooks/analysis_3d.html)


### 8.3 Light Curve <a id="lc"></a>

[1D analysis: notebooks/light_curve_flare.html](https://docs.gammapy.org/0.15/notebooks/light_curve_flare.html)

[With the Analysis class: 1D vs 3D](https://docs.gammapy.org/0.15/notebooks/light_curve.html)

## 9. To contact the gammapy team <a id="contact"></a>
* Mail: gammapy-cta-l@in2p3.fr
* Slack: https://gammapy.slack.com/archives/C0HP0KKL1
* Coordination Committee: GAMMAPY-COORDINATION-L@IN2P3.FR 
* Project managers:
    * Bruno Khelifi (APC, Paris): khelifi@in2p3.fr
    * Christopher van Eldik (ECAP, Erlangen): Christopher.van.Eldik@physik.uni-erlangen.de
* Lead Developers:
    * Axel Donath (MPIK, Heidelberg): axel.donath@mpi-hd.mpg.de
    * Régis Terrier (APC, Paris): terrier@apc.univ-paris7.fr
