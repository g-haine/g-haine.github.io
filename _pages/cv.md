---
layout: archive
title: "Curriculum vitæ"
permalink: /cv/
author_profile: true
docx: false
pdf: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education  
---

* **Ph.D. in Applied Mathematics**, Université de Lorraine (France), 2012
  * Defended in October 2012, entitled [*Observateurs en dimension infinie. Application à l'étude de quelques problèmes inverses*]({{ base_path }}/files/downloads/these.pdf), under the supervision of [Karim Ramdani](https://karim-ramdani.perso.math.cnrs.fr/) and [Marius Tucsnak](https://www.math.u-bordeaux.fr/~mtucsnak/).
* **Master’s Degree in Applied Mathematics**, Université de Lorraine (France), 2009
* **Bachelor’s Degree in Applied Mathematics and Computer Science**, Université de Lorraine (France), 2006

## Work experience  
---

* **Since 2013 - Associate Professor**  
  *ISAE-SUPAERO - Université de Toulouse*  
  **Duties included:**  
  * Lectures, practical sessions, and tutorial classes  
  * Research project development and management  
  * Improvement and redesign of engineering programs  

* **2012--2013 - Research Assistant (ATER)**  
  *Université de Lorraine*  
  **Duties included:**  
  * Practical teaching at Mines de Nancy  
  * Tutorial classes at Université de Lorraine  

* **2009--2012 - PhD Student with Teaching Duties**  
  *Université de Lorraine*  
  **Duties included:**  
  * Practical teaching at Mines de Nancy  
  * Member of the INRIA outreach working group  
  * Webmaster of the PhD students' website of the laboratory  

## PhD advisor  
---

0. **Antoine Bendimerad-Hohl**: *Discrétisation structurée de systèmes Hamiltoniens à ports d'interaction implicites*. Supervised with Laurent Lefèvre and Denis Matignon. Started in October 2022, defense on November, the 5th.  
0. **Anass Serhani**: *Systèmes couplés d'EDPs, vus comme des systèmes Hamiltoniens à ports avec dissipation : Analyse théorique et simulation numérique*. Supervised with Denis Matignon. Started in October 2017, defense on September 2020, the 28th.  
0. **Guillaume Delay**: *Étude d'un problème d'interaction fluide-structure : modélisation, analyse, stabilisation et simulations numériques*. Supervised with Sylvain Ervedoza and Michel Fournié. Started in November 2015, defense on August 2018, the 31st.  
{: reversed="reversed"}

## Research projects
---

### Current

{% comment %} * 2027-2032 - **MISTICS** - *Modelling, Simulation and Control of Irreversible Thermodynamic Systems* - [ANR](https://anr.fr/) {% endcomment %}
* 2025-2029 - **SPHERE** - *Structure-preserving methods for heat and electromagnetics research* - [AID](https://www.defense.gouv.fr/aid) - **Coordinator**

### Past

0. 2021-2025 - [**IMPACTS**](https://impacts.ens2m.fr/) - *Implicit port Hamiltonian control systems* - [ANR](https://anr.fr/)
0. 2021-2023 - **FAMAS** - *Fast and accurate Maxwell solver* - [AID](https://www.defense.gouv.fr/aid)
0. 2016-2021 - [**INFIDHEM**](https://websites.isae-supaero.fr/infidhem/) - *Interconnected infinite-dimensional systems for heterogeneous media* - [ANR](https://anr.fr/)--[DFG](https://www.dfg.de/)
0. 2017 - **FUSION** - *Fluide-structure : interaction et observateur non-linéaire* - [CNRS-PEPS](https://www.cnrs.fr/)
0. 2016 - **OPIMF** - *Observateurs et problèmes inverses en mécanique des fluides* - [CNRS-PEPS](https://www.cnrs.fr/)
0. 2014-2016 - **CARPE** - *Contrôle actif robuste d'écoulement de plaque épaisse* - [Fondation STAE](https://fr.wikipedia.org/wiki/Fondation_Sciences_et_technologies_pour_l%27a%C3%A9ronautique_et_l%27espace)   
0. 2010-2012 - **IPPON** - *Identification pour les problèmes de propagation d'ondes* - [FRAE](https://www.fnrae.org/detail-projet?id_theme=8&id_projet=44)
{: reversed="reversed"}
  
## Service and leadership  
---

* **2015--2024 - In charge of the core Applied Mathematics course in the engineering program**  
* **2020--2023 - Elected faculty representative on the Board of Directors**  
* **2015--2021 - Elected faculty representative on the Education Council**  

## Publications  
---

{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
### {{ category[1].title }}
<ol reversed>
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single-cv.html %}
    {% endfor %}
      {% if title_shown %}
</ol>
      {% endif %}
  {% endfor %}
{% else %}
<ol reversed>
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ol>
{% endif %}

