# Projet section web


## Cahier des charges

### 1. Présentation du projet
   1. **Client** : Le client du projet est M. Vilain, enseignant du bachelier en Techniques Graphiques de la HEPL (en web). Il demande de réaliser un site pour l'orientation web en raison du fait qu'il n'y en a pas du tout et que le site de la HEPL n'informe pas assez sur ce bachelier, ce qui peut parfois ne pas aider les étudiants qui seraient intéressés par le domaine du Web.
   2. **Objectifs du site** : 
      1. Le site à réaliser est un site vitrine pour la section web du bachelier en techniques graphiques de la HEPL
      2. Son but est d'augmenter le nombre d'étudiants
      3. Ainsi qu'augmenter le visibilité des anciens étudiants
   3. **Besoins du client** :
      1. Le site doit être vivant et être en contact avec la réalité en montrant les réalisations des étudiants
      2. Il doit y avoir les fiches des anciens étudiants et il faut parler du métier qu'ils font, afin que l'utilisateur ait une idée des débouchées éventuelles
      3. Il doit présenter le réseau des entreprises et parler de leur métier pour encore une fois, avoir une idée des débouchées mais aussi mettre l'accent sur le fait que les métiers du web sont en pénurie
         1. Mais aussi faciliter l'intéraction avec ce réseau via la publication des offres de stage et d'emploi
      4. Il doit y avoir une page dédiée à l'actualité de l'orientation web (conférences, journée portes ouvertes, événements, ...)
         1. Certaines de ces news peuvent être placées manuellement sur la page d'accueil
      5. Il doit y avoir un espace intéractif (forum), comme ça les futurs étudiants peuvent poser des questions sur les cours, les profs,... ou des questions plus personnelles et avoir une réponse d'un étudiant actuel afin d'avoir une idée sur la réalité
      6. Le site doit informer sur les valeurs, la qualité web (très demandé par les entreprises) et les pratiques de la section, ainsi que ce qui distingue des autres formations (glossaire? - tutoriel?)
      7. Il doit présenter le programme des cours (sous forme de tableau)
      8. Le site doit présenter les professeurs avec une fiche CV par exemple
      9. Il doit présenter le contexte académique (HEPL) et avoir des pages relatifs à la HEPL
      10. Il doit y avoir une page/section des questions habituelles (FAQ? par exemple)
      11. Il doit y avoir une newsletter dans le site
      12. Le site doit être multilingue (français, anglais, néerlandais, allemand)
      13. Il doit y avoir des rôles différents (administrateur, co-admins,...) qui ont des droits différents
      14. Il doit y avoir une fonctionnalité de partage aux réseaux sociaux pour les réalisations des étudiants
      15. Les images doivent être responsive
      16. Le niveau d'accessibilité doit est au minimum AA
      17. Il doit y avoir un moteur de recherche interne
      18. L'utilisateur doit pouvoir s'inscrire/se connecter pour pouvoir écrire/répondre dans le forum
      19. Lorsque quelqu'un répond à un sujet du forum, l'auteur du sujet reçoit un mail
      20. Il doit y avoir des notifications pour l'admin lorsqu'il reçoit un message
      21. Il doit y avoir un espace traduction des documentations 
   4. **Public cible** : 
      1. Les futurs étudiants
      2. Les parents des futurs étudiants
      3. Les étudiants actuels
      4. Les entreprises cherchant un stagiaire ou un employé
   5. **Personas** :
   
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
    Métier : Etudiante en web
    Besoin : Finalement en 3e année, Seda cherche désespérément un stage en tant que frond-end developer via Google mais n'en trouve pas qui lui convient. Heureusement, Natacha lui a renseigné le site de la section web et Seda va donc y chercher un stage !
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

### 2. Charte graphique
   1. Code couleur : 
   2. Polices : 
   3. Design : 
   
### 3. Description fonctionnelle et technique
   1. **Arborescence du site** :
      1. **Page d'accueil** : il y aura 3 sections
         1. La première est la section "Actualités"
         2. La deuxième est la section "A propos de l'orientation web" avec une petite description sur l'orientation web et un CTA vers la page "A propos"
         3. La dernière est la section "Présentation du réseau entreprise" avec une petite description et un CTA vers la page des offres d'emploi et de stage
      2. **Page des actualités** est une liste des news (du plus récent)
      3. **Page d'une actualité**
      4. **Page à propos de la section web** avec 4 sections
         1. La première section parle des valeurs, de la qualité web, des pratiques, débouchés et il aura un CTA "voir les oeuvres des étudiants" pour que l'utilisateur puisse avoir une idée concrète de ce qu'il pourra faire lorsqu'il finira ses études en web
         2. La section suivante parle du contexte académique (HEPL) (ou bien une section divisée en 2?)
         3. Ensuite, il y a un section "Programme des cours" avec une explication du cours et le nom du professeur qui donne ce cours (lien vers la fiche du professeur en question)
         4. Enfin, la dernière section montre quelques anciens étudiants en parlant du métier qu'ils font
      5. **Page des réalisations des étudiants** (liste)
      6. **Page d'une réalisation** d'un étudiant
         1. Il y a plusieurs informations à propos de la réalisation, comme le nom, l'auteur, la date, la présentation du projet, les objectifs et les besoins et les langages utilisés
         2. L'utilisateur peut aussi aller voir le site (s'il y en a un) via un lien
         3. Et peut partager le projet
      7. **Page des professeurs** (liste)
      8. **Page de la fiche d'un professeur**
         1. Cette page parle du professeur, de son parcours et des cours qu'il donne
      9. **Forum**
         1. L'utilisateur peut ajouter un sujet au forum via un CTA
         2. Il peut filtrer les sujets par tag en fonction de ses besoins (à propos des cours, de l'administration,...) et par langue
         3. Il peut aussi rechercher un sujet particulier grâce à un moteur de recherche interne
         4. Ensuite, il y a la liste des sujets
            1. En tout premier lieu se trouvent les sujets épinglés
            2. Pour chaque sujet, il y a le titre, l'auteur, le nombre de réponses, la date du dernier message envoyé dans le sujet et les tags liés à celui-ci
      10. **Page d'un sujet du forum**
          1. On trouve d'abord le tout premier message de l'auteur du sujet avec l'auteur, le titre et la date
          2. Messages/réponses par plus récent
          3. Bouton "répondre" créant un textarea ou si l'utilisateur n'est pas encore connecté, une boîte de dialogue pour se connecter/s'inscrire
          4. CTA "load more" pour plus de messages anciens
      11. Inscription/connexion pour le forum quand on veut répondre ou créer un nouveau sujet
      12. **Page de création d'un sujet** pour le forum
          1. Pour créer un sujet, il faut y mettre son titre du sujet et le message/question et la langue qu'il utilise
          2. L'utilisateur peut choisir un/des tag(s)
      13. **Page inscription**
          1. Un simple formulaire d'inscription avec les données basiques : l'identifiant, l'email et le mot de passe
      14. **Page connexion**
          1. Un simple formulaire de connexion avec l'email, le mot de passe et un "Se souvenir du mot de passe"
      15. **Questions habituelles**
      16. **Page contact**
          1. Il y a un petite section pour les coordonnées (adresse, téléphone, mail, réseaux sociaux?)
          2. Ensuite, il y a un formulaire de contact où on donne son nom, son prénom, son email, son numéro de téléphone et son message
          3. On peut aussi choisir l'objet du message : 
             1. Offre de stage/emploi
             2. Information sur la section??
             3. Autres
                1. Offre de stage/emploi
                2. Information sur la section??
          4. 
      17. **Page offre d'emploi/stage**
          1. Dans cette page se trouve une liste des offres d'emploi et de stage qu'on peut trier (en fonction de si c'est pour un stage ou un emploi) 
          2. L'utilisateur peut aussi recherche en fonction du métier (web developer, front-end designer, ...)
          3. L'utilisateur peut alors soit contacter l'agence via l'email ou le numéro de téléphone indiqué ou peut aller voir le site du l'agence pour en savoir plus
      18. **Page réglage** pour l'utilisateur connecté
          1. Ici, l'utilisateur connecté peut voir et éditer son identifiant, son email et son mot de passe 
      19. **Page traduction** 
      20. 
      
   2. **Menu** :
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
   3. **Footer** :
      1. Navigation
      2. Logo HEPL
      3. Coordonées
      4. FAQ?
      5. Newsletter
      6. Langue
   4. 


#### Planning : 
wireframe textuel : 26/09
wireframe : 03/10
design : 10/10