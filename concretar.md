# Concretar = delimitar + detallar

<svg viewBox="0 0 900 700"
     width="400"
     height="400"
     xmlns="http://www.w3.org/2000/svg"
     style="font-family:Arial,sans-serif">

  <!-- ===== LÍNEAS ===== -->

  <!-- Marco -->
  <rect x="200" y="0" width="600" height="600" fill="#ffffff" stroke="#000"/>

  <!-- Eje X -->
  <line x1="200" y1="300" x2="800" y2="300" stroke="#000" stroke-width="2"/>

  <!-- Eje Y -->
  <line x1="500" y1="0" x2="500" y2="600" stroke="#000" stroke-width="2"/>
  
  <!-- Diagonal de concretar -->
 
  <defs>
    <marker id="arrow"
            viewBox="0 0 10 10"
            refX="10"
            refY="5"
            markerWidth="6"
            markerHeight="6"
            orient="auto">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#8400ff"/>
    </marker>
  </defs>

  <line x1="250" y1="550" x2="750" y2="50" stroke="#8400ff" stroke-width="4" opacity="0.5" marker-end="url(#arrow)"/>

  <!-- ===== TEXTO EJES Y DIAGONAL ===== -->

  <!-- Etiqueta eje Y -->
  <text x="50" y="300"
        font-size="34"
        fill="#1f4fd8"
        font-weight="bold"
        dominant-baseline="middle">
    Detallar
  </text>

  <!-- Etiqueta eje X -->
  <text x="500" y="645"
        font-size="34"
        fill="orange"
        font-weight="bold"
        text-anchor="middle">
    Delimitar
  </text>

  <!-- Etiqueta diagonal-->
  <text x="515" y="320"
        font-size="22"
        fill="#8400ff"
        font-weight="bold"
        opacity="0.6"
        dominant-baseline="middle">
    Concretar
  </text>


  <!-- ===== TEXTO CUADRANTES ===== -->

  <!-- Arriba izquierda -->
  <text x="350" y="170" font-size="34" text-anchor="middle" fill="#1f4fd8">
    Detallado
  </text>
  <text x="350" y="205" font-size="34" text-anchor="middle" fill="orange">
    Ámbito abierto
  </text>

  <!-- Arriba derecha -->
  <text x="650" y="135" font-size="34" font-weight="bold" text-anchor="middle" fill="#000000">
    Concreto
  </text>
  <text x="650" y="170" font-size="34" text-anchor="middle" fill="#1f4fd8">
    Detallado
  </text>
  <text x="650" y="205" font-size="34" text-anchor="middle" fill="orange">
    Ámbito delimitado
  </text>

  <!-- Abajo izquierda -->
  <text x="350" y="420" font-size="34" font-weight="bold" text-anchor="middle" fill="#000000">
    Abstracto
  </text>
  <text x="350" y="455" font-size="34" text-anchor="middle" fill="#1f4fd8">
    Superficial
  </text>
  <text x="350" y="490" font-size="34" text-anchor="middle" fill="orange">
    Ámbito abierto
  </text>

  <!-- Abajo derecha -->
  <text x="650" y="455" font-size="34" text-anchor="middle" fill="#1f4fd8">
    Superficial
  </text>
  <text x="650" y="490" font-size="34" text-anchor="middle" fill="orange">
    Ámbito delimitado
  </text>

  <!-- ===== FONDOS CUADRANTES ===== -->

  <!-- Arriba izquierda -->
  <rect x="200" y="0" width="300" height="300" fill="#39ff14" opacity="0.05"/>
  <!-- Arriba derecha -->
  <rect x="500" y="0" width="300" height="300" fill="#7CFF7C" opacity="0.30"/>
  <!-- Abajo izquierda -->
  <rect x="200" y="300" width="300" height="300" fill="#ff4d4d" opacity="0.05"/>
  <!-- Abajo derecha -->
  <rect x="500" y="300" width="300" height="300" fill="#39ff14" opacity="0.05"/>

</svg>

**¡Hay que ser concretos en la vida!** (traaaaanquilo artista 🧑‍🎨, que a ti no te aplica).

Suerte en tu viaje a la esquina superior derecha... 😉


## Ejemplo

Cómo detallar un caso de uso de IA generativa/agéntica:

| Detallar ↓ / Delimitar → | Ámbito abierto | Ámbito delimitado |
|-|-|-|
| **Detallado** | <span style="color:grey">Usaremos IA generativa para mejorar la eficiencia operativa mediante la clasificación de consultas y la redacción de respuestas.</span> | <span style="color:green">Usaremos IA generativa para mejorar la eficiencia operativa mediante la clasificación de consultas y la redacción de respuestas en tickets de primer nivel para el producto X, integrándose con el sistema de ticketing X<sup>1</sup> mediante el protocolo X<sup>2</sup>, garantizando respuesta en idiomas español e inglés, con referencias exclusivamente a la base de conocimiento interna X<sup>3</sup>, con validación humana obligatoria antes del envío por parte de cualquier miembro del equipo X<sup>4</sup> (human in the loop) utilizando el sistema de autorización X<sup>5</sup>, todo mediante un agente implementado en el software X<sup>6</sup> con el lenguaje de programación X<sup>7</sup>,orquestado por la plataforma de IA agéntica X<sup>8</sup>.</span> |
| **Superficial** | <span style="color:red">Usaremos IA generativa para mejorar la eficiencia operativa.</span> | <span style="color:grey">Usaremos IA generativa para mejorar la eficiencia operativa en el soporte técnico del producto X.</span> |



<br>

___
<span style="color:grey">8 feb 2026</span>
