# Projet section web


## Cahier des charges

1. Présentation du projet 
   1. Objectifs du site : 
      1. Le site à réaliser est un site vitrine pour la section web du bachelier en techniques graphiques de la HEPL
      2. Son but est d'augmenter le nombre d'étudiants
      3. Ainsi qu'augmenter le visibilité des anciens étudiants
   2. Besoins du client :
      1. Le site doit être vivant et être en contact avec la réalité en montrant les réalisations des étudiants
      2. Ils doit y avoir les fiches des anciens étudiants et il faut parler du métier qu'ils font 
      3. Il doit présenter le réseau des entreprises et parler de leur métier
         1. Mais aussi faciliter l'intéraction avec ce réseau via la publication des offres de stage et/ou d'emploi
      4. Il doit y avoir une page dédiée à l'actualité de l'orientation web (conférences, journée portes ouvertes, événements, ...)
         1. Certaines de ces news peuvent être placées manuellement sur la page d'accueil
      5. Il doit y avoir un espace intéractif (forum)
      6. Le site doit informer sur les valeurs, la qualité web et les pratiques de la section, ainsi que ce qui distingue des autres formations (glossaire? - tutoriel?)
      7. Il doit présenter le programme des cours (sous forme de tableau)
      8. Le site doit présenter les professeurs avec une fiche CV par exemple
      9. Il doit présenter le contexte académique (HEPL) et avoir des pages relatifs à la HEPL
      10. Il doit y avoir une page/section des questions habituelles (FAQ? par exemple)
      11. Il doit y avoir une newsletter
      12. Le site doit être multilingue (français, anglais, néerlandais, allemand)
      13. Il doit y avoir des rôles différents (administrateur, co-admins,...) qui ont des droits différents
      14. Il doit y avoir une fonctionnalité de partage aux réseaux sociaux pour les réalisations des étudiants
      15. Les images doivent être responsive
      16. Le niveau d'accessibilité doit est au minimum AA
      17. Il doit y avoir un moteur de recherche interne
      18. L'utilisateur doit pouvoir s'inscrire/se connecter pour pouvoir écrire/répondre dans le forum
      19. Lorsque quelqu'un répond à un sujet du forum, l'auteur du sujet reçoit un mail
      20. Il doit y avoir des notifications pour l'admin lorsqu'il reçoit un message
   3. Public cible : 
      1. Les futurs étudiants
      2. Les étudiants
      3. Les entreprises
   4. Personas :
   

    Nom : Futur Etudiant
    Âge : 18 ans 
    Métier : futur étudiant
    Besoin : Futur Etudiant a terminé ses études secondaires. Il est fort intéressé par tout ce qui touche sur le web et souhaite en savoir d'avantage sur l'orientation web du Bachelier en Techniques Graphiques et surtout les cours et les débouchés de celui-ci.
    Parcours de l'utilisateur : 
    - Recherche dans un moteur de recherche via les mots-clés : ecole bachelier web
    - Il arrive sur le site et trouve une rubrique "A propos de l'orientation web"
    - Il a donc une description de la section ainsi que le programme des cours
    - Grâce à un CTA, il peut aller voir les réalisations des étudiants pour savoir exactement à quoi ressemble le produit fini d'un étudiant
    - 
----
    Nom : Seda Karadeniz
    Âge : 24 ans 
    Métier : Etudiante
    Besoin : Finalement en 3e année, Seda cherche désespérément un stage via Google mais n'en trouve pas qui lui convient. Heureusement, Natacha lui a renseigné le site de la section web et Seda va donc y chercher un stage !
    Parcours de l'utilisateur :
    - Elle entre dans le site grâce à l'url que Natacha lui a fournie
    - Dans le menu, elle clique sur "emploi"
    - Elle arrive sur la page des offres de stage et d'emploi et filtre pour ne voir que les stages
    - Une offre de stage répond à ses critères et grâce à un lien externe, elle peut aller sur leur site pour en savoir d'avantage et peut-être postuler
---
    Nom : Entreprise
    Âge : /
    Métier : 
    Besoin : L'Entreprise aurait besoin d'un stagiaire en front-end developer et sait que les étudiants de la HEPL sont très qualifiés. Il souhaite donc contacter un professeur pour lui donner son offre de stage afin qu'il puisse le communiquer à ses étudiants
    Parcours de l'utilisateur : 
    - Recherche dans un moteur de recherche via les mots-clés : hepl developpeur front-end 
    - Via le menu, il décide de cliquer sur "emploi"
    - Il y trouve des offres d'emploi et de stage
    - Ne sachant pas y mettre son offre, il décide de contacter l'admin qui lui pourra poster l'offre
    - Via le menu, il clique sur contact
    - En arrivant sur la page contact, il y trouve l'adresse mail et l'utilise pour prendre contact

2. Charte graphique
   1. Code couleur : 
   2. Polices : 
   3. Design : 
   
3. Description fonctionnelle et technique
   1. Arborescence du site :
      1. Page d'accueil 
         1. Section Actualités
         2. Section A propos de l'orientation web + CTA vers la page "A propos"
         3. Section Présentation du réseau entreprise + CTA vers les offres
      2. Page des actualités (liste par plus récent)
      3. Page d'une actualité
         1. Image principale
         2. Titre
         3. Date
         4. Contenu
         5. 
      4. Page à propos de la section web
         1. Contexte académique (HEPL)
         2. Valeurs, qualité web, pratiques, débouchés + CTA voir les oeuvres des étudiants
         3. Programme des cours + explication du cours et le nom du professeur qui donne ce cours (lien vers la fiche du professeur en question)
         4. Quelques anciens étudiants en parlant du métier qu'ils font
      5. Page des réalisations des étudiants (liste)
      6. Page d'une réalisation d'un étudiant
         1. Image
         2. Nom d projet
         3. Auteur du projet
         4. Date
         5. Lien vers le site
         6. Fonctionnalité de partage
         7. Excerpt du projet
         8. Langages utilisés
         9. Contenu :
            1. Présentation du projet (entreprise)
            2. Besoins et objectifs
            3. Images
         10. CTA? vers d'autres projets
      7. Page des professeurs 
      8. Page de la fiche d'un professeur
         1. Nom Prénom
         2. Parcours du professeur
         3. Cours qu'il donne
      9. Forum
         1. CTA "Ajouter un sujet"
         2. Filtre par tag
         3. Recherche
         4. Liste des sujets
            1. Sujets épinglés en premier
            2. Titre du sujet
            3. Auteur du sujet
            4. Nombre de réponses
            5. Date du dernier message envoyé dans le sujet
            6. Tags
         5. 
      10. Page d'un sujet du forum
          1. Tout premier message de l'auteur du sujet avec l'auteur, le titre et la date
          2. Messages par plus récent
          3. Bouton "répondre" créant un textarea ou si pas connecté, une boîte de dialogue pour se connecter/s'inscrire
          4. CTA "load more" pour plus de messages anciens
      11. Inscription/connexion pour le forum quand on veut répondre ou créer un nouveau sujet
      12. Page de création d'un sujet pour le forum
          1. Titre du sujet
          2. Message
          3. Choisir un/des tag(s)
          4. CTA "Ajouter le sujet"
      13. Page inscription
          1. Identifiant
          2. Email
          3. Mot de passe
          4. Confirmer le mot de passe
          5. CTA "S'inscrire"
      14. Page connexion
          1. Email
          2. Mot de passe
          3. "Se souvenir du mot de passe"
          4. CTA "Se connecter"
      15. Questions habituelles
      16. Page contact
          1. Coordonnées (adresse, téléphone, mail, réseaux sociaux?)
          2. Formulaire de contact
             1. Objet
                1. Offre de stage/emploi
                2. Information sur la section??
             2. Nom
             3. Prénom
             4. Email
             5. Message
             6. CTA "Envoyer"
      17. Page offre d'emploi/stage
      18. 
      
   2. Menu :
      1. Accueil
      2. Actualités
      3. A propos
         1. Section web
         2. Programme des cours
         3. Nos anciens
         4. Nos professeurs
      4. Réalisations
      5. Forum
      6. Contact
      7. Emploi
      8. Langue
      9. Recherche
      10. Se connecter
   3. Footer :
      1. Navigation
      2. Logo HEPL
      3. Coordonées
      4. FAQ?
      5. Newsletter
      6. Langue
   4. 