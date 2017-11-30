# Corpus de fragments de Garin le Loherain
Il s'agira de CapiTainSiser les documents, après avoir,
- encodé les métadonnées des documents (teiHeader);
- rendu la structure générale (front/body/back) des textes, ainsi que le gros de leur structure logique,
vers et laisses (i.e. strophes), notes ;
- l'encodage des corrections, résolutions d'abréviations, etc., serait apprécié, mais n'est pas obligatoire ;
- la segmentation des mots *n'est pas* demandée ; ce travail sera délégué à une XSLT, et, si vous voulez l'intégrer à votre travail, je la ferai tourner pour vous ;
- pour la numérotation (automatique) des vers, une XSL (et de l'aide si besoin) sera mise à votre disposition.

Dans CapiTainS, un système de référence aux vers seuls (éventuellement aux mots) sera demandé.

Pour vous aider, vous avez:
1. un exemple de fragment encodé dans le dossier exemple, ainsi que la documentation en html et le schema (dossier ODD) ;
2. par rapport à cet exemple, je ne vous demande pas de faire la segmentation par mots (w) ;
3. je suis disponible pour suivre votre travail et surtout pour répondre à toutes les questions sur le modèle XML ou le reste.
4. les métadonnées nécessaires sont dans le fichier csv. Vous n'avez qu'à traiter les fragments de Garin, mais, si vous le souhaitez, il y a deux ou trois courts fragments «bonus» qui peuvent être faits en plus (rien d'obligatoire), tirés des mêmes articles.

Dernière remarque: je n'ai mis qu'un seul corpus de fragments (corpus Garin le Loherain), mais si jamais plusieurs groupes étaient intéressés, j'en ai d'autres qui peuvent aussi faire l'affaire.

Vous avez, dans ce dossier:
racine
- les métadonnées en csv
- ce lisez-moi
    - exemple/  un exemple de fragment encodé
    - ocr/  le résultat de l'ocr des documents (fichier sortie.txt), ainsi que les sources (dossier src/) ;
    - odd/  la documentation et le schéma
