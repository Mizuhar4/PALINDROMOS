# PALINDROMOS
trabajo grupal

Integrantes: Benjamin Fernandez - Yoandri Villarroel - Alex Saez

------------------------------------------------------------ Paso 1 ------------------------------------------------------------

¿Qué hace el método?

R: Este metodo toma una cadena de texto en la entrada y en la salida retorna la comparacion entre la cadena invertida y la cadena ingresada.

¿Cómo lo hace?

R: primero crea una variable "resultado" siendo una cadena vacia, luego cambia el resultado diviendo la cadena con el .split(''), luego usa el reverse() para que la cadena dividida se invierta de posicion y luego lo vuelven a unir usando el .join(''). Por ultimo la cadena se compara con el resultado, siendo que si estos son iguales entonces seria un palindromo o en caso contrario, no lo seria.

¿Como lo uso?

R: Llamando el metodo esPalindromo() y darle una cadena de texto como argumento, lo cual con las instrucciones dentro del metodo se comparará la cadena con el resultado para devolver si es palindromo o no.

ejemplo:

-como cadena de texto usaremos la palabra "oso".

-al ingresarelo, las instrucciones del metodo invertiran la cadena de texto usada en el argumento.

-por ultimo se compara la cadena de texto principal en este caso "oso" la cual se comparará con la cadena invertida por lo cual retornara si es un palindromo o no.

------------------------------------------------------------ Paso 2 ------------------------------------------------------------

Benjamín Fernández: ![palindromo](https://github.com/BenjaFA/PALINDROMOS/assets/142475169/cc9ddee8-aedf-4a63-bed1-14d9ea0327a7)


Alex Sáez: ![image](https://github.com/BenjaFA/PALINDROMOS/assets/135442605/6a54467b-af11-4923-910a-85705f806b6e)


Yoandri Villarroel: ![Captura pantalla](https://github.com/BenjaFA/PALINDROMOS/assets/142508978/dfcf4536-2d69-4976-b5d4-d0e3251ccdc3)


------------------------------------------------------------ Paso 3 ------------------------------------------------------------

3.2: Los posibles casos criticos son: entrada vacia o nula, mayusculas o minusculas, espacios en blancos, caracteres especiales (@&$%) y entrada de numeros

3.4 ![image](https://github.com/BenjaFA/PALINDROMOS/assets/135442605/dafc14d4-7602-44d1-8d12-73cdd06164ea)
 

------------------------------------------------------------ Paso 4 ------------------------------------------------------------

4.1:

- Caso de prueba 1:
Input: 200 (número entero)
Output: ????
caso prueba 1: falso

- Caso de prueba 2:
Input: “” (cadena vacía)
Output: ????
caso prueba 2: falso

- Caso de prueba 3:
Input: “aaabccbaaa”
Output: ????
caso prueba 3: verdadero

- Caso de prueba 4:
Input: “ahabccbaaa”
Output: ????
caso prueba 4: falso

- Caso de prueba 5:
Input: “La tele letal”
Output: ????
caso prueba 5: falso


4.2:

¿Que consideraciones tomaron en cuenta?

R: Consideramos las entradas de numeros, entradas vacias y con espacios.

¿Que mejoró en su método?

R: la resistencia a posibles errores los cuales no podian ser tomados como argumentos anteriormente.

¿Qué rol jugaron las pruebas en mejorar su codigo?

R: nos dieron una mejor vision en como podriamos implementar en nuestro cdigo añadiendo excepciones.



            //                        REPOSITORIO COMUNITARIO

            
![reposi comu](https://github.com/BenjaFA/PALINDROMOS/assets/142475169/72cc6aa6-3b54-483b-b587-a40f2898f57e)



------------------------------------------------------------ Paso 5 ------------------------------------------------------------

Conclusion: Gracias a las pruebas unitarias podemos transformar un metodo que tenga varios erroes en un metodo mas estable contra errores, ademas, nos permite mejorar en el analisis de
situaciones criticas en diferentes metodos, por lo tanto, las pruebas unitarias es una parte importante en el testing de codigo.


------------------------------------- Resultado final del metodo y las pruebas unitarias -------------------------------------

![image](https://github.com/BenjaFA/PALINDROMOS/assets/135442605/33b2d60e-496b-49c1-a3fc-5c34dc71d694)

![image](https://github.com/BenjaFA/PALINDROMOS/assets/135442605/9d4c9ed8-5fed-461f-ab6b-864a7b9f57e4)

![image](https://github.com/BenjaFA/PALINDROMOS/assets/135442605/84d9fa61-4166-4b2a-88a9-e2d121e6d119)

Resultado de pruebas unitarias:

![image](https://github.com/BenjaFA/PALINDROMOS/assets/135442605/8505a02a-acd1-41d7-9860-ad390fa2f253)


