# Árbol de Problemas: Falta de Verdadera Agilidad en el Desarrollo de Software

A continuación se presenta el árbol de problemas que identifica las causas principales y los efectos de la falta de verdadera agilidad en el desarrollo de software con metodologías ágiles.

```mermaid
graph TD
    A[Falta de verdadera agilidad en el desarrollo de software con metodologías ágiles]
    
    subgraph Cultura Organizacional
        A --> E1[Resistencia al cambio]
        A --> E2[Falta de apoyo de la alta dirección]
    end
    
    subgraph Gestión y Liderazgo
        A --> F1[Falta de comunicación]
        A --> F2[Falta de liderazgo]
    end
    
    subgraph Alineación con el Manifiesto Ágil
        A --> G1[Desconocimiento de principios]
        A --> G2[Falta de aplicación]
    end
    
    subgraph Equipos y Personas
        A --> C1[Falta de formación]
        A --> C2[Conflictos internos]
    end
    
    subgraph Procesos y Prácticas Ágiles
        A --> B1[Inconsistencia en métodos]
        A --> B2[Falta de adaptación]
    end
    
    subgraph Herramientas y Tecnología
        A --> D1[Herramientas inadecuadas]
        A --> D2[Falta de automatización]
    end

    %% Efectos
    E1 & E2 & F1 & F2 & G1 & G2 & C1 & C2 & B1 & B2 & D1 & D2 --> H[Baja Productividad]
    E1 & E2 & F1 & F2 & G1 & G2 & C1 & C2 & B1 & B2 & D1 & D2 --> I[Baja Calidad del Software]
    E1 & E2 & F1 & F2 & G1 & G2 & C1 & C2 & B1 & B2 & D1 & D2 --> J[Insatisfacción del Cliente]
    E1 & E2 & F1 & F2 & G1 & G2 & C1 & C2 & B1 & B2 & D1 & D2 --> K[Alta Rotación de Personal]
    E1 & E2 & F1 & F2 & G1 & G2 & C1 & C2 & B1 & B2 & D1 & D2 --> L[Pérdida de Competitividad]
    E1 & E2 & F1 & F2 & G1 & G2 & C1 & C2 & B1 & B2 & D1 & D2 --> M[Incremento de Costos]
atisfacción del Cliente]
    E1 & E2 & F1 & F2 & G1 & G2 & C1 & C2 & B1 & B2 & D1 & D2 --> K[Alta Rotación de Personal]
    E1 & E2 & F1 & F2 & G1 & G2 & C1 & C2 & B1 & B2 & D1 & D2 --> L[Pérdida de Competitividad]
    E1 & E2 & F1 & F2 & G1 & G2 & C1 & C2 & B1 & B2 & D1 & D2 --> M[Incremento de Costos]
