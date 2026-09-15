# TechnoGroup — Análisis Comercial Apprecio

Análisis comercial profundo de la cuenta **TechnoGroup** (feb 2025 – sep 2026), elaborado a partir de la base de facturación y de ~90 hilos de correo con Humantech/TechnoGroup. Incluye historial de compra, estacionalidad, riesgo de recencia, potencial de crecimiento en 3 escenarios, insights desde correo ("Voice of Customer") y un dashboard ejecutivo. Con la estética de marca de Apprecio.

## Ver el informe

El informe es un único archivo HTML (`index.html`) con gráficos interactivos (Chart.js vía CDN) — no requiere build ni dependencias.

**Opción A — Abrir localmente:** descarga o clona el repo y abre `index.html` en el navegador.

**Opción B — Publicarlo con GitHub Pages (recomendado para compartir por link):**

1. Sube este repo a GitHub (ver pasos abajo).
2. En el repo, ve a **Settings → Pages**.
3. En **Source**, selecciona la rama `main` y la carpeta `/ (root)`.
4. Guarda. GitHub publicará el sitio en `https://<tu-usuario>.github.io/<nombre-repo>/` en 1–2 minutos.

## Subir este repo a GitHub

Este directorio ya es un repositorio git local con un commit inicial. Para subirlo:

```bash
# 1. Crea un repo vacío en GitHub (sin README, sin .gitignore) desde github.com/new
# 2. Conecta el remoto y sube:
git remote add origin https://github.com/<tu-usuario>/<nombre-repo>.git
git branch -M main
git push -u origin main
```

Si prefieres SSH en vez de HTTPS:

```bash
git remote add origin git@github.com:<tu-usuario>/<nombre-repo>.git
git branch -M main
git push -u origin main
```

## Contenido

- `index.html` — el informe completo (13 secciones + Voice of Customer + dashboard ejecutivo).
- `README.md` — este archivo.

## Fuente de datos

- Base de facturación: `LETRITAS_2025_-_2026__7_.xlsx` (hoja `CUADRATURAS`), RUT 77.626.825-9.
- Correos: búsqueda en Gmail entre Apprecio y los dominios `humantech.cl` / `technogroup.cl`, feb 2025 – sep 2026.

## Nota

Los montos y fechas reflejan la base de datos entregada; cualquier actualización de la facturación requiere regenerar el informe.
