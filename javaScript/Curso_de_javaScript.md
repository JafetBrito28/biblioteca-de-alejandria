
Curso de JavaScript 

loops: while 

la ultima opcion que tenemos para genera un loop 
el while

en la consola del navegador, 
antes de utilizar el while
deben de generar el array 

var estudiantes = ["maria", "sergio", "rosa", "Daniel"];

function saludarEstudiantes(estudiante){
	console.log('Hola, ${estudiante}');
}

Tienes que repasar esa clase

pero vamos a los objects

en esta clase vamos a entender que son los objetos
javascript esta en paradigma de objetos

como llevamos un objeto del mundo fisico al paradigma
de javascript. 

objecto, propiedades...

como yo escribo un objeto en javascript 

var miAuto = {
  marca: "Toyota",
  modelo: "Corolla",
  annio: 2020,
  detalleDelAuto: function(){
         console.log(´Auto ${this.modelo} ${this.annio}´);
	}
};

miAuto.marca
miAuto.annio
miAuto.detalleDelAuto();

Que pasa si quieres generar 30 carros 

... una funcion constructora. 

sus parametros sus propiedades. donde vamos a poner un ejemplo 

ya estando en la consola 

var miAuto = {
	marca: 
	modelo:
};





function auto(marca, modelo, annio) {
	this.marca = marca; 
	this.modelo = modelo;
	this.annio = annio;
	}
 

var autoNuevo = new 

un objeto que genera otro objeto. 

la capacidad de crear objetos, 
de rellenar una base de datos de objetos 
escritos en javascript 

interesante, en verdad que es muy interesante 

esto ya lo habia visto en react, 
veamos que de alguna manera, tienes una array 
entonces puedes tener un array de carros por ejemplo 

var articulos es lo que citan aqui 

var articulos = [
	{nombre: "bici", costo: 3000 
	{nombre: "bici", costo: 3000 },
	{nombre: "bici", costo: 3000 },
	{nombre: "bici", costo: 3000 },
	
	];

FILTER validar si algo es verdad o falso 

var articulosFiltrados = articulos.filter(function(articulo){
	return articulo.costo <=500
	});

var nombreArticulos = articulos.map(function(articulo){
	return articulo.nombre
	});


// el metodo filter () devuelve los valores concidentes
en una matriz de la coleccion. verificara todos los valores
de la coleccion y devolvera los valores coincidentes
en una matriz. 