## Connecto container 
```sh
docker-compose exec mongodb bash

```
## Connect with mongosh
```sh
mongosh "mongodb://sebas:password@localhost:27017/?tls=false" #connection uri
mongosh "mongodb+srv://sebchar21:password@mongodb102.q3cs0.mongodb.net/" #connection Uri to cloud DB
```

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```