# ServerManagerApp

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Description
Il s'agit d'une application de gestion de serveur dans un réseau local ou aussi les serveurs en remote d'une entreprise.
Dans ce repository se trouve la partie frontend réalisé avec Angular, vous pouver trouver la partie backend réalisé avec Java Spring Boot [ici](https://github.com/Ericko444/server-manager)

## Fonctionnalités
* L'utilisateur peut voir la liste des serveurs sauvegardés dans l'application
* Il peut filtrer les serveurs par
  * Tous les serveurs
  * Serveurs actifs
  * Serveurs hors service
* Il peut tester si un serveur est en panne ou est actif en effectuant un pig, alors le status du serveur changera selon son status actuel et le résultat du test
* Il peut ajouter un nouveau serveur
* Il peut générer un rapport sous format document pdf ou xls de l'état des serveurs

## Démo
* Liste des serveurs sauvegardés dans l'application

![Image 1](https://user-images.githubusercontent.com/60751096/160564563-2ed8e2f0-1544-4450-a59a-8f10e90b0524.png)

* Filtre des serveurs
  
  * Serveurs actifs
  ![Image 2](https://user-images.githubusercontent.com/60751096/160564754-806d1afb-7360-47bd-9d83-c04f4eeca0f8.png)

  * Serveur hors service   
  ![Image 5](https://user-images.githubusercontent.com/60751096/160564785-65a443c0-2845-4131-8edf-3fd07198a7b2.png)
  
  
* Test des serveurs
  
  * Voir si un serveur hors service a déjà été activé
  ![Image 10](https://user-images.githubusercontent.com/60751096/160565201-7b0a940c-0429-4fa9-bbaa-4deb01fc2678.png)

  ![Image 11](https://user-images.githubusercontent.com/60751096/160565159-6a849a87-a762-4f04-9157-bbcf99d41bd4.png)
  
  Ici, on voit bien que le statut du serveur n'a pas encore changé car il n'a pas encore été activé
  
  ![Image 12](https://user-images.githubusercontent.com/60751096/160565542-581c6369-1224-456a-8270-173e2ed89689.png)
  
  Ici, en testant le premier serveur, on voit qu'il a été activé et que son état est passé de SERVER DOWN à SERVER UP

* Ajout de nouveau serveur
  
  ![Image 13](https://user-images.githubusercontent.com/60751096/160565973-3c761aaf-ce9c-484c-ba30-5fe82f0a32c8.png)
  ![Image 14](https://user-images.githubusercontent.com/60751096/160566028-dd3118ff-4abe-4e57-a56b-da9e6224c39f.png)
  
* Test de serveur en remote

  ![Image 16](https://user-images.githubusercontent.com/60751096/160566226-3bbc04c6-d243-4880-84ee-476ddc3f79ea.png)
  ![Image 15](https://user-images.githubusercontent.com/60751096/160566262-5c54c5b9-eef5-4101-9dc6-71905bb1dac2.png)
  
* Générer un rapport

  ![Image 19](https://user-images.githubusercontent.com/60751096/160566721-ddf0996f-c35c-4091-9143-933f33f363c8.png)
  ![Image 20](https://user-images.githubusercontent.com/60751096/160566740-6fec7be7-f12f-42c7-94d8-60a03a871599.png)




