# attackpath.sh

Sitio construido con [Hugo](https://gohugo.io) + tema PaperMod.

## Uso local

```bash
hugo server -D          # servidor de desarrollo en http://localhost:1313 (incluye borradores)
hugo new writeups/htb-nombre.md   # crea un writeup nuevo desde el archetype
hugo                    # genera el sitio en public/
```

## Publicar

1. Sube este repo a GitHub.
2. Cloudflare Pages → Create project → conecta el repo.
3. Build command: `hugo --gc --minify`
4. Build output directory: `public`
5. Variable de entorno: `HUGO_VERSION` = `0.148.2`
6. Custom domain → `attackpath.sh`

## Pendientes antes de publicar

- [ ] Reemplazar `TU NOMBRE` / `TU_USUARIO` en `hugo.yaml` y `content/about.md`
- [ ] Añadir `static/favicon.ico`
- [ ] Quitar `draft: true` del primer post real
- [ ] Borrar `content/writeups/_PLANTILLA.md` o dejarlo como draft
