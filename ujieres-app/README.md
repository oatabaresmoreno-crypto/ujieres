# Ujieres · Iglesia Cristiana de Villa Hermosa

Sistema de programación de ujieres para El Pacto.

## Estructura del proyecto

```
ujieres-app/
├── index.html       # Estructura HTML y estilos
├── app.js           # Toda la lógica de la aplicación
├── vercel.json      # Configuración de despliegue en Vercel
└── README.md        # Este archivo
```

## Cómo desplegar en Vercel

### Opción 1 – Desde GitHub (recomendada)
1. Sube esta carpeta a un repositorio de GitHub
2. Ve a [vercel.com](https://vercel.com) e inicia sesión
3. Haz clic en **"Add New Project"**
4. Importa tu repositorio de GitHub
5. Vercel detectará automáticamente que es un sitio estático
6. Haz clic en **"Deploy"**
7. En ~30 segundos tendrás tu URL pública

### Opción 2 – Vercel CLI
```bash
npm install -g vercel
cd ujieres-app
vercel
```
Sigue las instrucciones en pantalla. Al terminar te dará una URL pública.

## Funcionalidades
- Programación mensual con calendario interactivo
- Búsqueda por persona, servicio y día
- Reglas automáticas: Bienvenida 1 = hombre, ALEIDA MORENO prioridad, servicios vinculados
- Carga de disponibilidad mensual vía Excel (.xlsx)
- Exportar programación a CSV
- Edición manual de asignaciones
