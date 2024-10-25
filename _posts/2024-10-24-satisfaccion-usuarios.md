---
title: Rediseñando En Torno al Usuario
post-image: https://i.pinimg.com/736x/45/f9/bf/45f9bfb0693441cfc3b2a4fd0fa91f0b.jpg
description: Satisfacción usuarios, psicologia de finalización de tareas
tags:
- UX
- UI
---

### ¿Cómo pasé de esto a esto? ¿Y por qué?

<div style="text-align: center;">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/5YAyCRgiSlE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


Esta fue una de las primeras aplicaciones que diseñé y aunque tenía potencial, la  experiencia e interfaz de usuario dejaban mucho que desear. Me incomodaba ver el grid vacío en la pantalla de inicio. Cada vez que la abría, durante mis pruebas, el vacio me causaba  incomodidad,  sentía la urgencia de escanear un producto para llenarlo, una vez que lo hacia, esa sensación disminuia.

Como desarrollador de software se que ser autodidacta es una habilidad crucial en este oficio y he  comprendído que para crear diseños más atractivos y funcionales es fundamental entender las teorias de diseñó de UX y  cómo  las personas interactuan con sus dispositivos. Una de las revelaciones más importantes que encontré en este camino fue sobre la teoria sobre la  satisfacción de los usuarios y en este post quiero profundizar en este tema.

### Tres puntos clave sobre la satisfacción del usuario

**La teoria de la Psicología de la Finalización de Tareas menciona 3 puntos:**

- **Teoría de la Autodeterminación**: Esta teoría postula que los individuos tienen tres necesidades psicológicas básicas: competencia, autonomía y relación. La necesidad de competencia es especialmente relevante aquí, ya que los usuarios buscan sentir que progresan y dominan las tareas. Completar tareas les proporciona una sensación de logro y satisfacción.<br>

- **Teoría del Flujo**: Este concepto, desarrollado por Mihaly Csikszentmihalyi, describe un estado mental donde las personas están completamente inmersas en una actividad. Para alcanzar este estado, las tareas deben ofrecer un desafío equilibrado: ni demasiado fáciles ni excesivamente difíciles. Facilitar la finalización de tareas ayuda a mantener a los usuarios en este estado de flujo, aumentando su satisfacción y compromiso.

- **Refuerzo Positivo**: Completar una tarea actúa como refuerzo positivo. Cuando los usuarios logran, por ejemplo, ingresar un alimento en tu aplicación, experimentan una liberación de dopamina, lo que les brinda una sensación de recompensa y satisfacción.

Comprender la psicología de la finalización de tareas y sus componentes me permitió mejorar el diseño de la interfaz de usuario (UI) de esta aplicación.

Como es sabido, el diseño de experiencia de usuario no solo se aplica al desarrollo de software sino a todo tipo de producto con el cual la personas interactuamos. Esto me remontó a mi niñez y a un producto en especifico. los albunes de vistas de mundiales y ánime de Panini. Al pensar friamente en ese producto y analizarlo a la luz de lo descrito por la psicología de finalizacióm de tareas, basicamente entregaban a los niños un album con 250 espacios vacios numerados y que al llenarlos  otorgaba un sentido de autodeterminación, tareas simples y refuerzos positivos.

<div style="text-align: center;">
  <img src="https://i.pinimg.com/736x/1a/1d/f4/1a1df43dd9477eb7c2d6409226de1160.jpg" alt="Descripción de la imagen" style="max-width: 100%; height: auto;">
</div>

### Rediseñando
En la pantalla principal de mi aplicación, decidí replicar este enfoque. En lugar de presentar un grid vacío, creé un grid con contornos que indican dónde debe colocarse un nuevo producto. Además, implementé una disposición aleatoria para cada tarjeta cada vez que el estado de la app cambia, lo que ayuda a reducir la sensación de monotonía.

<div style="text-align: center;">
  <img src="https://i.pinimg.com/736x/66/2d/f1/662df18c9951e1b852cb7838b6a6e276.jpg" alt="Descripción de la imagen" style="width: 375px; height: auto;">
</div>

Al agregar un producto, se llena un espacio vacio y los demás continuaran en blanco.

<div style="text-align: center;">
  <img src="https://i.pinimg.com/736x/55/6d/ef/556def427b2020645731053c73515cc5.jpg" alt="Descripción de la imagen" style="width: 375px; height: auto;">
</div>

Por defecto la aplicación pinta 6 espacios vacios inicialmente, cuando el usuario llena los 6 espacios en blanco predefinidos, el app crea siempre uno adicional en blanco para tratar de mantener la motivación del usuario.

<div style="text-align: center;">
  <img src="https://i.pinimg.com/736x/5e/96/24/5e96248ef49d78e83c53d4b18df39d7e.jpg" alt="Descripción de la imagen" style="width: 375px; height: auto;">
</div>

Este  cambio fue el resultado de la mezcla de una pequeña investigación, creatividad y algunos recurdos de la niñez. Me parece adecuado mencionar que además de esta teoría, hay muchas más que implementaré en futuros desarrollos y que documentaré en nuevos post con el objetivo de ayudar a la comunidad.

Quiero concluir detallando un poco el impacto que causa  la satisfacción en los usuarios que utilizan una aplicaciónes diseñadas con este enfoque.

- **Satisfacción del Usuario**: Cuando los usuarios logran completar tareas con facilidad, su satisfacción general aumenta. Se sienten en control y capaces, lo que se traduce en una experiencia de usuario positiva.

- **Lealtad a la Marca**: La satisfacción del usuario frecuentemente conduce a una mayor lealtad a la marca. Si los usuarios encuentran que tu aplicación facilita el seguimiento de su alimentación y se sienten motivados a interactuar con ella, es más probable que continúen usándola y la recomienden a otros.

Como desarrolladores  de aplicaciones moviles, es crucial que los  productos que creamos generen satisfacción a los usuarios que los utilizan. Desde ese punto de vista creo que este nuevo diseño es una mejora significativa al producto, cuyo resultado solo el tiempo podrá juzgar como efectivo o ineficaz.
