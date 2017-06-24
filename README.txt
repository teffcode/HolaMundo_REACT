PASOS PARA CREAR UN HOLA MUNDO CON REACT.JS

1. Crear index.html en editor de texto (Yo uso sublime)
2. Descargar las librerías de react en https://cdnjs.com/libraries/react
	- Librería 1: react.js -> Para CREAR los componentes
	- Librería 2: react-dom.js -> Para USAR los componentes
3. Copiar (copy script tag) las librerías en el <body>
4. Crear <script> con una función Hola(Props) en donde:
	- PROPS: Objeto que hace referencia a los datos que 
		queremos pasarle al componente al momento de
		inicializar la app.
	- Se crea un const name = props.name -> que es un dato nombre
	- Luego se retorna React.DOM.h1 -> el tag h1 es porque 	
		queremos que se visualice
	- Id: 'Title' -> el identificador del tag h1
5. Se instancia el componente -> es decir, se le da VIDA al objeto
	- Se instancia: const hola = React.createElement(Hola, {name: 'Mundo'})
		NOTAR que tiene 2 parámetros, el primero es la función y
		el segundo es el PROPS
6. Mostrar lo realizado en la UI (User Interface) con ReactDOM
	- Se muestra en la UI con el método render()
7. Finalmente, se crea el elemento id app en el tag <main>
8. EJECUTAR EN EL NAVEGADOR 👩🏻‍💻  
