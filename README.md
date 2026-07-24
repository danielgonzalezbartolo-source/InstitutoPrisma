# Instituto Prisma - GitHub Pages

Sitio web de [Instituto Prisma](https://institutoprisma.com.mx) migrado a GitHub Pages.

## Cómo publicar en GitHub Pages

### Requisitos previos
1. Instalar **Git**: https://git-scm.com/download/win
2. Tener cuenta en **GitHub**: https://github.com

### Pasos para publicar

Abre PowerShell en la carpeta `site` y ejecuta:

```powershell
# 1. Inicializar repositorio Git
git init
git add .
git commit -m "Migración de institutoprisma.com.mx a GitHub Pages"

# 2. Conectar con GitHub (reemplaza TU_USUARIO con tu usuario de GitHub)
git branch -M main
git remote add origin https://github.com/TU_USUARIO/institutoprisma.git
git push -u origin main
```

### Activar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Clic en **Settings** (configuración)
3. En el menú izquierdo: **Pages**
4. En **Source**: selecciona `main` branch y carpeta `/` (root)
5. Clic en **Save**

### URL del sitio

Tu sitio estará disponible en:
```
https://TU_USUARIO.github.io/institutoprisma/
```

### Dominio personalizado (opcional)

Si quieres usar `institutoprisma.com.mx`:
1. Crea un archivo `CNAME` con el contenido: `institutoprisma.com.mx`
2. En tu proveedor de dominio, configura un registro CNAME apuntando a `TU_USUARIO.github.io`
3. En GitHub Pages settings, ingresa el dominio personalizado

---

*Migrado el 2026-07-23*
