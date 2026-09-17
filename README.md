# NODAL IT — Landing corporativa

Sitio web corporativo de **NODAL IT**, una red de especialistas orientada a conectar tecnología, operación y negocio mediante servicios de infraestructura, software, datos y gobierno TI.

> **Tecnología aplicada al negocio.**

## Sitio

Producción: [https://www.nodal-it.cl](https://www.nodal-it.cl)

## Stack

- [Astro](https://astro.build/)
- HTML semántico
- CSS nativo
- JavaScript mínimo
- Sitio estático (`output: static`)
- Despliegue previsto en Cloudflare Pages

## Desarrollo local

Requisitos:

- Node.js 20 LTS o superior
- npm

```bash
npm install
npm run dev
```

Astro mostrará en consola la URL local de desarrollo.

### Build de producción

```bash
npm run build
```

El resultado estático se genera en `dist/`.

### Preview del build

```bash
npm run preview
```

## Estructura

```text
.
├── public/
│   └── assets/
│       └── images/
├── src/
│   ├── pages/
│   │   └── index.astro
│   └── styles/
├── astro.config.mjs
└── package.json
```

## Identidad visual

La implementación utiliza los assets oficiales de NODAL IT y respeta su sistema de marca.

Paleta institucional principal:

- Navy: `#06182E`
- Ink: `#102A4C`
- Cyan: `#18D9E6`
- Steel: `#637895`

Los colores de especialidad se utilizan únicamente como códigos funcionales de las capacidades de servicio.

## Secciones

La landing incluye:

- Hero / propuesta de valor
- Capacidades
- Cómo trabajamos
- Por qué NODAL IT
- Diagnóstico Tecnológico NODAL IT
- IA aplicada a la ejecución
- Contacto
- Footer corporativo

## Contacto

[contacto@nodal-it.cl](mailto:contacto@nodal-it.cl)

## Flujo Git

- `main`: producción
- `development`: integración
- `feature/*`: nuevas funcionalidades
- `fix/*`: correcciones

Los cambios se integran mediante pull request hacia `development`. Las versiones listas para producción se promueven posteriormente a `main`.

## Seguridad y repositorio público

Este repositorio es público. No deben versionarse:

- credenciales, tokens ni claves API;
- archivos `.env` o `.dev.vars`;
- certificados o llaves privadas;
- configuración local de herramientas o IDEs;
- artefactos de build y dependencias instaladas.

El archivo `.gitignore` del proyecto cubre estos casos habituales. Si en el futuro se incorporan servicios externos, las credenciales deben configurarse como variables de entorno en la plataforma de despliegue y nunca almacenarse en el repositorio.

## Licencia

El código y los recursos de identidad visual de NODAL IT se mantienen bajo propiedad de NODAL IT. La publicación de este repositorio no concede permiso para reutilizar la marca, logotipos, isotipo, piezas gráficas ni otros activos visuales fuera de este proyecto.
