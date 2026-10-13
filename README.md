# CargoBox — Diseño arquitectural del sistema

## Datos de identificación

- **Actividad:** Diseño arquitectural del sistema con IA
- **Materia:** Componentes de Lógica de Negocios
- **Unidad:** 3
- **Equipo:** 14
- **Integrantes:**
  - Pedro Omar Cardona Alvarez — Matrícula 2226579
  - Kloudenn Jafed Jiménez Valdivieso — Matrícula 2226639
  - Leonardo Acosta Morales — Matrícula 2226717

## Empresa

**CargoBox** es el caso de negocio para el que se propone un sistema de gestión de paquetería y envíos nacionales, abarcando la recepción de paquetes, generación de guías, rastreo, control de intentos de entrega, gestión de incidencias (destinatario ausente, dirección incorrecta, daños y seguros) y reportes automatizados.

## objetivo

El proyecto contiene una propuesta arquitectural organizada en las capas de dominio, aplicación e infraestructura, junto con diagramas UML, decisiones arquitecturales (ADR), matriz de trazabilidad y documentación de requisitos derivada del análisis de la Unidad 2.

## Estructura del proyecto

```text
CARGOBOX_ARQUITECTURA/
├── diagramas/
│   ├── clases/
│       ├── Diagrama capa de Dominio /.pdf/.drawio 
│       ├── Diagrama de Infraestructura /.pdf/.drawio 
│       └── Diagrama de Servicio /.pdf/.drawio 
│   ├── dominio/
│   │   └── mapa de dominio /.pdf 
│   └── secuencia/
│       ├── Diagrama de secuencia (incidencia) /.pdf/.drawio 
│       └── Diagrama de secuencia (principal) /.pdf/.drawio 
├── docs/
│   ├── ADRS/
│   │   └── ADRS /.pdf
│   ├── bitacora ia/
│   │   └── Bitacora obligatoria de IA /.pdf
│   ├── informe/
│   │   └── Actividad_Unidad_3_CLN_Arquitectura /.pdf
│   ├── trazabilidad/
│   │   └── Matriz de trazabilidad /.pdf
│   └── unidad 2/
│       ├── BRD /.pdf
│       ├── BPMN /.pdf
│       ├── USER STORIES /.pdf
│       └── GLOSARIO /.pdf
└── README.md
