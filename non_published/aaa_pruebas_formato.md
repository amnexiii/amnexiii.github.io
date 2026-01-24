# PRUEBAS DE FORMATO

https://amnexiii.github.io/non_published/aaa_pruebas_formato.html

https://amnexiii.github.io/bandeja_vacía.html

## Vídeo

<iframe width="560" height="315" src="https://www.youtube.com/watch?v=mTOUy_KG0Pk" frameborder="0" allowfullscreen></iframe>


## Texto

—

~~texto tachado~~

`código` o uso como `tag1` `tag2`

<mark>resaltado</mark>


## Imágenes

✔ Ancho: 1000 px → ideal para la mayoría de artículos

✔ Peso: < 300 KB

✔ Responsive: max-width:100%

Imagen sólo con ![]
![](bandeja_vacía.png)

Imagen con HTML max-width:100%
<img src="bandeja_vacía.png" style="max-width:100%; height:auto;">




## Tabla

Mes | Actividad | Productividad real (entrega de resultados)
-|-|-
Enero | Superar la gripe navideña. <br> Contar qué tal en las vacas. <br> Pensar qué hacer este año. | 0%
Febrero | x | x
Marzo | |
Abril| |
Mayo | |

## Mermaid

Según https://akuszyk.com/2023-05-03-yet-another-mermaid-in-github-pages-guide.html?utm_source=chatgpt.com

[Importar java]
<script type="module">
	import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
	mermaid.initialize({
		startOnLoad: true,
		theme: 'dark'
	});
</script>

Pintar gráfico 1:
<pre class="mermaid">
flowchart LR
     A-->B
</pre>

Pintar gráfico 2:
<pre class="mermaid">
graph LR
    %% Evento de Inicio
    Start(( )) --- OpenGate{ }

    subgraph Pool_Desayuno [Proceso de Desayuno Imperativo]
        direction LR
        
        %% Compuerta paralela (AND)
        OpenGate{ } --> Lane_A[<b>Persona A:</b> Preparar Bebida]
        OpenGate{ } --> Lane_B[<b>Persona B:</b> Preparar Comida]

        %% Carril Persona A
        subgraph Lane_A
            direction LR
            A1[Poner cafetera] --> A2[Calentar leche]
            A2 --> A3[Mezclar café y leche]
        end

        %% Carril Persona B
        subgraph Lane_B
            direction LR
            B1[Tostar pan] --> B2[Sacar ingredientes]
            B2 --> B3[Untar mantequilla y mermelada]
        end

        %% Sincronización (AND Join)
        A3 --> CloseGate{ }
        B3 --> CloseGate{ }

        %% Tarea final y fin
        CloseGate{ } --> FinalTask[Colocar en mesa]
        FinalTask --> End(( ))
    end

    %% Estilos BPMN
    style Start fill:#dfd,stroke:#3c3,stroke-width:2px
    style End fill:#fdd,stroke:#c33,stroke-width:4px
    style OpenGate fill:#ff9,stroke:#990,stroke-width:2px
    style CloseGate fill:#ff9,stroke:#990,stroke-width:2px
</pre>

<br>

