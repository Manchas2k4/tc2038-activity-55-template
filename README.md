![Tec de Monterrey](images/logotecmty.png)
# Actividad 5.5 Implementación A*

## <span style="color: rgb(26, 99, 169);">¿Qué tengo que hacer?</span>
En este repositorio encontrarás el archivo "main.cpp". En este archivo deberás desarrollar la implementación del problema presentado en esta actividad. En la parte superior del archivo coloca, en comentarios, tus datos. Por ejemplo:
```
// =========================================================
// File: main.cpp
// Authors:
//  Edward Elric - A00123456
//  Alphonse Elric - A00124598
// Date: 01/01/2021
// =========================================================
```
Implementa, <span style="text-decoration-line: underline;">en equipos de 2 personas (máximo)</span>, una solución para el problema que se describe a continuación.

## <span style="color: rgb(26, 99, 169);">**Descripción**</span>
Un laberinto se da como una matriz binaria *N* * *N* celdas donde el punto origen es la celda superior izquierda, es decir, la posición [0][0] y el punto destino es la celda inferior derecha, es decir, la posición [*N*-1][*N*-1] . Un Bot (agente virtual) saldrá de la posición origen y tiene que llegar a la posición destino. El Bot puede moverse en cuatro direcciones: 'U' (up), 'D' (down), 'L' (left), 'R' (right). El valor de 0 (cero) en una celda de la matriz representa que esta bloqueada y no se puede cruzar. El valor de 1 en una celda de la matriz representa que se puede cruzar por ahí.

## <span style="color: rgb(26, 99, 169);">**Entrada**</span>
El programa recibe un número entero, *N*, que indica el tamaño de la matriz. A continuación, *N* línea, en cada una de ellas *N* valores 0 ó 1.

## <span style="color: rgb(26, 99, 169);">**Salida**</span>
Deberá desplegar todas las posibles rutas de salida del laberinto.

## <span style="color: rgb(26, 99, 169);">**Ejemplo de entrada**</span>
```
4
1  0  0  0
1  1  0  1
1  1  0  0
0  1  1  1
```

## <span style="color: rgb(26, 99, 169);">**Ejemplo de salida**</span>
```
DDRDRR
DRDDRR

```

Para probar tu implementación, compila tu programa con el comando:
```
g++ -std=c++11 main.cpp -o app
```
Posteriormente, ejecuta tu programa. Para realizar las pruebas, puedes usar las siguientes líneas de código.
```
./app > mysolution.txt
diff mysolution.txt solution.txt
```
Si el segundo comando no tiene ninguna salida, los resultados que obtuviste son los esperados.

## <span style="color: rgb(26, 99, 169);">**¿Bajo qué criterios se evalúa mi evidencia?**</span>

- **80%** - Para cada una de las funcionalidades se evaluará:

    - **Excelente (80%)** - pasa correctamente todos los casos de prueba.
    - **Muy Bien (60%)** - pasa correctamente el 75% de los casos de prueba.
    - **Bien (40%)** - pasa correctamente el 50% de los casos de prueba.
    - **Insuficiente (20%)** - pasa correctamente menos del 50% de los casos de prueba.

- **10%** - El código deberá seguir los lineamientos estipulados en el estándar de codificación: <span class="instructure_file_holder link_holder">[liga_estándar_codificación](estandar.pdf)</span>
- **10%** - Se especifica (en comentarios) la complejidad computacional de cada uno de las funciones desarrolladas.

## <span style="color: rgb(26, 99, 169);">**¿Dónde la entrego?**</span>
Cuando hayas pasado todas las pruebas, recuerda publicar el código en tu repositorio (*git push*).

## <span style="color: rgb(26, 99, 169);">**Importante**</span>
Recuerda colocar el nombre y las matrículas de ambos integrantes en en los comentarios iniciales. En caso de que se incumpla este punto, se penalizará con 20 puntos sobre la calificación obtenida.
