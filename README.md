# TerroristAttackDashboard
Création d'un tableau de bord interactif sur les attaques terroristes. 

```
mongoimport --host terrorismcluster-shard-00-02.miafv.mongodb.net:27017 --db terrorismAttack_db --collection terrorismAttack --type csv --file terrorismAttack_db.csv --headerline --authenticationDatabase admin --ssl --username admin --password root 
```

```
mongoimport --host terrorismcluster-shard-00-02.miafv.mongodb.net:27017 --db terrorismAttack_db --collection terrorismAttack --type csv --file streaming.csv --headerline --authenticationDatabase admin --ssl --username admin --password root 
```
