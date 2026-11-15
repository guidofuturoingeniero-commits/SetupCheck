# SetupCheck

Landing page de **SetupCheck**, una plataforma web para validar configuraciones de PC antes de comprar: estima temperatura, detecta cuellos de botella y ofrece reportes reales de la comunidad.

> Proyecto del curso — avance de implementación de la Landing Page (solo HTML, CSS y JavaScript, sin frameworks CSS).

## Autores

| Nombre | Rol |
|--------|-----|
| _Nombre Apellido_ | _Rol_ |
| _Nombre Apellido_ | _Rol_ |
| _Nombre Apellido_ | _Rol_ |

> Completar con los integrantes del equipo.

## Segmentos objetivo

- **Entusiastas / gamers** que arman o actualizan su PC y quieren validar el combo antes de comprar.
- **Técnicos y ensambladores** que necesitan referencias reales de temperatura y rendimiento.
- **Creadores de contenido** que requieren estabilidad térmica en cargas largas.

## Principales características

- **Simulador de configuraciones:** elige componentes (ej. Ryzen 5 5600 + RTX 4060) y obtén un análisis.
- **Riesgo térmico:** estimación de temperatura en carga (riesgo bajo, medio o alto).
- **Cuellos de botella:** detección de desbalance entre componentes.
- **Benchmarks y reportes de la comunidad:** búsqueda, filtros, detalle y comparación de configuraciones.
- **Aportar reportes:** flujo para subir una captura y publicar datos detectados.
- **Ranking y reputación** de aportantes.
- **Tutorial "¿Cómo funciona?"** en versión web y mobile.
- **Login y registro** de usuarios.

## Estructura del proyecto

```
.
├── README.md
└── public/
    ├── index.html
    ├── favicon.ico
    ├── *.html                 # resto de pantallas (benchmarks, simulador, comunidad, ...)
    └── assets/
        ├── styles/styles.css
        ├── scripts/main.js
        └── images/
```

## Cómo ejecutarlo

1. Clonar el repositorio.
2. Abrir `public/index.html` en el navegador (o usar *Open in Browser* de WebStorm / la extensión Live Server).

## Flujo de trabajo (GitFlow)

- `main`: versión estable.
- `develop`: integración; de aquí salen las ramas `feature/*`.
- `feature/<nombre-corto>`: nuevas funcionalidades, se fusionan a `develop`.
- `release/*` y `hotfix/*`: según GitFlow.

## Tecnologías

HTML5, CSS3, JavaScript. Fuente: Google Fonts (Inter).
