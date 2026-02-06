# Cuadrantes

## Amplitud Vs. Definición

<script type="module">
	import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
	mermaid.initialize({
		startOnLoad: true,
		theme: 'dark'
	});
</script>

<pre class="mermaid">
flowchart TD

    %% Ejes
    Y[Definición<br/>↑<br/>Concreto]:::axis
    X[Amplitud → Específico]:::axis

    %% Cuadrantes
    Q1["Específico<br/>Concreto"]:::quad
    Q2["General<br/>Concreto"]:::quad
    Q3["General<br/>Abstracto"]:::quad
    Q4["Específico<br/>Abstracto"]:::quad

    %% Layout
    Y --> Q1
    Y --> Q2
    X --> Q1
    X --> Q4

    Q2 --- Q1
    Q2 --- Q3
    Q3 --- Q4

    %% Estilos
    classDef quad fill:#f5f5f5,stroke:#333,stroke-width:1px;
    classDef axis fill:#fff,stroke:#000,stroke-width:0px;
</pre>


<br>

___
3 feb 2026+
