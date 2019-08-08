# Jeedom-WidGet_Object-all-picture

Widget dédié aux objets avec choix multiple pour l'affichage des images.  
Peut être utiliser en version desktop et mobile.  

Voici l'ensemble des images disponibles pour ce widget, avec la valeur de la variable "equipImg".  
  
|  Numéro  |   Icon OFF  |   Icon ON   |   Valeur "equipImg"   |
| :------: | :---------: | :---------: | :-------------------: |
| 1 | ![Object éléctrovanne](cmd.action.other.Object-all-picture/Object-electrovanne_NOK.png) | ![Object éléctrovanne](cmd.action.other.Object-all-picture/Object-electrovanne_OK.png) | **Object-electrovanne** |
| 2 | ![Object prise Legrand extérieur](cmd.action.other.Object-all-picture/Object-prise-legrand-exterieur_NOK.png) | ![Object prise Legrand extérieur](cmd.action.other.Object-all-picture/Object-prise-legrand-exterieur_OK.png) | **Object-prise-legrand-exterieur** |
| 3 | ![Object prise Legrand](cmd.action.other.Object-all-picture/Object-prise-legrand_NOK.png) | ![Object prise Legrand](cmd.action.other.Object-all-picture/Object-prise-legrand_OK.png) | **Object-prise-legrand** |
| 4 | ![Object théière Rivierabar](cmd.action.other.Object-all-picture/Object-theiere-rivierabar_NOK.png) | ![Object théière Rivierabar](cmd.action.other.Object-all-picture/Object-theiere-rivierabar_OK.png) | **Object-theiere-rivierabar** |
| 5 | ![Ventilateur metal grand](cmd.action.other.Object-all-picture/Ventilateur-metal-grand_NOK.png) | ![Ventilateur metal grand](cmd.action.other.Object-all-picture/Ventilateur-metal-grand_OK.png) | **Ventilateur-metal-grand** |
| 6 | ![Ventilateur metal petit](cmd.action.other.Object-all-picture/Ventilateur-metal-petit_NOK.png) | ![Ventilateur metal petit](cmd.action.other.Object-all-picture/Ventilateur-metal-petit_OK.png) | **Ventilateur-metal-petit** |
| 7 | ![Ventilateur plafond bois](cmd.action.other.Object-all-picture/Ventilateur-plafond-bois_NOK.png) | ![Ventilateur plafond bois](cmd.action.other.Object-all-picture/Ventilateur-plafond-bois_OK.png) | **Ventilateur-plafond-bois** |
| 8 | ![Ventilateur plafond bois 2](cmd.action.other.Object-all-picture/Ventilateur-plafond-bois-2_NOK.png) | ![Ventilateur plafond bois 2](cmd.action.other.Object-all-picture/Ventilateur-plafond-bois-2_OK.png) | **Ventilateur-plafond-bois-2** |  
  
## Utilisation du widget
Tout d'abord, installer le widget via le market de Jeedom, ou cliquer sur ce [lien](https://www.jeedom.com/market/index.php?v=d&p=market&author=lolo-95 "lien vers le market Jeedom") .  
Ensuite, aller dans le module Object qui vous intéresse, par exemple *plugins* / *programmation* / *Virtuel* / *Prise Cheminée* .  
Choisir l'onglet *Commandes*, dans un premier temps on clic sur la roue crantée au bout de la ligne *On* .  
On va sur l'onglet *Affichage*, on sélectionne *Object-all-picture (widget)* dans le tableau *Widget* .
Puis, dans *Paramètres optionnels widget* on clic sur *+ ajouter* à droite, une ligne supplémentaire apparaît en dessous, dans *Nom* on écrit *equipImg*, puis dans *valeur* on entre le nom qui se trouve à droite dans le tableau ci-dessus, par exemple *Object-prise-legrand*, ne pas oublier d'enregistrer les modification avec le bouton *Enregistrer* en haut à droit de la fenêtre, puis on ferme la fenêtre.  
Dans un deuxième temps on reproduit la même chose avec la ligne *Off* de l'onglet *Commandes* .......  
Voilà vous avez configuré votre widget, allez dans *Acceuil* / *Dashboard* / *Salon* , le widget *Prise Cheminée* à changer avec l'image de Object-prise-legrand, cliquer dessus pour changer son état.  
  
## Changelog
Août 2019 : création du widget.