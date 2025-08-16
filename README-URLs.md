
# URLs para GitHub Pages (David Ricardo Colonia)

Incluye variantes listas para dos escenarios. Reemplaza `<USUARIO>` y `<REPO>` por los tuyos.

## Opción A — Sitio principal de usuario
URL final: https://<USUARIO>.github.io/

Archivos:
- robots-user.txt → renómbralo a **robots.txt**
- sitemap-user.xml → renómbralo a **sitemap.xml**

Cambia `<USUARIO>` y súbelos a la raíz del repo.

## Opción B — Sitio de proyecto
URL final: https://<USUARIO>.github.io/<REPO>/

Archivos:
- robots-project.txt → renómbralo a **robots.txt**
- sitemap-project.xml → renómbralo a **sitemap.xml**

Cambia `<USUARIO>` y `<REPO>` y súbelos a la raíz del repo.

---

## Edición rápida (ejemplos)

### Reemplazo directo en GitHub Web
1. Abre el archivo y pulsa **Edit**.
2. Cambia `<USUARIO>` y `<REPO>`.
3. **Commit changes**.

### Línea de comandos (macOS/Linux/Git Bash)
Sitio de usuario:
```bash
sed -i 's/<USUARIO>/miusuario/g' robots-user.txt sitemap-user.xml
mv robots-user.txt robots.txt
mv sitemap-user.xml sitemap.xml
```

Sitio de proyecto:
```bash
sed -i 's/<USUARIO>/miusuario/g;s/<REPO>/mi-repo/g' robots-project.txt sitemap-project.xml
mv robots-project.txt robots.txt
mv sitemap-project.xml sitemap.xml
```

---

## Nota
- `lastmod` se estableció en 2025-08-16. Puedes actualizarlo cuando quieras.
- Sube **solo** la pareja final `robots.txt` y `sitemap.xml` (no subas todas las variantes).
