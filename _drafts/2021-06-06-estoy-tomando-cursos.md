---
layout: post
title: Estoy tomando un curso de desarrollo web y otro de aprendizaje de máquinas
tags: ideas
summary: "
Creo que era una deuda que tenía con mis estudios y ahora que llevo 1 mes de haber empezado, se me están ocurriendo ideas y proyectos para hacer y es bacán <3.
"
---

Trabajé un tiempo en una empresa de software, con un equipo de desarrollo súper bacán, pero al que entré luego de varios cambios en mis labores, pues al principio hacia mejoras de software y hardware a un dispositivo de que vivía en un mundo de desarrollo casi aparte. En ese tiempo era mañoso (más que hoy) y decía que no me gustaba tanto programar... una de las mentiras más grandes que me he dicho a mi mismo y que, gracias a los cursos que empecé a tomar, logré darme cuenta.

Mientras estudiaba ingeniería, tuve que programar siempre y n casi todos los ramos. Las tareas que más me gustaban no eran las de resolver ecuaciones y ni hacer desarrollos matemáticos, sino las que involucraban programar (principalmente en Python, Matlab y C). Ahora miro hacia el pasado y pienso *por qué cresta pensaba que no me gustaba?*. Sólo recuerdo que la pasaba mal cuando me pedía una tarea en un lenguage (ni siquiera podía hablar de *framework*) que tenía que aprender de manera autodidacta, sin entender qué estaba pasando y sólo preocupándome de que el *output* fuera lo que me pedían: súper fome aprender así.

Ahora que estoy tomando los cursos, me encanta comprobar que: 1) me ha costado repoco retomar los fundamentos y conceptos clave y 2) no tener que hacerlo por obligación, sin deadlines anti-pedagógicos y con el *acompañamiento* que ofrencen las plataformas online, esto es bacán y se siente súper gratificante avanzar, aunque sea una clase a la semana.

El de desarrollo web está en [Udemy](https://www.udemy.com/course/the-web-developer-bootcamp/) y el de aprendizaje de máquinas está en [Coursera](https://www.coursera.org/learn/machine-learning). El primero lo compré en oferta a ~12 lucas y el segundo es gratis, pero luego puedo pagar ~70 dólares para obtener el certificado de -ni más ni menos que-la Universidad de Stanford.

## Se me están ocurriendo ideas
Mi trabajo actualmente tiene poco de *hacer* y mucho menos de *programar*, lo que me está pasando la cuenta. Hace poco me compré una impresora 3D y me cambió la vida (tengo pendienten u post sobre eso), así que con eso ahora puedo *hacer*. Pero, por otro lado, lo más avanzado que tenido que programar han sido un par de hojas de cálculo que vinculan respuestas de formularios que usamos para hacer evaluaciones. 

### ¿Cómo agilizar la socialización de proyectos de estudiantes?
Cada vez que tengo que implementar una nueva evaluación (todos los semestres) me digo a mi mismo "si supiera hacer aplicaciones webs, no tendría que pelear con las mañas de estas tablas". No es que no me guste, pero definitivamente podría hacer una aplicación simple para poder sistematizar instrumentos de evaluación pedagógica, que actualmente tienen un costo humano enorme.

En concreto, en un curso flexible de proyectos diversos (~60 a ~90 estudiantes, distribuidos en ~20 equipos por cada semestre) tiene hoy en día el siguiente problema:
- Antes de la pandemia existían hitos de evaluación que tenían como propósito principal poder socializar los proyectos. Esto se hacía con presentaciones en una sala grande, con presentaciones y feedback cronometrado.
- Ahora no se puede y tener una sesión de ~3 horas de presentaciones es un despropósito. Ni siquiera nos entusiasma como equipo docente

### Actualmente lo hacemos así
Pedimos que la entrega sea un video de máximo 4 minutos (a veces cambiamos ese número), que lo suban a algún servicio en la nube y que nos manden el link. Luego, el equipo docente se manda sus maratones respectivas de correcciones, pero en paralelo **asignamos 2 a 3 videos a cada equipo para que elles mismes los vean y den retroalimentación a sus compañeres**. Esto ocurre más o menos así
- Centralizamos todos los enlaces
- Conocemos, a rasgos generales, los temas de cada proyecto y les asignamos: un video de un equipo con temas similares y un video de un equipo totalmente diferente. A veces le agregamos un tercero si es que tienen información afin.
- Publicamos la asignación de videos en una tabla que se interpreta así: *"si estás en el equipo `bellota`, te toca ver los videos de los equipos `bombón` y `burbuja`"*. Esta tabla contiene los enlaces de los equipos, para que sea más rápido llegar a ellos.
- Luego, le pedimos a cada estudiante que, mediante un formulario de google, ingresen su retroalimentación, según 2 a 3 items que definimos con el equipo docente.

El "problema" del formulario es que cada persona debe declarar a qué equipo pertenece y a qué equipos va a evaluar, pues necesitaremos hacer llegar ese feed-back al otro equipo, posteriormente, además de tener a mano la lista de asignaciones y enlaces.

### Desarrollo web al rescate -eventualmente-
Si U-Cursos tiene una [sistema de autenticación](https://github.com/Ucampus/upasaporte-server-demo), la asignación de videos es manual (pero "rápida") y lo único que necesitamos es que les estudiantes llenen formularios, en base a esa asignación, entonces una aplicación web hace la pega súper rápido. 

De lo que aprendí en el (anti)curso autodidacta de Ruby on Rails de mi trabajo anterior, es que lo más complejo (*¿quizás?*) es generar una vista para configurar cada evaluación, sus preguntas y qué grupo revisa a cual. Todo lo demas es escritura y lectura sencilla en una base de datos relacional.

Tengo hartas ganas de hacerlo... espero poder hacerme el tiempo eso sí jajajaj
