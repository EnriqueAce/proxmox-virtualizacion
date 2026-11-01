# Virtualización de servidores con Proxmox VE

Sitio educativo hecho con MkDocs Material.

## Vista previa local

```bash
pip install -r requirements.txt
mkdocs serve
```

Abrí http://127.0.0.1:8000

## Publicar gratis en GitHub Pages

1. Reemplazá `TU-USUARIO` en `mkdocs.yml` por tu usuario de GitHub.
2. Creá un repositorio público llamado `proxmox-virtualizacion` y subí estos archivos a la rama `main`.
3. Esperá a que termine la acción **Publicar sitio** (pestaña *Actions*). Crea la rama `gh-pages`.
4. En el repositorio: **Settings → Pages → Source: Deploy from a branch → `gh-pages` / `(root)`**.
5. Tu sitio queda en `https://TU-USUARIO.github.io/proxmox-virtualizacion/`.

Cada `git push` a `main` vuelve a publicar el sitio.
