<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

# Diagrame de tip _Flowchart_

```mermaid
flowchat LR
A[/Anul I/] -->|Tranzitie usoara| B[Anul II]
A -.->|Tranzitie grea| C[\Anul IV/]
C -->|Tranzitie medie| D[Master]
```
**De retinut**
-diagramele _Flowchrat_ au noduri si conectori
-nodurile au:
  -forma (data de parantezele folosite la descrierea _nodului_)
  -ID (sirul folosit in afara descriereii nodului)
  -Descriere (textul ce apare in caseta nodului si care este implementat in interiorul diferitelor tipul de paranteze - ce decid forma )
  -Conectorii au:
    -Diferite tipuri de sageti sau chiar pot  activa fara sageti
    -Diferite tipuri de linii 

  ## Diagrame _Flowchrat_ avansate

```mermaid
A -->B &
A & B -->C & D & E --> F & G 
```

  # Diagrame de tip _Timeline_

```mermaid
title "Timeline"
sanction "Sectiunea I"
2023-2024
        : am luat la facultate
        : am luat contact cu mediul academic
2024-2025
        : am terminat anul I
        :am facut practica
2025-2026
        :
        : am facut practica la fotogrametrie
2026-2027
        : am terminat facultatea

        
```
  


  
