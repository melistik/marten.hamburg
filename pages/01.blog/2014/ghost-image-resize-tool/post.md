---
title: "ghost image resize tool"
slug: "ghost-image-resize-tool"
date: 6.11.2014 23:35:00
image: "ghost-image-resize.png"
taxonomy:
    category: blog
    tag: ["Website", "Tech"]
---

Bei der Umstellung meines Blog's auf [ghost](https://github.com/TryGhost/Ghost) ist mit sehr schnell aufgefallen, dass die Möglichkeit fehlt Bilder entsprechend ihres Layouts in verschiedene Größen darstellen zu können. Nach ein wenig Recherche nach einem passenden Tools hierzu ohne Erfolg habe ich kurzerhand eine kleines PHP-Script selbst geschrieben. Dies möchte ich auf diesem Wege mit euch teilen, da mir aufgefallen ist, dass sehr viele diese Feature sich von ghost wünschen. Es ist zwar auf der Roadmap doch wann es genau umgesetzt wird ist unbekannt.

Es basiert primär auf Mod-Rewrite, welches Requests auf die Original-Bilder durch ein intelligentes Script schleust und dieses on the fly das Bilder verkleinert und entsprechend ausgibt. Das ist auch schon die gesamte Magie, doch hierdurch muss das Theme nur geringfügig angepasst werden und auf es kann auf spezielle HTML-Tags im Blogbeitrag verzichtet werden. Die Details zur Benutzung habe ich auf [Github](https://github.com/melistik/ghost-image-resize) beschrieben. Dort findet ihr auch das Script zur eigenen Verwendung. 

Über Feedback hierzu würde ich mich sehr freuen.
