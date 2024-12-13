# Examen 1ª Evaluación

---

Explica a continación cada apartado del examen

Con cada apartado realiza un commit diferente 


## Apartado 1  

---
### Diagrama de Flujo de las Damas  
![diagrama1.png](imgs/diagrama1.png)
![diagrama2.png](imgs/diagrama2.png)

## Apartado 2

---

### Tipo de tablero

```
String[][] tablero={
    {null,"rojo",null,"rojo",null,"rojo",null,"rojo"},
    {"rojo",null,"rojo",null,"rojo",null,"rojo",null},
    {null,"rojo",null,"rojo",null,"rojo",null,"rojo"},
    {null,null,null,null,null,null,null,null},
    {null,null,null,null,null,null,null,null},
    {"negro",null,"negro",null,"negro",null,"negro",null},
    {null,"negro",null,"negro",null,"negro",null,"negro"},
    {"negro",null,"negro",null,"negro",null,"negro",null},
};
```
**El tablero consta de dos colores, *rojo* y *negro***
, las fichas cada vez que avanzan una fila se desplazan una
posicion hacia la izquierda o derecha
porque se mueven en diagonales.


## Apartado 3

---
### Funciones

Para facilitar la compresion del
código se podrian crear tres funciones.  
1. Funcion *recorrerTablero*
2. Funcion *hayFicha*
3. Funcion *tipoDeFicha*

La primera funcion sustituyendo practicamente todo el diagrama  para 
dejar más "limpia" la funcion `main`.  
La segunda sustituyendo la condicion del tercer if: `tablero[i][j] != null`.
Esto porque es mucho más legible el nombre de la funcion que el código sin más   
Finalmente la tercera sustituiria desde `tablero[i][j]==rojo` hasta `j++`
*esto ultimo no incluido*. **Pero deberian hacerse algunas modificaciones si se quiere crear esta funcion**. Aun asi permitiria aumentar la legibilidad del código una vez hechos los cambios.

## Apartado 4

---
### javaDoc
**recorrerTablero**
```
     /**
     * Recorre las distintas posiciones de una tabla 
     * @param tablero tabla que va a recorrer
     */
    static void recorrerTablero(String[] tablero){

    }
```

**hayFicha**
```
/**
* Comprueba que valor hay en una posicion de un tablero
* @param valor valor de una posicion en un tablero
* @return true si el valor no es nulo y false si es nulo
*/
static boolean hayFicha(String valor){
return true;
}
```
**tipoFicha**

```
    /**
     * Comprueba el tipo de ficha que hay en un tablero
     * @param ficha valor de la ficha que hay en una posicion
     * @return tipo de ficha que hay en la posicion
     */
    static String tipoFIcha(String ficha){
        return "rojo";
    }
```