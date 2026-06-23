# softguard-assets

Repositorio público para alojar imágenes y PDFs usados en campañas de email
(Listmonk). Los archivos quedan disponibles vía GitHub Pages en URLs estables.

## Subir un archivo nuevo

```bash
cd ~/softguard-assets
cp /ruta/al/archivo.jpg assets/
git add assets/archivo.jpg
git commit -m "Agregar archivo.jpg"
git push
```

La URL pública queda en:

```
https://moshesinger31-star.github.io/softguard-assets/assets/<nombre-del-archivo>
```

Puede tardar 1-2 minutos en publicarse después del push. Para verificar:

```bash
curl -I https://moshesinger31-star.github.io/softguard-assets/assets/<nombre-del-archivo>
```

Debe responder `200 OK` (no `404`).
