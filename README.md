# Venus Landing (Astro)

Landing y documentacion oficial de Venus, una libreria moderna y ligera para networking en JavaScript/TypeScript.

## Venus v2.0.0

Novedades principales:

- Smart Parsing: deteccion automatica de JSON o texto (ideal para RSS/XML).
- Multi-Format Support: soporte para blob, formData y arrayBuffer.
- Query Params: opcion params para construir query strings de forma segura.
- Enhanced DX: JSDoc completo para mejor IntelliSense en VS Code.
- API unificada: options consistentes en get/send/update/updateOnly/remove.
- Retry configurable con backoff para errores transitorios.
- Hooks ligeros: beforeRequest y afterResponse.
- getRss con normalizacion RSS/Atom y modos strict/lenient.

## Scripts

- npm run dev: inicia entorno local.
- npm run build: genera build de produccion.
- npm run preview: previsualiza la build.

## Estructura principal

- src/pages/index.astro: landing principal.
- src/pages/doc.astro: pagina de documentacion.
- src/components: secciones reutilizables de landing/docs.
- src/styles/global.css: estilos globales.

## Desarrollo

1. Instalar dependencias:

```bash
npm install
```

2. Levantar entorno local:

```bash
npm run dev
```

3. Abrir en navegador:

`http://localhost:4321`

## Referencias

- GitHub: https://github.com/code-braydev/venus
- NPM: https://www.npmjs.com/package/@braydev/venus
