```javascript
class God {
	constructor(name) {
		this._name  =  name;
	}
	
	get name() {return this._name;}
	set name(newName) {this._name = newName;}
	getName() {return this._name;}
	
};

class Human extends God	{
	static  tagline  = ['Pray','Work','Learn','Play','Party','Grateful','Repeat'];
	
	constructor(name) {
		super(name);
	}
}

// Example usage:
console.log('Hello World!');
const beta = new Human('Beta Priyoko');
console.log('My Name:', beta.getName());
console.log('Tagline:', Human.tagline);
```
