
lister les docker processus 
--------------------------------
```
docker ps 
docker ps -a 
```

garder une image en fonction
--------------------------------
d : detache
i : interactif

```
docker run -di --name youness alpine:latest
```

se connecter a un docker
--------------------------------

```
docker exec -ti youness sh
```

La commande lancer conteneur NGINX :
--------------------------------
-p exposition de port, Ex. faire rediriger un port du conteneur vers notre machine locale

```
docker run -tid -p 8080:80 --name web nginx:latest
```



#Les options : 
--------------------------------------

    -t : Allouer un pseudo TTY (terminal virtuel)
    -i : Garder un STDIN ouvert (l'entrée standard plus précisément l'entrée clavier)
    -d : Exécuter le conteneur en arrière-plan et afficher l'ID du conteneur





