---
permalink: /
title: "About me"
author_profile: true
redirect_from:  
  - /about/
  - /about.html
---
---

**Science is in danger, please take a look at this [petition](https://framapetitions.org/petition/user/science.peace/open-letter-to-protect-educational-and-scientific-institutions-in-times-of-conflict).**

---

Since April 2013, I am Associate Professor in the department DISC of [ISAE-SUPAERO](https://www.isae-supaero.fr/).  

I defended my PhD Thesis on October 2012, the 22nd, entitled *Observateurs en dimension infinie. Application à l’étude de quelques problèmes inverses*, under the supervision of [Karim Ramdani](https://karim-ramdani.perso.math.cnrs.fr/) and [Marius Tucsnak](https://www.math.u-bordeaux.fr/~mtucsnak/). I focused on inverse problems for linear systems using the observers-based algorithm introduced by Ramdani, Tucsnak and Weiss (*Recovering the initial state of an infinite-dimensional system using observers*, Automatica, vol. 46, pp. 1616-1625, 2010). Such problems arise for instance in medical imaging, meteorology, source identification and much more.  

Since then, I worked on modeling, control and discretization of Partial Differential Equations, mainly in the port-Hamiltonian framework.  

## Latest Publications

<ul>
{% assign filtered = site.publications | where: "category", "manuscripts" %}
{% assign sorted = filtered | sort: "date" | reverse %}
{% for post in sorted limit:2 %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

## Current projects in development

I am working on a collection of python methods and classes in the [SCRIMP project](https://github.com/g-haine/scrimp), intended to speed up the coding process of structure-preserving discretization of port-Hamiltonian systems.

I also developped [BibReview](https://g-haine.github.io/bibreview/) -- a configurable bibliographic review engine for collecting, curating, and publishing scholarly literature as static websites -- and maintain the bibliographic database about port-Hamiltonian systems [PHRAISE](https://g-haine.github.io/phraise/) as a demonstrator.

## Some useful CLI snippets

* [**doi2bib**](https://gitlab.isae-supaero.fr/-/snippets/10/): to format a bibtex entry from a DOI.
* [**getDOI**](https://gitlab.isae-supaero.fr/-/snippets/11/): to find a DOI from keywords.
* [**reduce**](https://gitlab.isae-supaero.fr/-/snippets/13/): to reduce the size of a pdf.
