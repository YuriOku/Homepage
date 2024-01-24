---
title: "Research"
date: 2020-05-07T18:54:23+09:00
---

## Publications

[My Publications - NASA ADS Library](https://ui.adsabs.harvard.edu/public-libraries/nh_1-GaxRliz19Uv7IJ2XA)

## Research

I am studying galaxy formation using numerical simulations.
My research field ranges from the scale of interstellar medium to the large-scale structure of the universe.
{{< myimg src="/media/researchfield.png" title="Left: Superbubble formed by multiple supernova explosions simulated with Athena++ (Stone et al. 2020); Center: Milky-Way-mass isolated galaxy simulated with GADGET3-Osaka (Shimizu et al. 2019, Oku et al. 2022); Right: The formation of the large scale structure of the universe simulated with GADGET3-Osaka" width="100%" >}}

### Cosmological Hydrodynamical Simulations (Oku and Nagamine submitted)
In our paper ["Osaka Feedback Model III: Cosmological Simulation CROCODILE"](https://arxiv.org/abs/2401.06324), we updated our supernova feedback model developed in [Oku et al. (2022)](https://ui.adsabs.harvard.edu/abs/2022ApJS..262....9O/abstract) and performed a suite of full-box cosmological simulations CROCODILE (Cosmological hydROdynamical simulation of struCture fOrmation and feeDback physIcs in gaLaxy Evolution), named in homage to [Osaka University’s official mascot, Dr. Wani](https://www.osaka-u.ac.jp/sp/drwani/en/), a crocodile.
Our CROCODILE simulation is executed using GADGET4-Osaka SPH code and incorpolates feedback from supernova (SN) and active galactic nuclei (AGN). 
A key innovation in our SN feedback model is the integration of a metallicity- and redshift-dependent, top-heavy IMF, which enables a higher energy injection rate per unit stellar mass formed at high redshift.

{{< youtube va60KPnOFXQ>}}
{{< centering class="mov-link" link="https://www.dropbox.com/scl/fi/tm6lecrtaar61x0xox11t/CROCODILE_density.mp4?rlkey=cu45cd5frztmbms9h9mvfgbn9&dl=0" >}}
This movie can be downloaded here
{{< /centering >}}

In the paper, we show that our CROCODILE simulation reproduces the observed galaxy stellar mass function (GSMF) and investigate the impact of SN and AGN feedback on the metal enrichment of the intergalactic medium (IGM).
The movie below shows the density-weighted metallicity projection of the CROCODILE simulation.
We find that the SN feedback is a key driver in the chemical enrichment of the IGM.
Additionally, the AGN feedback creates metal-rich, bipolar outflows that extend and enrich the CGM and IGM over a few Mpc scales.

{{< youtube fgAIcF2vGbY>}}
{{< centering class="mov-link" link="https://www.dropbox.com/scl/fi/8ss2farurrxrt8chngmfy/CROCODILE_metallicity.mp4?rlkey=t9niy3yqol8sg6ydcijz1tkdn&dl=0" >}}
This movie can be downloaded here
{{< /centering >}}

### Modeling Supernova Feedback (Oku et al. 2022)
In our paper ["Osaka Feedback Model II: Modeling Supernova Feedback Based on High-Resolution Simulations"](https://ui.adsabs.harvard.edu/abs/2022ApJS..262....9O/abstract), I worked on modeling the supernova feedback for galaxy simulations. We studied the momentum of superbubbles formed by multiple supernovae, and applied it to our feedback model. We modeled both kinetic and thermal feedback effects by supernovae, which is necessary to reproduce the two key roles of the supernova feedback: regulating local star formation and driving the galactic wind.

The video below shows the density-weighted gas density, temperature, and metallicity of five isolated galaxies simulated with different stellar feedback models in face-on view. The Fiducial run includes both kinetic and thermal feedback models. We use a stochastic thermal feedback model to reproduce the hot bubbles by supernovae, and we see bright points in the temperature plot.
The Non-stochastic run also includes both kinetic and thermal feedback, but thermal feedback is not stochastic. Such a simple "thermal bomb" is known to be subjected to the "overcooling problem" due to the lack of the resolution to resolve the cooling mass.
The SNII-kinetic and SNII-thermal runs are simulations with only kinetic and thermal feedback from Type II supernovae, and NoFB run is a simulation without feedback. In runs with kinetic feedback (Fidicial, Non-stochastic, and SNII-kinetic), the turbulence driven by kinetic feedback maintains their gas disks against gravitational collapse while the other galaxies become clumpy.

{{< youtube eJUKijc57AE>}}
{{< centering class="mov-link" link="https://www.dropbox.com/scl/fi/t87s2j95znsdehxxtl94j/faceon.mp4?rlkey=rofltg97endy91raqglm8vi4b&dl=0" >}}
This movie can be downloaded here
{{< /centering >}}
