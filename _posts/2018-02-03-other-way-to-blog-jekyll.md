---
layout: single
title: "Eine andere Art, eine Webseite aufzubauen: Jekyll"
permalink: andere-art-zu-bloggen-mit-jekyll
date: 2018-02-03 19:00:00 +0200
categories: technology
keywords: jekyll web
header:
    og_image: /assets/images/jekyll-logo-2x.png
---
_Oder: es muss nicht immer Wordpress sein_

Vielen fällt als erstes [Wordpress](http://wordpress.org) ein, wenn es darum geht, eine Webseite oder ein Blog zu bauen. [Ungeheuer viele Seiten](https://www.codeinwp.com/blog/wordpress-statistics/) sind darauf aufgebaut. Es ist ein sehr mächtiges und allgemeines Werkzeug, das man mit einer großen Zahl von Themes und Plugins auf seinen eigenen Bedarf zurecht konfigurieren kann. Aber für viele Aufgaben ist es damit nicht der beste und vor allem nicht der einfachste Ansatz. Auf der Suche nach einer guten Lösung für mich bin ich auf [Jekyll](https://jekyllrb.com) gestoßen. 

![Jekyll logo](/assets/images/jekyll-logo-2x.png)

Im Gegensatz zu Wordpress und ähnlichen CMS (Content Management Systemen) wie [Typo3](https://typo3.org/), [Joomla](https://www.joomla.org/) oder [Drupal](https://www.drupal.org/) ist Jekyll ein statischer Seitengenerator. Es produziert also aus dem Geschriebenen _einfache_ HTML-Seiten, die der Webserver dann zum Browser schicken kann, während bei dynamischen CMS jede Seite aus Informationen zusammengesetzt wird, die bei jedem Request aus einer Datenbank geholt werden müssen und per Skript zu der jeweiligen HTML-Seite zusammengeführt werden. Braucht man diese Dynamik, ist Jekyll der falsche Weg. Wenn man jedoch tatsächlich eine eher statische Webseite braucht - und das kann auch heißen, dass ein Blog auf dieser Seite präsentiert wird - bietet sich Jekyll förmlich an.

Den Anfänger verwirrt eventuell, dass man Jekyll auf unterschiedliche Art und Weise betreiben kann: Jekyll kann entweder nur dann in Aktion treten, wenn sich am Inhalt oder Layout der Seite etwas ändert und neue HTML-Seiten produziert werden müssen, aber Jekyll kann auch selbst die Seiten _serven_ und also die Aufgabe eines Webservers wie Apache oder nginx mit übernehmen. Und dann gibt es da noch die geek-freundliche Kombination von Jekyll mit git. Doch all diese Möglichkeiten der Verwendung sind eigentlich nicht entscheidend, es geht darum, dass man seine Inhalte in einer freundlichen Form schreiben kann ([Markdown][markdown], Liquid, HTML und CSS) und Jekyll produziert daraus eine Webseite inklusive Blog. 

Und die produzierte Seite braucht keine Datenbank und kann auf jedem beliebigen Webserver gehostet werden. Damit läuft auf dem von außen erreichbaren Server viel weniger sicherheitskritische Software. Auf dem eigenen lokalen Computer lässt sich umfangreich experimentieren und ausprobieren bevor man Änderungen auf den Server hochlädt. Durch die einfache Struktur werden auch Dinge wie Datensicherung, Versionierung und Umzug stark vereinfacht.

Wenn Jekyll so viele Vorteile hat, warum nutzt es dann nicht jeder? Nun, es wird tatsächlich oft eingesetzt, auch für komplexere Projekte wie [micro.blog](https://micro.blog). Zum anderen gibt es die kleine Hürde, dass für das Einrichten und Benutzen von Jekyll ein wenig an der Kommandozeile gearbeitet werden muss (es sei denn man setzt [Jekyll Admin](https://github.com/jekyll/jekyll-admin) ein). Es braucht zwar nur einige wenige Kommandos, aber hier werden doch sicher einige abgeschreckt. 

Für alle, die das zumindest nicht definitiv für sich ausschließen, werde ich in den nächsten Wochen eine kleine Artikelreihe zum Start mit Jekyll schreiben. 

[markdown]: https://daringfireball.net/projects/markdown/
