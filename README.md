---
layout: pages
title: "État et révolution numérique"
---

# État et révolution numérique

### Bienvenue

Ce site est dédié à l'enseignement &laquo;&nbsp;*État et révolution
numérique*&raquo;&nbsp; proposé aux élèves du Master d'affaires
publiques de [SciencesPo Paris][iep] dans le cadre d'une conférence de
méthode de 12&nbsp;séances. Il a vocation à être collaboratif, tout
son contenu étant déposé dans le domaine public.

En somme, ce site deviendra ce que vous en ferez&nbsp;!

Cette page d'accueil explique le fonctionnement de ce site collaboratif et renvoie vers les contenus intéressant chacune des séances de la conférence.

### Une difficulté ?

Si vous ne sortez vraiment pas, regardez la <a href="http://help.github.com/pages">documentation GitHub</a> et collaborez avec les membres de la conférence. En dernier recours, adressez-vous à vos enseignants.

### Derniers billets publiés

 <table class="noborder">
    {% for post in site.posts %}

  <tr>
   <td class="noborder"><span>{{ post.date | date_to_string }}</span></td>
   <td class="noborder">
    <div><a href="{{ post.url }}">{{ post.title }}</a></div>
    <div>({{ post.tags | join: ', ' }})</div>
    </td>
  </tr>

    {% endfor %}
  </table>

[iep]: http://www.sciences-po.fr
