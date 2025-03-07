# TP noté
## Lancer l'application
  **Installer les dépendances**\
    lancer la commande : composer i
   
  **Modifier le .env**\
    exemple :\
    DATABASE_URL="mysql://root:@127.0.0.1:3306/todo-app?serverVersion=8.2.0&charset=utf8mb4"
  
  **Initialiser la base de données**\
    php bin/console doctrine:database:create\
    php bin/console doctrine:migrations:migrate
  
  **Lancer le projet**\
    symfony server:start

  **Aller sur le lien suivant**\
    http://127.0.0.1:8000/task
    
## Action possible
  **Filter**\
    Choisissez votre filtre, et cliquer sur le bouton filter.
    
  **Create**\
    Cliquer sur le bouton "create new", remplisser le formulaire, et cliquer sur le bouton "save".

  **Edit**\
    Cliquer sur le bouton "edit", remplisser le formulaire, et cliquer sur le bouton "update".

  **Delete**\
    Cliquer sur le bouton "delete", il vous sera demander si vous êtes sur de supprimer cette task. Cliquer sur le second bouton "delete".

  **Marquer comme terminé**\
    Cliquer sur le bouton "Marquer comme terminé". Le status sera modifier en Yes, et le bouton disparaitra.
