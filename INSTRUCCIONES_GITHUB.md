# 🚀 INSTRUCCIONES PARA SUBIR A GITHUB

## PASO 1: Crear el repositorio en GitHub

1. Ve a https://github.com/new
2. Nombre del repositorio: `album-mundial-2026`
3. Descripción: "Gestor interactivo de estampas para el Mundial 2026 - Aplicación web con almacenamiento local"
4. Selecciona: **Public** (para que sea accesible)
5. Click en "Create repository"

## PASO 2: Conectar tu repositorio local

Ejecuta estos comandos en tu terminal:

```bash
cd ~/Proyectos/album-mundial-2026

# Agregar el repositorio remoto
git remote add origin https://github.com/israeldiazdev/album-mundial-2026.git

# Cambiar rama a main (si es necesario)
git branch -M main

# Subir todos los archivos
git push -u origin main
```

## PASO 3: Habilitar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Abre Settings → Pages
3. Source: **Deploy from a branch**
4. Branch: **main**
5. Folder: **/ (root)**
6. Click Save
7. Tu sitio estará disponible en: `https://israeldiazdev.github.io/album-mundial-2026/`

## PASO 4: Verificar la publicación

- Índice: https://israeldiazdev.github.io/album-mundial-2026/
- App Principal: https://israeldiazdev.github.io/album-mundial-2026/album-mundial-2026.html
- App Premium: https://israeldiazdev.github.io/album-mundial-2026/album-mundial-2026-premium.html

## 📋 Lo que se ha preparado

✅ Repositorio local inicializado
✅ 12 archivos listos para subir
✅ Commit inicial hecho
✅ Licencia MIT incluida
✅ .gitignore configurado
✅ index.html como página de inicio
✅ Workflow GitHub Actions configurado

## 🔑 Variables de entorno

Si necesitas agregar variables sensibles (nunca subas credenciales):
1. Settings → Secrets and variables → Actions
2. Click "New repository secret"
3. Agrega lo que necesites

## 💡 Comandos útiles después

```bash
# Ver estado
git status

# Ver historial
git log --oneline

# Hacer cambios futuros
git add .
git commit -m "Descripción del cambio"
git push
```

---

**Listo para ejecutar los comandos del PASO 2 cuando quieras** 🚀
