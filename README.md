
# Controladores P, PI y PID - Método: 0ptimización por enjambre de partículas

Controladores P, PI y PID para funciones de transferencia de primer y segundo orden utilizando el método de optimización por enjambre de partículas.




![Logo](https://docs.servicestack.net/img/pages/apps/jupyter-python.png)


## Descripción

Utilizando la librería EP, se diseñaron controladores P, PI y PID, según las condiciones requeridas para el proceso, ya sea eliminación de error en esta estable, minimizar tiempo de establecimiento, máximo pico, o cualquier otra condición que se desee. Se define la cantidad de iteraciones según el tipo de controlador, sin usar parada temprana para tener obtener la mayor optimización posible, esta se dá por el método de minimizar optimización.
El desempeño del controlador se compara con el lazo cerrado de la función de transferencia para poder evaluar la respuesta del enjambre de partículas.

