---
layout: exercices
---

## MARSHAL

Example d'exercie pour le modèle [MARSHAL](https://plantmodelling.shinyapps.io/marshal/). Exemple créé par Valentin Couvreur et Valentine Calay (Faculté des bio-ingénieurs, UCL)

<span style="color: red;"><i class="fab fa-youtube"></i></span> Petite vidéo explicative sur MARSHAL:

<div class="video-container"><iframe width="100%" src="http://www.youtube.com/embed/Y_qlC08hj88" frameborder="0" allowfullscreen></iframe></div>

#### The context

Following the success of your research on the root permeability of millet, Syngenta hires you as a consultant to integrate the "root hydraulics" component into soybean ideotypes (Glycine max). An ideotype is a conceptual plant that brings together the characteristics (or traits) ideally suited to a soil x climate combination.

#### Root traits:

Syngenta would like to test a priori the drought tolerance of future soybean varieties with increased root radial conductivity (0.000281 instead of 0.000181 cm hPa-1 d) in the young area of each root type (0 -> 9 cm from the tip). These features are called *RT* (high radial conductivity in young taproot tissue), *RLL* (high radial conductivity in young long lateral root tissue), and *RL* (high radial conductivity in young lateral root tissue).

Varieties with early maturity of the root xylem can also be selected. These have an axial conductance multiplied by 10, 9 cm from the tip of the root. These features are called *XT* (high axial conductance in young taproot tissue), *XLL* (high axial conductance in young long lateral root tissue), and *XL* (high axial conductance in young lateral root tissue).

#### The environment:

Soil evaporation in the arid climate of the Negev Desert generates a water potential on the soil surface of -15000 hPa ("permanent wilting point"), but the underground microirrigation system linearly increases the water potential to -300 hPa ("field capacity") at 40 cm depth. Drainage naturally stabilizes this potential at -300 hPa below 40 cm.


#### Questions :

- For the default root system, what are the root types that absorb the most water (root depth profile / radial fluxes tab), and what is the root type that carries the most water in its xylem (root depth profile / axial fluxes tab)?

- Under the evolution / Transpiration simulations tab, you can see how the water availability for the plant (considered equivalent to its transpiration) responds to the environment and root traits. Among the features *XT*, *XLL*, and *XL* (modified one by one), which is the most promising to increase water availability? Interpret.

- Among the traits *RT*, *RLL*, and *RL*, which most increases water availability for the plant? Interpret.

- You can now conclude which radial and axial conductivity traits should be selected as a priority for your ideotype. 

- How does the water availability for this ideotype evolve in the presence of a surface micro-irrigation system (water potential of -300 hPa at the surface, decreasing linearly to reach -20000 hPa at 40 cm depth, and keeping this value of -20000 hPa at greater depth)? 

- Under these conditions, what is the water availability of the initial variety compared to the variety with the *RT* trait? Interpret. 

<hr>
**A hybrid analytical-numerical method for solving water flow equations in root hydraulic architectures.** 
<br>
Meunier F, Draye X, Vanderborght J, Javaux M, Couvreur V.  

<a class="btn btn-outline-primary btn-sm mb-1" href="https://paperpile.com/shared/pqeFaT" target="_blank"><i class="fal fa-newspaper"></i> Article</a>
<a class="btn btn-outline-success btn-sm mb-1" href="https://marshal-root.github.io/" target="_blank"><i class="fal fa-link"></i> Website</a>
<hr>