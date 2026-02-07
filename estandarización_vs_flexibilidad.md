# Estandarización Vs. Flexibilidad

<svg viewBox="0 0 900 700"
     width="400"
     height="400"
     xmlns="http://www.w3.org/2000/svg"
     style="font-family:Arial,sans-serif">

  <!-- Marco -->
  <rect x="200" y="0" width="600" height="600" fill="#ffffff" stroke="#000"/>

  <!-- Ejes (el "+") -->
  <line x1="500" y1="0" x2="500" y2="600" stroke="#000" stroke-width="2"/>
  <line x1="200" y1="300" x2="800" y2="300" stroke="#000" stroke-width="2"/>

  <!-- ===== ETIQUETAS EJES ===== -->

  <!-- Etiqueta eje Y -->
  <text x="0" y="300"
        font-size="34"
        font-weight="bold"
        dominant-baseline="middle">
    Flexibilidad
  </text>

  <!-- Etiqueta eje X -->
  <text x="500" y="645"
        font-size="34"
        font-weight="bold"
        text-anchor="middle">
    Estandarización
  </text>

  <!-- ===== CUADRANTES ===== -->

  <!-- Arriba izquierda -->
  <text x="350" y="170" font-size="34" text-anchor="middle">
    Caos (1)
  </text>

  <!-- Arriba derecha -->
  <text x="650" y="170" font-size="34" text-anchor="middle">
    ¡Éxito! (3)
  </text>

  <!-- Abajo izquierda -->
  <text x="350" y="455" font-size="34" text-anchor="middle">
    Ordeno y
  </text>
  <text x="350" y="490" font-size="34" text-anchor="middle">
    mando (2)
  </text>

  <!-- Abajo derecha -->
  <text x="650" y="455" font-size="34" text-anchor="middle">
    ¡Esto es
  </text>
  <text x="650" y="490" font-size="34" text-anchor="middle">
    código! 😋
  </text>

<!-- ===== FONDOS CUADRANTES ===== -->

<!-- Arriba izquierda -->
<rect x="200" y="0" width="300" height="300" fill="#ff4d4d" opacity="0.05"/>
<!-- Arriba derecha -->
<rect x="500" y="0" width="300" height="300" fill="#7CFF7C" opacity="0.20"/>
<!-- Abajo izquierda -->
<rect x="200" y="300" width="300" height="300" fill="#ff4d4d" opacity="0.05"/>
<!-- Abajo derecha -->
<rect x="500" y="300" width="300" height="300" fill="#39ff14" opacity="0.03"/>

</svg>

- (1) Si en lugar de "caos" dices "fluir", parece que es bueno... pero NO. No cuela 😅. Salvo que estés pintando cuadros abstractos, o alguna actividad artística similar.
- (2) Te lo ha mandado tu jefe "porque él sabe". Si realmente sabe, ¿qué pasará con ese conocimineto cuando se jubile o cuando le pille un tractor? Y si te ha mandado una soplapollez, ¿será porque no conoce [la mítica frase de "Esteban Curritos"](https://www.reddit.com/r/quotes/comments/1no01a4/it_doesnt_make_sense_to_hire_smart_people_and/?tl=es-419)? 😋
- (3) **¡Un proceso para humanos bien definido y al mismo tiempo flexible, felicidades!**

## ¿Cómo estandarizar?

Los cuadrantes de la derecha requieren más explicación.

La única manera de **estandarizar** es **definir procesos**. Un proceso son **entradas, pasos y salidas**. Diferenciemos **dos tipos de procesos**, según quién los consume:
- **Procesos consumidos por máquinas**. Cuadrante de abajo a la derecha. O bien están implementados en código, o bien son flujogramas en un software de workflows que ejecuta automatismos. Definir bien el proceso aquí es el reto de toda la vida; si no entiendes los pasos correctos, no serás capaz de establecer los requisitos funcionales que después los desarrolladores van a implementar. Ya hay muchísima literatura y marcos de trabajo al respecto (Agile/Scrum/Kanban, DevOps, XP, BPMN, Lean, CMMI, etc etc etc...); no puedo aportar nada nuevo.
- **Procesos consumidos por humanos**. Cuadrante de arriba a la derecha. Aquí es donde veo el mayor reto, y <span style="color:coral">veo mucho espacio de mejora</span>; o al menos, no soy capaz de encontrar papers sobre lo que tengo en la cabeza. Lo desarrollo en el siguiente apartado.

<mark>Trabajo en curso a partitr de aquí...</mark>

## Procesos consumidos por humanos

**Definir un proceso para humanos/agentes no implica matar la flexibilidad.** Eso sólo ocurre si defines cada minúsculo detalle, si cubres todas las infinitas posibilidades. Pero eso no es un proceso; es o bien código, o bien un flujograma infumable. En el segundo caso, suponiendo que sea correcto y que sea automatizable, ¿a qué esperas para meterlo en algún software de workflows para que lo ejecute una máquina? Y si no es automatizable, más vale que lo sustituyas por un proceso declarativoa a más alto nivel, porque lo que tienes ahora no se lo va a leer ni el tato... 😎

Si defines el proceso a un nivel de abstracción adecuado, evitarás el caos. Si defines el "qué", dejando al mismo tiempo la flexibilidad de ejecutar cada paso de diferentes maneras —el "cómo"—, estarás en el cuadrante bueno 😉. Para ello, te puede ayudar aplicar el principio declarativo de desarrollo de código a procesos para humanos/agentes 👌... 

## El papel de la IA agéntica

**Cómo encaja la IA agéntica en todo esto?**
Desde 2023, la IA agéntica juega un interesante papel que oscila entre ambos cuadrantes. Una gaente de IA, siendo muy ambicioso, asume el rol de "humano", y por tanto puede leer Hay casos de uso con "mucho código y algo de agéntica para 


<br>

___
6 feb 2026+
