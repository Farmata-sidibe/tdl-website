Pour le deploiement en local
- clone du dossier tdl-website
- puis clone de chaque projet individuellement (tdl et tdlApi)
  Lancer le site
  - ouvrir deux termial pour le dossier tdl et pour chaque terminal taper les commandes suivantes:
  - php artisan serve
  - npm run dev
  Afin de lancer le laravel et Vite
Pour effectuer la migration de la base de données :
-php artisan migrate

Pour le dossier tdlApi
-ouvrir un nouveau terminal qui pointe vers ce dossier et taper la commande suivante:
-npm start

Avec ces commandes vous pouvez visualiser le site en local et avoir accés au produits scrappés via l'api nodejs (tdlApi)
N'oubliez pas de configuré votre fichier .env dans chaque dossier

vous pouvez aussi le deployer sur Docker
