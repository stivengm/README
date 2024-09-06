# README

```mermaid

graph LR;

D[Dominio]
A[Datos]
I[Infraestructure]
G[Gateway]
P[Presentación]
H{Hay contenido}
M[Memoria local]

P --> D
D --> G
G --> I
I --> A
A --> H

H --> |SI| A
H --> |NO| I

A --> I

I --> M
M --> P


```
