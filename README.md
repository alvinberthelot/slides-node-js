# slides-node-js

Contenus textuels (et support diapositives PDF) pour apprendre à utiliser la pateforme Node.js.

L'apprentissage est découpé en plusieurs sections qu'il convient de parcourir de préférence dans cet ordre :

1. Node.js ([Fichier node-js-v1.0.0.pdf](https://github.com/alvinberthelot/slides-node-js/blob/master/node-js-v1.0.0.pdf))
2. Mocha ([Fichier node-js-mocha-v1.0.0.pdf](https://github.com/alvinberthelot/slides-node-js/blob/master/node-js-mocha-v1.0.0.pdf))


## Licence

[![Licence Creative Commons](http://i.creativecommons.org/l/by-sa/3.0/88x31.png)](http://creativecommons.org/licenses/by-sa/3.0/deed.fr)

Ce(tte) œuvre est mise à disposition selon les termes de la [Licence Creative Commons. Attribution - Partage dans les Mêmes Conditions 3.0 non transposé](http://creativecommons.org/licenses/by-sa/3.0/deed.fr).

Copyright (C) 2017 Alvin Berthelot.

### Explications licence CC BY-SA 3.0

Cette licence permet aux autres de remixer, arranger, et adapter votre œuvre, même à des fins commerciales, tant qu’on vous accorde le mérite en citant votre nom et qu’on diffuse les nouvelles créations selon des conditions identiques.

Cette licence est souvent comparée aux licences de logiciels libres, “open source” ou “copyleft”.

Toutes les nouvelles œuvres basées sur les vôtres auront la même licence, et toute œuvre dérivée pourra être utilisée même à des fins commerciales.

C’est la licence utilisée par Wikipédia ; elle est recommandée pour des œuvres qui pourraient bénéficier de l’incorporation de contenu depuis Wikipédia et d’autres projets sous licence similaire.

### Contribution et réappropriation

Le fichier PDF est généré avec Asciidoctor à partir de ce dépôt Git.

Cela signifie que vous n’avez pas besoin de vous battre avec un fichier binaire (le PDF) pour contribuer, vous réapproprier le contenu ou modifier le thème de présentation.

## Générer le PDF

Cloner ce dépôt Git

	git clone https://github.com/alvinberthelot/slides-node-js

Cloner le dépôt Git Asciidoctor-pdf pour générer le PDF

	git clone https://github.com/asciidoctor/asciidoctor-pdf

Générer le PDF

	cd slides-js
	ruby ../asciidoctor-pdf/bin/asciidoctor-pdf

