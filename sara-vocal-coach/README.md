# NFOKU · Clientes

Entregables de NFOKU para sus clientes, publicados con GitHub Pages en
`https://nfokumkt-gdl.github.io/clientes/`

## Estructura

```
clientes/
├── README.md                         ← este archivo
└── sara-vocal-coach/                 ← una carpeta por cliente (minúsculas, guiones)
    ├── index.html                    ← Inicio del cliente: pestañas y lista de documentos
    ├── og.png                        ← miniatura para compartir el Inicio
    ├── brief/
    │   ├── index.html
    │   └── og.png
    ├── cotizaciones/
    │   └── octubre-2026/             ← una subcarpeta por propuesta (mes-año)
    │       ├── index.html
    │       └── og.png
    ├── branding/                     ← línea gráfica: paleta, tipografías, logo
    │   ├── index.html
    │   ├── og.png
    │   └── logo-sara-*.png           ← logos en negro, marfil y vino
    └── reportes/                     ← se crea cuando exista el primero
        └── 2026-10-quincena-1/
            ├── index.html
            └── og.png
```

## Reglas

1. **Cada documento es una carpeta** con su `index.html` y su `og.png` (1200×630). Así la URL queda limpia y la miniatura siempre está junto a su página.
2. **Nombres en minúsculas, sin acentos ni espacios**, separados por guiones: `sara-vocal-coach`, `octubre-2026`.
3. **Documentos que se repiten van en plural con subcarpeta por fecha**: `cotizaciones/octubre-2026/`, `reportes/2026-10-quincena-1/`. Los que son únicos van en singular: `brief/`, `branding/`.
4. **Nunca se borra una versión enviada al cliente.** Si cambia una cotización ya aceptada, se crea otra carpeta (`noviembre-2026/`).
5. **Al agregar un documento**, se actualiza el `index.html` de Inicio del cliente y las pestañas de sus páginas.
6. **Mensajes de commit** con cliente, documento y versión: `sara vocal coach cotizacion octubre v01`.

## Links para compartir

| Documento | URL |
|---|---|
| Inicio Sara Vocal Coach | https://nfokumkt-gdl.github.io/clientes/sara-vocal-coach/ |
| Brief | https://nfokumkt-gdl.github.io/clientes/sara-vocal-coach/brief/ |
| Cotización octubre 2026 | https://nfokumkt-gdl.github.io/clientes/sara-vocal-coach/cotizaciones/octubre-2026/ |
| Línea gráfica | https://nfokumkt-gdl.github.io/clientes/sara-vocal-coach/branding/ |

> El repositorio es público: cualquiera con la ruta puede abrir los documentos. Las páginas llevan `noindex` para no aparecer en Google.
