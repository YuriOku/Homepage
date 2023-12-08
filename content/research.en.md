---
title: "Research"
date: 2020-05-07T18:54:23+09:00
---

## Publications

[My Publications - NASA ADS Library](https://ui.adsabs.harvard.edu/public-libraries/nh_1-GaxRliz19Uv7IJ2XA)

## Research

I am studying galaxy formation using numerical simulations.
My research field ranges from the scale of interstellar medium to the large-scale structure of the universe.
{{< figure src="/media/researchfield.png" title="Left: Superbubble formed by multiple supernova explosions simulated with Athena++ (Stone et al. 2020); Center: Milky-Way-mass isolated galaxy simulated with GADGET3-Osaka (Shimizu et al. 2019, Oku et al. 2022); Right: The formation of the large scale structure of the universe simulated with GADGET3-Osaka" width=100% >}}

### Modeling Supernova Feedback (Oku et al. 2022)
In our paper ["Osaka Feedback Model II: Modeling Supernova Feedback Based on High-Resolution Simulations"](https://arxiv.org/abs/2201.00970), I worked on modeling the supernova feedback for galaxy simulations. We studied the momentum of superbubbles formed by multiple supernovae, and applied it to our feedback model. We modeled both kinetic and thermal feedback effects by supernovae, which is necessary to reproduce the two key roles of the supernova feedback: regulating local star formation and driving the galactic wind.

The video below shows the density-weighted gas density, temperature, and metallicity of five isolated galaxies simulated with different stellar feedback models in face-on view. The Fiducial run includes both kinetic and thermal feedback models. We use a stochastic thermal feedback model to reproduce the hot bubbles by supernovae, and we see bright points in the temperature plot.
The Non-stochastic run also includes both kinetic and thermal feedback, but thermal feedback is not stochastic. Such a simple "thermal bomb" is known to be subjected to the "overcooling problem" due to the lack of the resolution to resolve the cooling mass.
The SNII-kinetic and SNII-thermal runs are simulations with only kinetic and thermal feedback from Type II supernovae, and NoFB run is a simulation without feedback. In runs with kinetic feedback (Fidicial, Non-stochastic, and SNII-kinetic), the turbulence driven by kinetic feedback maintains their gas disks against gravitational collapse while the other galaxies become clumpy.

{{< youtube eJUKijc57AE>}}
This movie can be downloaded [here](https://www.dropbox.com/scl/fi/t87s2j95znsdehxxtl94j/faceon.mp4?rlkey=rofltg97endy91raqglm8vi4b&dl=0)
