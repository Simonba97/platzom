# PLATZOM

Platzom es un idioma inventado para el desarrollo del curso de fundamentos de javascript; éste es el primer proyecto que se ejecutará en el mismo.

 Realizado por [Simón Bustamante Alzate](https://instagram.com/simonba97)

 ## DESCRIPCIÓN DEL IDIOMA

 - Si la palabra termina en "ar", se quitan esas dos letras.
 - Si la palabra inicia con "Z", se le añade "pe" al final.
 -Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio.
 -Si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y minúsculas.

 ## INSTALACIÓN

```
 npm intall platzom 
 ```

 ## USO

 ```
 import platzom from 'platzom'

 platzom("Programar") //Program
 platzom("Zorro") //Zorrope
 platzom("abecedario") //abece-dario
 platzom("sometemos") //SoMeTeMoS
 ```

 ## CRÉDITOS
 - [Simón Bustamante Alzate](https://instagram.com/simonba97)

 ## LICENCIA 

 [MIT](https://opensource.org/licenses/MIT)


