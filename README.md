# Manu Hybrid OS — PWA

App web progresiva personal para el plan híbrido de Manu: fuerza, running, bitácora, semáforo tibial y versiones ideal/mínima/noche.

## Archivos

- `index.html`: app principal.
- `manifest.webmanifest`: configuración para instalar como app.
- `service-worker.js`: soporte offline básico.
- `icons/`: íconos para Android/iOS/PWA.
- `.nojekyll`: evita procesamiento de Jekyll en GitHub Pages.
- `robots.txt`: intenta evitar indexación en buscadores. No lo convierte en privado.

## Publicar gratis en GitHub Pages

1. Crear un repositorio público, por ejemplo `manu-hybrid-os`.
2. Subir estos archivos a la raíz del repo.
3. Ir a Settings → Pages.
4. En Build and deployment, elegir Source: Deploy from a branch.
5. Seleccionar branch `main` y folder `/root`.
6. Guardar. GitHub suele tardar unos minutos en publicar.

La URL debería quedar así:

`https://TU-USUARIO.github.io/manu-hybrid-os/`

## Instalar en teléfono

### iPhone
Abrir la URL en Safari → Compartir → Agregar a pantalla de inicio.

### Android
Abrir la URL en Chrome → menú ⋮ → Instalar app o Agregar a pantalla principal.

## Nota

Esta primera versión no tiene backend ni login. Es intencional: rápida, gratis, instalable y fácil de modificar.
