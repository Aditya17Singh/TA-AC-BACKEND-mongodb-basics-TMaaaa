writeCode

Write code to:-

- create a database named `mountains`
use mountains
- a collection inside that database named `himalayas`
db.createCollection("himalayas")
- insert 1 document into that collection `{name: 'Dhauldhar range', height: '4000 mtrs'}`
db.himalayas.insert([{}])
- insert multiple document using insertMany command
db.himalayas.insertMany([{}])
- find all documents from mountains
db.himalays.find()
- find a single document using name
