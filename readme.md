# ISDI Pizzería
## Antecedentes
Durante el año 2015, ISDI decidió abrir una pizzería para ayudar a sus estudiantes a pasar las tardes y noches 
de estudio de una forma más amena, ofreciendo pizzas con una buena materia prima y buen precio.

Tras todo lo acontecido en los últimos años, ISDI se plantea volver a abrirla, pero esta vez quiere mejorar varias cosas.
Se ha encontrado con una base de datos perdida que tiene información y con esta captura que informa un poco de cómo está
todo originado:

![DDBB esquema](ISDIPizzeriaSchema.png)

El equipo encargado de la explotación de este proyecto no tiene muy claro (todavía) qué uso se le puede dar a los datos
que hay en esta base de datos. Por ello, vamos a realizar unas búsquedas para ofrecer valor y sugerencias.

### Prospección básica
Vamos a realizar una búsqueda rápida en todas las tablas para saber qué información tenemos.

Necesitamos saber qué pizzas se han estado haciendo. Un listado de esas pizzas:

¿Y cuántas son?


¿Cuántos ingredientes utiliza cada pizza?

Y ordenadas de mayor a menor

¿Cuál es el ingrediente más usado en las pizzas?

Las pizzas están agrupadas por Categoría. ¿Cuál es el ingrediente más utilizado en cada categoría?

### Prospección intermedia

¿Qué día se ha tenido mayor número de pedidos?

¿Cuál es la pizza más vendida?

¿En qué rango de horas suele haber mayor número de pedidos?

¿Cuál es el valor medio de los pedido?

¿Cuál es el pedido con mayor valor, qué día y hora se realizaron?

¿Cuáles son las pizzas vendidas cada mes?

### Prospección Avanzada

¿Cuál ha sido el total por cada ingrediente utilizado (Utilizad el valor de un uso de ingrediente para S, 2 para M, 3 para L, etc.)
De esta forma, sabremos el volumen de ingredientes que pueden ser necesarios en la pizzería.

Con esta información, podemos optimizar las pizzas que se utilizan, para ello, hay ciertos ingredientes que no se utilizan.
¿Qué ingredientes y de qué pizzas son?
