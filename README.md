# Mi tablero de notas

App de notas adhesivas con colores, prioridades, búsqueda y guardado automático.

## Cómo publicarla en internet (GitHub + Vercel)

### Parte 1: Subir el código a GitHub

1. Creá una cuenta en https://github.com (si no tenés).
2. Clic en el botón verde **"New"** (o el "+" arriba a la derecha → "New repository").
3. Ponele un nombre, por ejemplo `notas-adhesivas`. Dejalo **Public**. No marques nada más.
4. Clic en **"Create repository"**.
5. En la página que aparece, buscá la opción **"uploading an existing file"** (es un link en el texto).
6. Arrastrá TODOS los archivos de esta carpeta a esa ventana (menos la carpeta `node_modules` si aparece — no la subas).
7. Abajo, clic en **"Commit changes"**.

### Parte 2: Publicar con Vercel

1. Andá a https://vercel.com y registrate **con tu cuenta de GitHub** (botón "Continue with GitHub").
2. En el panel, clic en **"Add New..."** → **"Project"**.
3. Vercel te muestra tus repositorios de GitHub. Buscá `notas-adhesivas` y clic en **"Import"**.
4. No cambies nada de la configuración (Vercel detecta Vite solo).
5. Clic en **"Deploy"**.
6. Esperá ~1 minuto. ¡Listo! Vercel te da tu link público (algo como `notas-adhesivas.vercel.app`).

### De ahí en adelante

Cada vez que cambies el código en GitHub, Vercel republica solo. No tenés que volver a hacer nada.

---

## Para correrla en tu computadora (opcional)

Si tenés Node.js instalado:

```
npm install
npm run dev
```

Y abrí la dirección que aparece (normalmente http://localhost:5173).
