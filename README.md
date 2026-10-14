# Xenon Isotope Filtering at the Kinematic Edge of Inelastic Dark Matter

This repository contains the numerical material accompanying the study:

**“Xenon Isotope Filtering at the Kinematic Edge of Inelastic Dark Matter.”**

The analysis investigates how small differences among xenon isotope masses can be strongly amplified when endothermic dark-matter scattering occurs close to the upper kinematic boundary of the Galactic velocity distribution.

## Contents

The repository includes:

- Jupyter notebook used for the numerical analysis
- Isotope-resolved minimum-speed calculations
- Helm form-factor weighting
- Kinematic-only and full isotope response fractions
- Dominant-isotope maps in the \((m_\chi,\delta)\) plane
- Natural versus isotope-modified xenon comparisons
- Halo-edge sensitivity analysis
- Numerical benchmark tables and CSV outputs

## Benchmark

The main benchmark used in the manuscript is

$$
m_\chi = 1.1~\mathrm{TeV},
\qquad
\delta = 365~\mathrm{keV}.
$$

The Standard Halo Model parameters are

$$
v_0 = 238~\mathrm{km\,s^{-1}},
\qquad
v_{\rm esc} = 544~\mathrm{km\,s^{-1}},
\qquad
v_E = 250.5~\mathrm{km\,s^{-1}}.
$$

## Main idea

Close to the kinematic endpoint,

$$
\eta(v_{\min}) \propto
\left(v_{\max}-v_{\min}\right)^2,
$$

so small isotope-dependent shifts in \(v_{\min}\) can generate large differences in the relative isotope response.

## Running the notebook

Open

```text
Xenon_Isotope_Filtering_5Figures_BOLD_LABELS_BLUE_MARKDOWN.ipynb
