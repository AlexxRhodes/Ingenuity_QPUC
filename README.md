# Ingenuity_QPUC
Project by Alex RHODES and Eliot PAZZE

Canva : https://www.canva.com/design/DAG0oGv7Y8s/Q9ij_uBzxmuhIZibXk6X4A/edit?utm_content=DAG0oGv7Y8s&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

Elements de reflexion : 
  - Image du présentateur
  - Voix de Julien Lepers/Samuel Etienne
  - Comparaison timestamp pour gérer les conflits de buzzer
  - Afficher image du joueur prise par la webcam juste avant
  - Questions générées par LLM via API
  - Buzzer si erreur

Déroulement du jeu : 
  - 9 points gagants :
    * Le premier qui buzz remporte entre 1 et 3 points
      * Si 4 participants : 1, 2 puis 3 points en boucle
      * Si 3 participants : 2 points
      * Si 2 participants : 3 points
    * S'il se trompe ou met trop de temps à répondre : buzzer + perd la main
    * Possibilité de buzzer avant la fin de l'énnoncé de la question
  - 4 à la suite
    * 4 propositions de thèmes dont 1 caché
    * Choix du thème dans l'ordre de la victoire au "9 points gagnants"
    * 40 secondes pour répondre à 4 de questions d'affliée (1 bonne réponse = 1 point)
    * S'il passe ou se trompe : retour à 0
    * A la fin des 40s, sa dernière série de bonne réponse est retenu et les 2 candidats avec la plus haute série vont en face-à-face.
  - Face à face :
    * 
