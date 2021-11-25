# Critère :
1. Arborescence
2. Guidage
3. [Contrôle explicite](#3-contrôle-explicite)
	- [Actions explicites & Contrôle utilisateur](#actions-explicites--contrôle-utilisateur)
		- [Définition](#définition)
		- [Lien de retour](#lien-de-retour)
		- [Breadcrump](#breadcrump)
		- [Menu](#menu)
4. Accompagnement à l'erreur

## 3. Contrôle explicite :
### Actions explicites & Contrôle utilisateur :
#### Définition
Actions explicites :  
> Ce critère indique que le système doit assurer une synchronisation minutieuse entre les actions réalisées par l’utilisateur et les réponses rendues par le système. Ce dispositif doit répondre d’une manière explicite et immédiate aux actions de l’usager.

Contrôle utilisateur :  
> Ce critère stipule que l’utilisateur doit toujours contrôler le séquencement de ses actions pour interagir avec le système. Il doit avoir la main pour annuler, reprendre ou interrompre une action, quand il le souhaite.

#### Lien de retour

On trouve des liens de retours "généraux" lors de la navigation dans le [formulaire de demande de devis de gestion de bornes](https://freshmile.com/demande-de-devis/devis-gestion-de-borne/).  
On y trouve un bouton de réinitialisation du formulaire ainsi que des boutons de retour pour revenir aux étapes précédentes.

#### Breadcrump
En assez bon exemple, on peut trouver les pages : "[Propriétaire de bornes](https://freshmile.com/propriétaire-de-bornes)"

Exemples :
- [Entreprises](https://freshmile.com/proprietaires-de-bornes/entreprises/)
- [Hôtels](https://freshmile.com/proprietaires-de-bornes/hotels/)

Ils sont bons, car en plus du fil d'Arianne, on retrouve notre position grâce à l'URL.  
Il aurait été encore mieux de retrouver la catégorie dans le `<title>` de la page. Ainsi que de garde une interaction à l'actif dans le menu pour continuer de mettre la catégorie actuelle en valeur.

En revanche, les pages : "[En savoir plus](https://freshmile.com/en-savoir-plus)"

Exemples :
- [Advenir](https://freshmile.com/en-savoir-plus/advenir)  
Dans cet exemple, on retrouve bien la catégorie dans l'URL. Mais la page elle-même est accessible depuis le menu "Liens utile" du footer. Ce qui rend plus confus l'utilisateur quant à sa position dans le site.

- [Comment payer ses recharges Freshmile ?](https://freshmile.com/payer-recharges-freshmile/)  
Dans les cas des articles de cette catégorie, on ne retrouve pas la catégorie dans les liens. On peut donc les confondre avec des pages de premier niveau.

On peut aussi noter un problème commun à tous ces cas. Lors de l'arrivé sur ses pages, il est très difficile de savoir où nous nous trouvons. En effet, la catégorie "En savoir plus" n'est visible que dans le footer. Ce qui peut perdre l'utilisateur. Qui pourra alors penser qu'il se trouve dans l'une des pages présente dans le menu principal.

#### Menu
Les menus ne changent ni de position ni de contenu lors de la navigation.