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
flowchart TB

%% =========================
%% CUADRÍCULA 2x2
%% =========================

subgraph ROW1[" "]
direction LR
Q2["General<br/>Concreto"]
Q1["Específico<br/>Concreto"]
end

subgraph ROW2[" "]
direction LR
Q3["General<br/>Abstracto"]
Q4["Específico<br/>Abstracto"]
end

ROW1 --- ROW2

%% =========================
%% EJES
%% =========================

Y1["Definición ↑<br/>Concreto"]
Y2["Abstracto"]

X1["General"]
X2["Amplitud → Específico"]

Y2 --> Y1
X1 --> X2

Y1 --- Q2
X2 --- Q4

%% =========================
%% ESTILOS
%% =========================

classDef quad fill:#f7f7f7,stroke:#333,stroke-width:1px;
class Q1,Q2,Q3,Q4 quad;

style ROW1 fill:transparent,stroke-width:0;
style ROW2 fill:transparent,stroke-width:0;
</pre>


<br>

___
3 feb 2026+
