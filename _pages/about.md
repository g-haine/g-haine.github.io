---
permalink: /
title: "About me"
author_profile: true
redirect_from:  
  - /about/
  - /about.html
---

Since April 2013, I am Associate Professor in the department DISC of [ISAE-SUPAERO](https://www.isae-supaero.fr/).  

I defended my PhD Thesis on October 2012, the 22nd, entitled `Observateurs en dimension infinie. Application à l’étude de quelques problèmes inverses`, under the supervision of [Karim Ramdani](https://karim-ramdani.perso.math.cnrs.fr/) and [Marius Tucsnak](https://www.math.u-bordeaux.fr/~mtucsnak/). I focused on inverse problems for linear systems using the observers-based algorithm introduced by Ramdani, Tucsnak and Weiss (*Recovering the initial state of an infinite-dimensional system using observers*, Automatica, vol. 46, pp. 1616-1625, 2010). Such problems arise for instance in medical imaging, meteorology, source identification and much more.  

Since then, I worked on modeling, control and discretization of Partial Differential Equations, mainly in the port-Hamiltonian framework.  

## Latest Publications

<ul>
{% assign filtered = site.publications | where: "category", "manuscripts" %}
{% assign sorted = filtered | sort: "date" | reverse %}
{% for post in sorted limit:2 %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

## Current projects

* [PHRAISE](https://g-haine.github.io/phraise/): **P**ort-**H**amiltonian **R**epresentation and **A**pproximation of **I**nterconnected **S**ystems using **E**nergy is a bibliographical survey attempt about port-Hamiltonian researches, both on the theoretical and the numerical sides.  
* [SCRIMP](https://g-haine.github.io/scrimp/): **S**imulation and **C**ont**R**ol of **I**nteractions in **M**ulti-**P**hysics is a python collection, namely a *package*, of methods and classes for the structure-preserving discretization and simulation of multi-physics models, using the formalism of port-Hamiltonian systems.  

## PhD advisor

* **Guillaume Delay**: *Étude d'un problème d'interaction fluide-structure : modélisation, analyse, stabilisation et simulations numériques*. Supervised with Sylvain Ervedoza and Michel Fournié. Started in November 2015, defense on August 2018, the 31st.  
* **Anass Serhani**: *Systèmes couplés d'EDPs, vus comme des systèmes Hamiltoniens à ports avec dissipation : Analyse théorique et simulation numérique*. Supervised with Denis Matignon. Started in October 2017, defense on September 2020, the 28th.  
* **Antoine Bendimerad-Hohl**: *Discrétisation structurée de systèmes Hamiltoniens à ports d'interaction implicites*. Supervised with Laurent Lefèvre and Denis Matignon. Started in October 2022, defense on November, the 5th.  

