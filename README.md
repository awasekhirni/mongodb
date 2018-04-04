# mongodb

Registering as a service  in windows 
sc.exe create MongoDB binPath= "\"C:\Program Files\MongoDB\Server\3.6\bin\mongod.exe\" --service --config=\"C:\data\mongod.cfg\"" DisplayName= "MongoDB" start= "auto"

net start MongoDB
net stop MongoDB

mongod --dbpath "C:\Program Files\MongoDB\Server\3.4\bin\data" --port 27017 --logpath "C:\Program Files\MongoDB\Server\3.4\mongo.log


MongoDB Client
RoboMongo
NoSQLBooster for MongoDB
MongoChef
