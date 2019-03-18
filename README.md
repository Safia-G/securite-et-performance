# securite-et-performance - Premier TP -

J'ai décidé  de tester le site de l'entreprise dans laquelle j'effectue mon alternance :
https://www.tcp-innovation.fr/

Voici le résultat du test effectué :

  - Progressive Web App : 55
  - Performance : 48
  - Accessibility : 94
  - Best Practices : 67

Afin d'améliorer ces scores voici ce que je propose :

Progressive Web App :
  - Répondre avec un 200 en mode hors connexion
  - Configurer un écran de démarrage personnalisé
  - Faire correspondre la barre d'adresse avec les couleurs de la marque: balise `<meta name =" theme-color ">`.
Performance :
  - Réduire la taille des images
  - Servir des images en tant que WebP
  - Optimiser les images
  - Réduire les scripts bloquant le rendu
  - Réduire les feuilles de style bloquant le rendu.
Accessibility :
  - Revoir le nom des liens
  - Les couleurs de fond et de premier plan n'ont pas un rapport de contraste suffisant.
Best Practices :
  - Utiliser HTTP / 2 pour ses propres ressources: 46 demandes n'ont pas été traitées sur h2
  - Utiliser des écouteurs passifs pour améliorer les performances de défilement
  - Ouvrir les ancres externes en utilisant rel = "noopener"
  - Le nom abrégé du manifeste n'est pas tronqué lorsqu'il sera affiché sur l'écran d'accueil
