:warning: checker l'url de la db (regarder le fichier **.env**) avant d'aller plus loin...

:warning: Si l'entité a été modifiée, ou alors n'est pas encore présent dans votre db, il faut mettre à jour la db ...

1.  Préparer la requête sql

```
bin/console doctrine:schema:update --dump-sql
```
2. Effectuer la requête sql et modifier la db

```
bin/console doctrine:schema:update --force
```
