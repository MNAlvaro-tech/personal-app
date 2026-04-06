# MiVida — App Personal PWA

## Archivos del proyecto
```
miapp/
├── index.html     ← App completa (toda la lógica aquí)
├── manifest.json  ← Configuración PWA
├── sw.js          ← Service Worker (modo offline)
└── README.md      ← Este archivo
```

## Cómo publicarla (para instalar en iPhone)

### Opción A — Netlify Drop (más fácil, 0 cuenta requerida)
1. Ve a **netlify.com/drop**
2. Arrastra la carpeta `miapp/` entera al navegador
3. Obtén un enlace tipo `https://algo-aleatorio.netlify.app`
4. En tu iPhone, abre ese enlace en **Safari**
5. Toca **Compartir** (cuadrado con flecha) → **Añadir a pantalla de inicio**
6. ¡Listo! Tienes icono en tu home como app nativa.

### Opción B — GitHub Pages (gratis, repositorio privado)
1. Crea cuenta en github.com
2. Nuevo repositorio **privado**
3. Sube los 3 archivos
4. Settings → Pages → Source: main branch
5. Accede desde Safari en iPhone e instala

## Datos
- Todo se guarda en **LocalStorage** de tu iPhone
- Los datos NO salen de tu dispositivo
- Si limpias Safari/datos del sitio, se borran → haz backup con export (próxima versión)

## Módulos incluidos
- 💸 **Gastos** — registro diario con categorías y totales por mes
- ✈️ **Viajes** — destinos, fechas, presupuesto, checklist de preparación
- 📚 **Libros** — lista con estados (pendiente/leyendo/leído)
- 💪 **Hábitos** — tracker diario con rachas
- ✅ **Tareas** — to-do con prioridades y fechas

## Próximas fases
- Exportar/importar datos (JSON backup)
- Notas libres
- Gráficas de gastos por mes
- Notificaciones de hábitos
