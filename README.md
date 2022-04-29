# Assignment-2

An object in JavaScript is a collection of key-value pairs. Each key-value pair is called as a property. A property can be a function, an array, an object itself or any primitive data type i.e. integer, string, etc. Functions in object are called as methods.
Example
var human = {
	firstName: "Virat",
	lastName: "Kohli",
	age: 30,
	fullName: function(){
		return this.firstName + " " + this.lastName		
	}
}

Here firstName, lastName, and fullName are properties of the same object i.e. human. firstName is the key and Virat is the value of the property.
human.firstName; //Output: Virat

human.fullName(); //Output: Virat Kohli
