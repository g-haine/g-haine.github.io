---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* **Ph.D. in Applied Mathematics**, Université de Lorraine (France), 2012
* **Master’s Degree in Applied Mathematics**, Université de Lorraine (France), 2009
* **Bachelor’s Degree in Applied Mathematics and Computer Science**, Université de Lorraine (France), 2006

## Work experience

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

## Publications

### Journal Articles

  <ol reversed>
  {% assign filtered = site.publications | where: "category", "manuscripts" %}
  {% assign sorted = filtered | sort: "date" | reverse %}
  {% for post in sorted %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ol>
  
### Conference Papers

  <ol reversed>
  {% assign filtered = site.publications | where: "category", "conferences" %}
  {% assign sorted = filtered | sort: "date" | reverse %}
  {% for post in sorted %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ol>
  
## Teaching

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## PhD advisor

* **Antoine Bendimerad-Hohl**: *Discrétisation structurée de systèmes Hamiltoniens à ports d'interaction implicites*. Supervised with Laurent Lefèvre and Denis Matignon. Started in October 2022, defense on November, the 5th.  
* **Anass Serhani**: *Systèmes couplés d'EDPs, vus comme des systèmes Hamiltoniens à ports avec dissipation : Analyse théorique et simulation numérique*. Supervised with Denis Matignon. Started in October 2017, defense on September 2020, the 28th.  
* **Guillaume Delay**: *Étude d'un problème d'interaction fluide-structure : modélisation, analyse, stabilisation et simulations numériques*. Supervised with Sylvain Ervedoza and Michel Fournié. Started in November 2015, defense on August 2018, the 31st.  
  
## Service and leadership

* **2015--2024 - In charge of the core Applied Mathematics course in the engineering program**  
* **2019--2023 - Elected faculty representative on the Board of Directors**  
* **2015--2023 - Elected faculty representative on the Education Council**  

