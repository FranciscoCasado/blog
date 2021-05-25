---
layout: post
title: Empecé a hacer este sitio
tags: how
summary: "
Un poco de vanidad, las buenas influencias de la cultura **OpenSource** y la incerteza laboral hicieron que decidiera comenzar este sitio.<br>


Aquí pretendo compartir las cosas que hago, como cualquier otro blog. El dominio principal [www.franciscocasado.cl](https://franciscocasado.cl/) lo he dejado como *portafolio*.<br>


En este post cuento por qué lo empecé, cómo escogí el dominio y *-bien a grandes rasgos-* como funciona esta página
"

---
## Por qué lo empecé
Hace dos meses tuve dudas de mi presente y futuro laboral en este escenario incierto que ha traido la pandemia y, dentro de todas las cosas que reflexionaba, una de las ideas que más se repetía era la de prepararme para buscar trabajo.

Nunca me ha gustado mi curriculum y en estos tiempos entiendo poco que exista haya que enviar un documento si, en su lugar, puedo tener un portafolio siempre disponible para cualquiera, al alcance de un click. Se usa harto en el diseño, el arte e incluso el desarrollo de software, pero en la *ingeniería*, no mucho. Así que me decidí a hacer mi propia página para alojar mi portafolio.

## El dominio
Lo primero que pensé quiero *dejar una marca*, de manera que sea difícil olvidar donde encontrar esta información. Como mi apellido es llamativo y no tan fácil de olvidar, pensé en que esa sería mi marca, al fin y al cabo, la llevo usando de manera involuntaria desde que tengo memoria... pero el dominio `casado.cl` ya tenía un dueño (alguien que no conozco, con una página web incompleta y que cada vez que reviso, renuevan la titularidad por más años que la vez anterior >:c ).

Después de las reflexiones de hace dos meses, pensé *"va a tener que ser mi nombre no más"* y así fue como compré el dominio `franciscocasado.cl`. Además, tenía ganas de tener un correo de contacto *bacán* y no un `@gmail` genérico (también están todas las combinaciones de mi nombre e iniciales ocupadas). Y por supuesto que es `.cl` y no `.com`, ni cualquier comodín de GoDaddy.

## Cómo funciona esta página
Esta página y mi portafolio están construidas con la integración de GitHub Pages y [Jekyll](https://jekyllrb.com/), usando el tema [Hyde](https://github.com/poole/hyde), creado por [Mark Otto](https://github.com/mdo). El código de esta página se encuentra en [este repositorio](https://github.com/FranciscoCasado/blog).

La gracia de Jekyll es que para escribir estos posts solo tengo que crear un archivo `.md` en la carpeta `_posts`y listo. No tengo que preocuparme del HTML para poblar esta página con contenido. Además, es muy fácil de instalar y correr localmente en mi computador, lo que me permite hacer modificaciones al estilo y el funcionamiento de la página en mi computador y, cuando quiera publicar los cambios, basta con hacer `commit`y `push`y en un par de minutos se actualiza el sitio.

*Actualización: Acabo de leer en la documentación de Jekyll que se pueden crear borradores (`drafts`) para escribir posts, pero que no aparecerán en la vista pública (hasta que sean trasladados a la carpeta `_posts`). Quizás debería haber hecho eso con este post :sweat_smile:*

El dominio está registrado en [NIC Chile](https://www.nic.cl/) y el servidor de nombre (DNS Server), que se encarga de enrutar el dominio `franciscocasado.cl`y el subdominio `blog.franciscocasado.cl` al contenido que subo a GitHub Pages, usa FreeDNS.

