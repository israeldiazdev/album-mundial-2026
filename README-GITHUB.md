# 🌟 Album Mundial 2026 - Gestor de Estampas

> Una aplicación web interactiva profesional para gestionar y controlar tu colección de estampas del Mundial 2026 de Panini.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Version](https://img.shields.io/badge/version-1.0-blue)
![Status](https://img.shields.io/badge/status-production%20ready-brightgreen)

## 📸 Vista Previa

Accede directamente a la aplicación:

- **[🎯 Aplicación Principal](https://israeldiazdev.github.io/album-mundial-2026/album-mundial-2026.html)** - Versión completa con todas las características
- **[⭐ Versión Premium](https://israeldiazdev.github.io/album-mundial-2026/album-mundial-2026-premium.html)** - Con estadísticas avanzadas

## 🎯 Características Principales

### 📊 Panel de Control
- Visualización en tiempo real de tu progreso
- Gráficos interactivos con Chart.js
- 4 métricas principales: total obtenidas, faltantes, porcentaje, repetidas

### 👥 Grupos Mundialistas
- **12 Grupos** (A-L) con todos los equipos del Mundial 2026
- **48 Equipos** organizados por grupo
- **624 Estampas** base (13 por equipo)
- Colores diferenciados por grupo

### 🌍 Sección de Equipos
- Vista completa de todos los equipos
- Progreso individual por equipo
- Sincronización automática con grupos

### ⚽ Elementos Especiales
- **109 Estampas** adicionales distribuidas en 6 categorías:
  - Balón Oficial Trionda
  - Copa del Mundo
  - Mascotas
  - Estadios
  - Insignias de Naciones
  - Otros Elementos

### 🥤 Colección Coca-Cola
- **12 Estampas** exclusivas de Coca-Cola
- Control independiente

### 📋 Gestión de Repetidas
- Selector dinámico de estampas
- Ingreso de cantidades
- Tabla interactiva
- Cálculo automático

## 💾 Almacenamiento y Datos

- **LocalStorage**: Almacenamiento en el navegador (5-10 MB)
- **Automático**: Todos los cambios se guardan instantáneamente
- **Persistente**: Los datos se mantienen entre sesiones
- **Exportar/Importar**: Realiza copias de seguridad en JSON

### Total de Estampas
```
Grupos: 624 estampas
Elementos: 109 estampas
Coca-Cola: 12 estampas
─────────────────────
TOTAL: 745 estampas
```

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Diseño responsivo con Grid y Flexbox
- **JavaScript ES6+**: Lógica e interactividad
- **Chart.js v4.4.0**: Gráficos interactivos
- **LocalStorage API**: Persistencia de datos

## 📱 Compatibilidad

| Navegador | Versión | Estado |
|-----------|---------|--------|
| Chrome | 90+ | ✅ Completo |
| Firefox | 88+ | ✅ Completo |
| Safari | 14+ | ✅ Completo |
| Edge | 90+ | ✅ Completo |
| Opera | 76+ | ✅ Completo |

## 📱 Responsividad

- ✅ Desktop (1920px+)
- ✅ Tablet (768-1024px)
- ✅ Mobile (<768px)

## 🚀 Inicio Rápido

### Opción 1: Usar desde GitHub Pages
Simplemente abre en tu navegador:
```
https://israeldiazdev.github.io/album-mundial-2026/
```

### Opción 2: Usar localmente
1. Clona el repositorio
```bash
git clone https://github.com/israeldiazdev/album-mundial-2026.git
cd album-mundial-2026
```

2. Abre `album-mundial-2026.html` en tu navegador

### Opción 3: Usar desde servidor local
```bash
# Con Python 3
python3 -m http.server 8000

# Con Node.js
npx http-server

# Con Ruby
ruby -run -ehttpd . -p8000
```

Luego abre: `http://localhost:8000`

## 📖 Documentación

El proyecto incluye documentación completa:

- **[README.md](README.md)** - Documentación general
- **[GUIA_RAPIDA.md](GUIA_RAPIDA.md)** - Manual rápido de usuario
- **[ESPECIFICACIONES_TECNICAS.md](ESPECIFICACIONES_TECNICAS.md)** - Detalles técnicos
- **[RESUMEN_EJECUTIVO.md](RESUMEN_EJECUTIVO.md)** - Resumen del proyecto
- **[EJEMPLOS_PRACTICOS.md](EJEMPLOS_PRACTICOS.md)** - 12+ casos de uso reales
- **[INDICE_COMPLETO.md](INDICE_COMPLETO.md)** - Índice completo del paquete

## 💡 Casos de Uso

### 👤 Coleccionista Casual
```
Compra ocasionalmente → Registra en la app → Disfruta del progreso
```

### 🏆 Coleccionista Competitivo
```
Compra regularmente → Analiza gráficos → Optimiza estrategia
```

### 👨‍👩‍👧‍👦 Coleccionista Familiar
```
Recolecta con familia → Comparte datos → Compite amistosamente
```

## 🎓 Ejemplos Prácticos

### Registrar una estampa
1. Abre "Grupos Mundialistas"
2. Busca tu equipo
3. Marca la estampa con ✓
4. ¡Automáticamente se actualiza el progreso!

### Ver tu progreso
1. Abre "Panel de Control"
2. Observa los gráficos en tiempo real
3. Ajusta tu estrategia según necesites

### Hacer backup
1. Ve a "Repetidas"
2. Click en "Descargar Progreso"
3. Se descarga un archivo JSON con todos tus datos

### Restaurar datos
1. Click en "Cargar Progreso"
2. Selecciona tu archivo JSON guardado
3. ¡Listo, tus datos se restauran!

## 🔧 Configuración Personalizada

El código está completamente comentado y es fácil de personalizar:

- Cambiar colores de grupos
- Modificar datos de equipos
- Agregar nuevas secciones
- Personalizar gráficos

Consulta [ESPECIFICACIONES_TECNICAS.md](ESPECIFICACIONES_TECNICAS.md) para más detalles.

## 📊 Estadísticas del Proyecto

```
Archivos:           15
Líneas de código:   4,500+
Tamaño:            ~150 KB
Lenguajes:         HTML5, CSS3, JavaScript
Licencia:          MIT
Estado:            Producción
Versión:           1.0
Fecha:             Mayo 2026
```

## 🔐 Seguridad

- ✅ Datos completamente privados
- ✅ Sin conexión a servidores
- ✅ Sin cuenta requerida
- ✅ Sin publicidades
- ✅ Sin seguimiento

## 🆓 Licencia

Este proyecto está bajo licencia **MIT**. Puedes:
- ✅ Usar comercialmente
- ✅ Modificar
- ✅ Distribuir
- ✅ Usar privadamente

Con la única condición de incluir la licencia original.

Ver [LICENSE](LICENSE) para más detalles.

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! 

Si encontraste un bug o tienes una sugerencia:
1. Abre un issue
2. Describe el problema/sugerencia
3. ¡Ayuda a mejorar el proyecto!

## 📞 Soporte

Para preguntas o problemas:
1. Consulta la documentación incluida
2. Revisa [GUIA_RAPIDA.md](GUIA_RAPIDA.md)
3. Busca en los [EJEMPLOS_PRACTICOS.md](EJEMPLOS_PRACTICOS.md)
4. Abre un issue en GitHub

## 🌟 Características Futuras

Posibles mejoras para versiones futuras:
- [ ] Versión móvil (PWA)
- [ ] Sincronización en la nube
- [ ] Comunidad de usuarios
- [ ] Sistema de intercambios
- [ ] Análisis predictivos
- [ ] Gamificación avanzada

## 🙏 Agradecimientos

Gracias por usar **Album Mundial 2026**. 

Este proyecto fue creado con ❤️ para todos los coleccionistas de estampas.

---

## 📈 Estadísticas del Repositorio

![GitHub stars](https://img.shields.io/github/stars/israeldiazdev/album-mundial-2026)
![GitHub forks](https://img.shields.io/github/forks/israeldiazdev/album-mundial-2026)
![GitHub watchers](https://img.shields.io/github/watchers/israeldiazdev/album-mundial-2026)

---

<div align="center">

### ⚽ ¡Que comience el Mundial 2026! 🏆

**[Abre la aplicación](https://israeldiazdev.github.io/album-mundial-2026/)**

Hecho con ❤️ por [israeldiazdev](https://github.com/israeldiazdev)

</div>
