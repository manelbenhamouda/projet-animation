Tâches à réaliser : Animations et Intégration des Médias
1. Animations
* Menu de navigation :
    * Ajouter une transition sur les liens du menu pour changer leur couleur au survol
    * Optionnel : Appliquer une transformation (par exemple, un léger déplacement ou une augmentation de taille) sur les liens ou icônes lors du survol
* Bouton "Découvrir plus" :
    * Ajouter une transition sur le bouton pour qu'il réagisse au survol.
    * Appliquer une transformation CSS sur le bouton (par exemple : zoom, rotation, ou translation) lors du survol
* Galerie d'images :
    * Ajouter une transition sur les images pour qu'elles réagissent au survol.
    * Appliquer une transformation CSS sur les images (par exemple : zoom, rotation, ou translation) lors du survol
2. Intégration des Médias
* Images :
    * Utiliser la balise <picture> pour gérer l'affichage des images dans différentes résolutions selon la taille de l'écran.
    * Vérifier que les images sont bien responsives, c'est-à-dire qu'elles s'adaptent correctement à différentes tailles d’écran
* Vidéo :
    * Intégrer une vidéo avec la balise <video>, en utilisant l'attribut poster pour afficher une image avant le démarrage de la vidéo
    * Vérifier que la vidéo est bien responsive (qu'elle s'ajuste à la taille de l'écran) et fonctionne correctement sur tous les appareils
3. Optimisation des Médias
* Lazy Loading des images :
    * Ajouter l’attribut loading="lazy" à chaque balise <img> pour activer le lazy loading, c’est-à-dire que les images ne se chargeront qu’au moment où elles sont visibles à l’écran
* Compression des images :
    * Utiliser des images optimisées en format WebP ou JPEG compressé pour améliorer les performances du site
    * Expérimenter avec l'attribut srcset pour servir des images de résolutions différentes selon la taille de l'écran (par exemple, une image en haute résolution pour les grands écrans et une version plus légère pour les mobiles)

Instructions supplémentaires :
* Tester le projet sur différents appareils (ordinateur, tablette, smartphone) pour vérifier la réactivité et la performance des images et vidéos
* Faire attention à la fluidité des transitions et transformations : l'objectif est d'améliorer l'interactivité et l'expérience utilisateur sans compromettre les performances
* Optimiser les temps de chargement en compressant les images et en utilisant le lazy loading, surtout pour les pages qui contiennent beaucoup d'images ou de vidéos

Bonnes pratiques :

* Utilisez des transitions douces (0.3s à 0.5s) pour les interactions avec les boutons, les images et les liens afin d'améliorer l'expérience utilisateur
* Vérifiez la compatibilité des médias sur différents navigateurs
