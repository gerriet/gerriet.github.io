---
layout: single
title: "Eine andere Art ein Blog oder eine Webseite aufzubauen: Jekyll"
# permalink: andere-art-zu-bloggen-mit-jekyll
---
_Oder: es muss nicht immer Wordpress sein_

Vielen fällt als erstes [Wordpress](http://wordpress.org) ein, wenn es darum geht, eine Webseite zu bauen. [Ungeheuer viele Seiten](https://www.codeinwp.com/blog/wordpress-statistics/) sind darauf aufgebaut. Es ist ein sehr mächtiges und allgemeines Werkzeug, das man mit einer großen Zahl von Themes und Plugins auf seinen eigenen Bedarf zurecht konfigurieren kann. Aber für viele Aufgaben ist es damit nicht der beste und vor allem nicht der einfachste Ansatz. Auf der Suche nach einer guten Lösung für mich bin ich auf [Jekyll](jekyllrb.com) gestoßen. 

Im Gegensatz zu Wordpress und ähnlichen CMS (Content Management Systemen) wie Typo3, Joomla oder Drupal ist Jekyll ein statischer Seitengenerator. Es produziert also aus dem Geschriebenen _einfache_ HTML-Seiten, die der Webserver dann zum Browser schicken kann, während bei dynamischen CMS jede Seite aus Informationen zusammengesetzt wird, die bei jedem Request aus einer Datenbank geholt werden müssen und per Skript zu der jeweiligen HTML-Seite zusammengeführt werden. Braucht man diese Dynamik, ist Jekyll der falsche Weg. Wenn man jedoch tatsächlich eine eher statische Webseite braucht - und das kann auch heissen, dass ein Blog auf dieser Seite präsentiert wird - bietet sich Jekyll förmlich an.

Den Anfänger verwirrt eventuell, dass man Jekyll auf unterschiedliche Art und Weise betreiben kann: Jekyll kann entweder nur dann in Aktion treten, wenn sich am Inhalt oder Layout der Seite etwas ändert und neue HTML-Seiten produziert werden müssen, aber Jekyll kann auch selbst die Seiten "serven" und also die Aufgabe eines Webservers wie Apache oder nginx mit übernehmen. Und dann gibt es da noch die geek-freundliche Kombination von Jekyll mit git. 

In diesem Artikel geht es um die Erstellung einer Webseite mit "angehängtem" Blog, die sich in freundlichem [Markdown](https://daringfireball.net/projects/markdown/) schreiben lassen. 

Auch wenn man direkt mit _purem_ Jekyll anfangen kann, vereinfacht man sich doch einiges, wenn man vorab ein Theme wählt, z.B. von [jekyllthemes](http://jekyllthemes.org). 