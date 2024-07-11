```javascript
class Human {
	static tagline = ['Pray','Work','Learn','Play','Party','Grateful','Repeat'];

	constructor(name) {
		this._name  =  name;
	}
	
	get name() {return this._name;}

	set name(newName) {this._name = newName;}

	getName() {return this._name;}

};

const beta = new Human('Beta Priyoko');
console.log('Name:', beta.getName());
console.log('Tagline:', beta.tagline);
```
