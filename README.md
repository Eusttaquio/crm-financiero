# CRM Comercial & Financiero (GitHub Pages + Google Sheets)

Paquete listo para publicar como aplicación web gratuita con enlace fijo y acceso directo desde el celular.

## Archivos incluidos
- `index.html`: Aplicación web responsive en modo oscuro con Bandeja Operativa Diaria (`📅 TERMINADAS HOY`, `🚨 COBROS ATRASADOS`, `📅 SERVICIOS`, `💰 INGRESOS PRÓXIMOS`, `💸 EGRESOS PRÓXIMOS`), matriz Categoría × Ingreso/Egreso, registro de cobros parciales y DSO.
- `manifest.json`: Configuración PWA para instalar el acceso directo en la pantalla de inicio del teléfono como si fuera una app nativa.
- `apps_script_backend.gs`: Código para pegar en **Extensiones → Apps Script** de tu planilla de Google Sheets.

## Cómo subirlo a GitHub Pages en 3 pasos
1. Creá un repositorio nuevo en GitHub (ej. `crm-financiero`, público o privado según tu plan).
2. Subí `index.html`, `manifest.json` y `README.md` a la rama `main`.
3. Entrá en **Settings → Pages**, elegí **Deploy from a branch** → `main` / `(root)` y guardá. En 1 minuto tendrás tu enlace fijo `https://<tu-usuario>.github.io/crm-financiero/`.
