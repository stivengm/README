# README

```mermaid

graph LR;

D[Dominio]
A[Datos]
I[Infraestructure]
G[Gateway]
P[Presentación]
H{Hay contenido}

P --> D
D --> G
G --> I
I --> A
A --> H

H --> |SI| A
H --> |NO| I



```
