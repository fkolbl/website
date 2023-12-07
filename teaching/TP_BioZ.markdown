---
layout: page
title: Teaching - Electronics S9 Introduction to Biosignals
permalink: /teaching/TP_BioZ/

cours: "/assets/pdf/cours_BioZ_etud.pdf"
TP: "/assets/pdf/TP_BioZ.pdf"
code: "/assets/code/TP_BioZ_code_etudiant.zip"
---

Les documents relatifs au cours sur la mesure et modélisation des bio-impédance sont :
- [le support de cours](/assets/pdf/cours_BioZ_etud.pdf),
- [le texte de TP](/assets/pdf/TP_BioZ.pdf),
- [le code Python de départ](/assets/code/TP_BioZ_code_etudiant.zip).

Le TP et en particulier le matériel utilisé repose sur des solutions *open science* (en particulier sur une carte de mesure de bio-impédance BIMMS) qui peuvent être consultées sur la [page suivante]({% link open_science/open_science.markdown %}). Si vous souhaitez installer les librairies sur votre ordinateur pour pouvoir effectuer le TP dessus, il vous faudra idéalement créer un environnement (*conda* ou autre) avec une version de *Python* supérieure à 3.7, contenant les *packages numpy, scipy et matplotlib* ainsi que deux bibliothèques open sources installable au moyen du gestionnaire de package *pip*:
- [Andi-py](https://pypi.org/project/andi-py/) permettant d'utiliser les oscilloscopes embarqués Analog Discovery 2,
- [BIMMS](https://pypi.org/project/bimms/) permettant de contrôler directement la carte de mesure de bio-impédance par des commandes haut-niveau.