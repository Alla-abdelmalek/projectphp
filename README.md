## SuperShop - Projet eCommerce PHP


Il s'agit d'un projet eCommerce développé en utilisant du PHP natif. Il est conçu pour fournir une expérience d'achat en ligne fonctionnelle et conviviale pour les clients.

Fonctionnalités
Inscription et authentification des utilisateurs : Les utilisateurs peuvent créer des comptes et se connecter en toute sécurité pour accéder à leur profil et effectuer des achats.
Catalogue de produits : Affichage d'une large gamme de produits avec des détails tels que le nom, la description, le prix et la disponibilité.
Panier d'achat : Les utilisateurs peuvent ajouter des produits à leur panier, modifier les quantités et passer à la caisse.
Gestion des commandes : Les utilisateurs peuvent consulter leur historique de commandes et vérifier l'état de leurs commandes en cours.
Intégration de paiement : Intégration avec une passerelle de paiement pour faciliter les transactions en ligne sécurisées.
Panel d'administration : Un panel d'administration est disponible pour les administrateurs du site afin de gérer les produits, les catégories et les commandes.

### Structure des dossiers de l'application FrontEnd

```
├───app
│   ├───Http
│   │   └───Controllers
│   └───Models
├───config
├───public
│   ├───assets
│   │   ├───css
│   │   ├───fonts
│   │   ├───images
│   │   └───js
│   └───uploads
│       ├───admins
│       ├───banners
│       ├───products
│       └───slides
└───resource
    ├───files
    └───view
        ├───content
        └───include
```
### Inastalation
1- Clonez le dépôt :
https://github.com/AbdessamadSayhi/supershop.git

2- Configurez la base de données :

Créez une nouvelle base de données MySQL pour le projet.
Importez le fichier supershop_rdb.sql situé dans le répertoire resource\files.
Mettez à jour les informations d'identification de la base de données dans le fichier config.php.

### Features:

- Home Page
- Category
- Category Lists
- Product
- Serach
- Cart
- Payments
- Order
- Invoice Generate
- User Registration
- User Login
- User Dashboard
