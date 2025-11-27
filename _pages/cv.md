---
layout: archive
title: "Curriculum vitæ"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education  
---

* **Ph.D. in Applied Mathematics**, Université de Lorraine (France), 2012
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

## PhD advisor  
---

0. **Antoine Bendimerad-Hohl**: *Discrétisation structurée de systèmes Hamiltoniens à ports d'interaction implicites*. Supervised with Laurent Lefèvre and Denis Matignon. Started in October 2022, defense on November, the 5th.  
0. **Anass Serhani**: *Systèmes couplés d'EDPs, vus comme des systèmes Hamiltoniens à ports avec dissipation : Analyse théorique et simulation numérique*. Supervised with Denis Matignon. Started in October 2017, defense on September 2020, the 28th.  
0. **Guillaume Delay**: *Étude d'un problème d'interaction fluide-structure : modélisation, analyse, stabilisation et simulations numériques*. Supervised with Sylvain Ervedoza and Michel Fournié. Started in November 2015, defense on August 2018, the 31st.  
{: reversed="reversed"}
  
## Teaching  
---

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Service and leadership  
---

* **2015--2024 - In charge of the core Applied Mathematics course in the engineering program**  
* **2020--2023 - Elected faculty representative on the Board of Directors**  
* **2015--2021 - Elected faculty representative on the Education Council**  

