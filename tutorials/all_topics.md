# Tutorial/Code list
Here you can find the complete list of available tutorials. Please refer to the section below for related materials for each tutorial.
* 1)[The 2018 Palu, Indonesia slow supershear earthquake](#palu)
* 2)[2D spectral element modelling of wave propagation in nonlinear media](#sem2dpack)
* 3)[1D-3C spectral element modelling of wave propagation in nonlinear media](#1d3csem)
* 4)[Modelling nonlinear soil behaviour on elementary level](#iwanelem)
* 5)[Finite-source model preparation for SEM3D ](#convertisseur)
* 6)[Using obspy to download seismic data](#obspy)


<a name="palu"></a>
## 1) The 2018 Palu, Indonesia slow supershear earthquake 
2D damage (low-velocity fault zone) model for dynamic rupture modelling in SEM2DPACK
* [Repository](https://github.com/elifo/damaged_fault)
* [Manual](https://github.com/elifo/damaged_fault/blob/master/README.md)
* Reference: Oral, Weng, & Ampuero, 2019, Does a damaged fault zone mitigate the near-field
landslide risk during supershear earthquakes?—Application to the 2018 magnitude 7.5
Palu earthquake, Geophysical Research Letters, [DOI](https://doi.org/10.1029/2019GL085649), [PDF (preprint)](https://eartharxiv.org/repository/view/638/)

<a name="sem2dpack"></a>
## 2) 2D spectral element modelling of wave propagation in nonlinear media
Spectral element modelling of 2D wave propagation including site effects
* Code [`SEM2DPACK`](https://github.com/jpampuero/sem2dpack/tree/iwan)
* Examples: coming soon
* References: 
    * Oral, Ayoubi, Ampuero, Asimaki, and Bonilla, Kathmandu Basin as a local modulator of seismic waves: 2-D modelling of non-linear site response under obliquely incident waves, [DOI](https://doi.org/10.1093/gji/ggac302) [PDF](https://eartharxiv.org/repository/view/2772/) 
    * Oral, Gélis and Bonilla, 2019, 2-D P-SV and SH spectral element modelling of seismic wave propagation in non-linear media with pore-pressure effects, Geophysical Journal International, [PDF](https://eartharxiv.org/repository/view/1954/) [DOI](https://doi.org/10.1093/gji/ggz041)
    * Phd Dissertation: [Oral (2016)](https://tel.archives-ouvertes.fr/tel-01562279)

<a name="1d3csem"></a>
## 3) 1D-3C spectral element modelling of wave propagation in nonlinear media
One-dimensional (1D) three-component (3C) spectral element modeling (SEM) of seismic wave propagation in nonlinear media with pore-pressure effects
* Code: [`1D3CSEM`](https://github.com/elifo/1D3CSEM)
* [Manual](https://github.com/elifo/1D3CSEM/blob/main/MANUAL/manual.pdf)
* [All examples](https://github.com/elifo/1D3CSEM/tree/main/EXAMPLES)
* References: 
    * Oral, Gélis, Bonilla, Delavaud, 2017, Spectral element modelling of seismic wave
propagation in visco-elastoplastic media including excess-pore pressure development,
Geophysical Journal International, [DOI](https://doi.org/10.1093/gji/ggx375), [PDF](https://eartharxiv.org/repository/view/1953/)
    * Phd Dissertation: [Oral (2016)](https://tel.archives-ouvertes.fr/tel-01562279)

<a name="iwanelem"></a>
## 4) Modelling nonlinear soil behaviour on elementary level
Elemantary code —no wave propagation— for Iwan model, used for testing nonlinear soil behaviour under dynamic loading
* Code: [`IWANelem`](https://github.com/elifo/IWANelem)
* Example list [here](https://github.com/elifo/IWANelem/blob/master/README.md)

<a name="convertisseur"></a>
## 5) Finite-source model preparation for SEM3D 
This repository includes the files necessary to prepare a finite source model that can be used as input for the 3D spectral element code of SEM3D (of Ecole Centrale Paris, IPGP and CEA).
* Code: [`Convertisseur`](https://github.com/elifo/Convertisseur)
* [Manual](https://github.com/elifo/Convertisseur/blob/master/DOC/manual.pdf)
* Reference: Oral, E., Gatti, F. and Lopez‐Caballero, F., 2018, June. 3d spectral element modeling of near source effects including kinematic rupture and finite-fault effects.


<a name="obspy"></a>
## 6) How to download seismic data by using obspy
Obspy is a cool tool that will make your life easier. Below are very simple examples:  
* Downloading IRIS data (US/CA arrays): [`link to notebook`](https://github.com/elifo/obspy_tutorials/blob/main/download_iris_data.ipynb)
* Downloading French data (public/private through EIDA): [`link to notebook`](https://github.com/elifo/obspy_tutorials/blob/main/download_french_data.ipynb)
* Processing mseed data and first plots: [`link to notebook`](https://github.com/elifo/obspy_tutorials/blob/main/process_mseed_data.ipynb)


## Coming soon
* Kinematic source modelling for offshore Martinique, the Lesser Antilles Subduction Zone
* Heterogeneous stress preparation for 3D fault medium
* How to use linear algebra for seismic source relocation
* How to apply high-frequency back-projection to an earthquake
