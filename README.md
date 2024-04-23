# Arrays_JS

- Un array es una zona de almacenamiento continuo, donde se puede introducir varios valores, cada uno de ellos ubicado por la posición que ocupa en el array, también son denominados o conocidos arreglos o vectores y cuando son de dos dimensiones son llamados matrices.

- Los arrays nos brindan la capacidad de almacenar una coleccion de elementos y acceder a ellos de manera individual. 

- Cada elemento se identifica mediante su posición en el array de manera **índice** y estos indices son siempre secuenciales en Javascript son altamente flexibles en términos de los diferentes tipos de datos quepodemos almacenar en cada posición del array.

## Crear un array 

1. Declarando un array con elementos en linea.

```Javascript
let miArray = [1, 2, 3]
console.log("--------------------");
console.log("Arrays en Javascript");
console.log("--------------------");
console.log("1. Declarando un array con elementos en lines");
let miArray = [1, 2, 3];
console.log(miArray);
```

2. Declarando un array con la sintaxis **new array()**

```Javascript
let miArray2 = new Array (1,2,3);
console.log(miArray);
```

3. Declarando un array con un tamaño especifico utilizando la sintaxis **new array** y asignando valores despues:

```Javascript
let miArray3 = new Array (3);
miArray[0] = 1;
miArray[1] = 2;
miArray[2] = 3;
console.log(miArray3);
```

4. Declarando un array con elementos de diferentes tipos de datos

```Javascript
let miArray3 = [1, "dos", true, {nombre: "Juan", edad:30}];
console.log(miArray4);
```

5. 
