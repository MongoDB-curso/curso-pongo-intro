# Connect to container

docker compose exec mongodb bash

# Connect with mongosh

mongosh "mongodb://root:root123@localhost:27017/?tls=false"

mongosh "mongodb://root:root123@localhost:27017/?tls=false"

mongosh "mongodb+srv://stefanreyes33:kIdG9SUNzzuS2c4S@mongodb101.mcrrm.mongodb.net/"

show dbs
show collections

use("platzi_store")

db.products.find()
