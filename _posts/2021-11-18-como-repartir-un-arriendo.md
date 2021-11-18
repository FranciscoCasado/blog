---
layout: post
title: "Cómo repartir el arriendo entre varias personas y el diseño de juegos" 
tags: ideas
summary: "
Todos los días consumo podcasts y videos en youtube y, cada tanto, aprendo cosas que me fascinan por lo sencillas que son, pero lo complejo de los problemas que resuelven. Hace pocos días estaba escuchando mi podcast favorito de *diseño de juegos*, [Ludology](https://ludology.libsyn.com/), y mencionaron *cómo repartir un arriendo.*
"
---

___¿Qué tiene que ver repartir el pago de un arriendo con un juego?___ 

A continuación explico en detalle y el algoritmo lo describo en la última sección de este post. Es muy sencillo y *astuto*.

## El diseño de juegos
Desde hace un tiempo que he estado aprendiendo harto sobre *diseño de juegos*, que es algo así como *de qué manera combinamos historias, personajes y mecánicas para generar una experiencia entretenida*. Dentro de esta disciplina -que se estudia a nivel universitario y se ejerce profesionalmente desde el siglo pasado- hay un vasto conjunto de elementos que le van dando sabor y ritmo a cada juego, pero nada tiene un impacto tan inmediato y característico como *las mecánicas*.

Las mecánicas son las reglas y procedimientos que se realizan en un juego y se estudian en profundidad ya que generan situaciones de tensión y resolución de conflictos de manera mucho más *efectiva* que la *historia* que tenga el juego. por ejemplo Un juego puede tener una premisa *entretenida*, como Monopoly, pero un conjunto de mecánicas que hacen que nadie la pase bien. Así como *UNO* tiene mecánicas más intrincadas, pero que generan momentos muy emocionantes en una partida, a pesar de no haber historia ni personajes. 

Hay libros completos dedicados al estudio de las mecánicas. Para juegos de mesa, por ejemplo, Geoff Engelstein (quien también participa del podcast y hace clases en NYU!) tiene un compendio de mecánicas en su libro *Building Blocks of Tabletop Game Design: An Encyclopedia of Mechanisms*.

En el podcast, Geoff analiza cómo las estrategias para un pago de arriendo *justo* puede generar mecánicas de juego interesantes.

## Ya, pero ¿porqué repartir el arriendo es interesante para los juegos?
Si alguna vez has tenido que compartir un gasto grande, como un arriendo, probablemente te has topado con que no es sencillo determinar cuánto tiene que pagar cada persona.

A priori, uno podría definir un cobro igual por los espacios comunes y cada persona luego paga un proporcional por el espacio de uso exclusivo (como las piezas y baños *en suite*). ¿Pero y si los tamaños son iguales y una pieza recibe más luz que la otra? ¿Cuál vale más? ¿Ambas personas valoran en igua medida tamaño, iluminación, ruido, etc.?

Suena como a participar de una subasta, ¿o no? ¿cómo se resuelven estos *conflictos* de manera justa? El episodio del podcast cierra con la siguiente frase: *"Esto definitivamente es una mecánica que podría usarse en un juego"*.

## El algoritmo
Supongamos que dos amigues, Tulio y Juanin, compartirán un arriendo que, en total, vale $500 (en las unidades monetarias que quieras). Es un departamento y tiene dos piezas: una con un ventanal grande, muy luminoso, y otra con una ventana más pequeña y que le da sombra todo el día.

Para resolver cuanto pagará cada une, deben hacer lo siguiente:
1. Anotar cuanto estarían dispuestos a pagar por usar cada una de las habitaciones, considerando que la suma de todos los precios sea igual a la suma del total del arriendo ($500). 
Supongamos que Tulio valora mucho más la habitación luminosa, mientras que Juanín es más indiferente:

|        | Luminosa | Sombría |
|--------|----------|---------|
| Tulio  | $300     | $200    |
| Juanín | $250     | $250    |

2. Cada habitación es adjudicada a la persona que le puso el precio más alto. En este caso, Tulio se queda con la luminosa, pues le puso un precio de \$300, mientras que Juanín se queda con la sombría, pues le puso un precio de \$250.

3.  ¿Cuánto debe pagar cada une? El promedio que eligieron para cada habitación:

|        | Habitación | Precio indicado | Precio a pagar |
|--------|------------|-----------------|----------------|
| Tulio  | Luminosa   | $300            | (300+250)/2 = **$275**           |
| Juanín | Sombría    | $250            |(200+250)/2 = **$225**           |

Acá se ve lo bacán del agoritmo: cada une termina pagando **menos** que el valor que indicó y, en suma, se paga el arriendo completo.

Ahora bien, alguien podría querer ofrecer un precio más bajo por la habitación con la que cree que se quedará, para así bajar lo más posible el precio a pagar. Sin embargo, este metodo favorece la *honestidad*, ya que bajar el precio de la habitación que quiero, hace que suba automáticamente mis chances de obtener la pieza que NO quiero, pues para bajar el precio a una, hay que subirle el precio a otra. Por lo tanto, lo mejor es poner el interés real por cada una de las piezas, para pagar lo justo por lo que sí se quiere.



*Simple y entretenido... ¿o no?*