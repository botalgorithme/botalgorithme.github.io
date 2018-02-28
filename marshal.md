---
layout: exercices
title: MARSHAL
---

## MARSHAL

Example d'exercie pour le modèle [MARSHAL](https://plantmodelling.shinyapps.io/marshal/). Exemple créé par Valentin Couvreur et Valentine Calay (Faculté des bio-ingénieurs, UCL)

<span style="color: red;"><i class="fab fa-youtube"></i></span> Petite vidéo explicative sur l'emplois de MARSHAL:

<div class="video-container"><iframe width="100%" src="http://www.youtube.com/embed/Y_qlC08hj88" frameborder="0" allowfullscreen></iframe></div>

### Le contexte

Suite au succès de vos recherches sur la perméabilité racinaire du mil, Syngenta vous engage comme consultant pour intégrer la composante « hydraulique de la racine » dans les idéotypes de soja (Glycine max). Un idéotype est une plante conceptuelle rassemblant les caractéristiques (ou traits) idéalement adaptés à une combinaison sol x climat.

### Les traits racinaires :

Syngenta voudrait tester à priori la tolérance à la sécheresse de futures variétés de soja dont la conductivité radiale racinaire est augmentée (0.000281 au lieu de 0.000181 cm hPa-1 j) dans la zone jeune de chaque type de racines (0 -> 9 cm de l’extrémité). Ces traits sont appelés *RT* (high radial conductivity in young taproot tissue), *RLL* (high radial conductivity in young long lateral root tissue), et *RL* (high radial conductivity in young lateral root tissue).

Des variétés à maturité précoce du xylème racinaire peuvent également être sélectionnées. Celles-ci ont une conductance axiale multipliée par 10, à 9 cm de la pointe de la racine. Ces traits sont appelés *XT* (high axial conductance in young taproot tissue), *XLL* (high axial conductance in young long lateral root tissue), et *XL* (high axial conductance in young lateral root tissue).

### L’environnement :

L’évaporation du sol sous le climat aride du désert du Negev génère un potentiel de l’eau à la surface du sol de -15000 hPa (« point de flétrissement permanent »), mais le système de micro-irrigation sous-terrain augmente le potentiel de l’eau linéairement jusqu’à atteindre -300 hPa (« capacité au champ ») à 40 cm de profondeur. Le drainage stabilise naturellement ce potentiel à -300 hPa sous 40 cm.


### Questions :

-	Pour le système racinaire par défaut, quels sont les types racinaires absorbant le plus d’eau (onglet root depth profile / radial fluxes), et quel est le type racinaire transportant le plus d’eau dans son xylème (onglet root depth profile / axial fluxes) ?

-	Sous l’onglet simulations evolution / Transpiration, vous pouvez voir comment la disponibilité en eau pour la plante (considérée équivalente à sa transpiration) répond à l’environnement et aux traits racinaires. Parmi les traits *XT*, *XLL*, et *XL* (modifiés un à un), lequel est le plus prometteur pour augmenter la disponibilité en eau ? Interprétez.

-	Parmi les traits *RT*, *RLL*, et *RL*, lequel augmente le plus la disponibilité en eau pour la plante ? Interprétez.

-	Vous pouvez maintenant conclure quels sont les traits de conductivité radiale et de conductance axiale qui doivent être sélectionnés en priorité pour votre idéotype. 

- Comment évolue la disponibilité en eau pour cet idéotype en présence d’un micro-irrigateur de surface (potentiel de l’eau de -300 hPa en surface, décroissant linéairement pour atteindre -20000 hPa à 40 cm de profondeur, et gardant cette valeur de -20000 hPa plus en profondeur) ? 

- Dans ces conditions, quelle est la disponibilité en eau de la variété initiale par rapport à celle portant le trait *RT* ? Interprétez.

