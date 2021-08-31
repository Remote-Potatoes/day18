# Mongo Document
```js
const user = {
	_id: 'e0e9r8q24309583490584320958432',
	name: "daniel",
	from: "NL",
}

const wdClass = {
	_id:'aksdjfhsdfkjghdsfkjghsfdkljghdsfkjlghdfkljghfdsiuyt438y5483972uyrkjrhiusjghfdskjgh',
	name: "Web Dev",
	partTime: true,
	students: [
		ObjectId('e0e9r8q24309583490584320958432')
	]
}
```


```mongo
{
	_id: ObjectId(),
	name: String,
	from: String
}

{
	_id: ObjectId(),
	name: String,
	partTime: Boolean,
	students: [ObjectId()]
}
```

The way we are going to implement relations with MongoDB is using a node package called `mongoose`.

MERN stack
MongoDb
ExpressJs
ReactJs
NodeJs

Data

### One to One Relationship
User Document
DNA Document
1 User has 1 DNA
1 DNA is assigned to 1 USER


### One to Many
1 Recipe is assigned to 1 restaurant
1 restaurant can have x recipes

### Many to Manny Relationship
1 Person might have 10 Hobbies
1 Hobby might 10000 people 

1 Book can be written by multiple authors
1 Author can have many books
