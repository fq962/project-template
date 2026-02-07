# Project Template

Template base para inicializar nuevos proyectos rápidamente con una estructura organizada y las dependencias esenciales ya configuradas.

## Tech Stack

- **Next.js** 16 (App Router)
- **React** 19
- **TypeScript** 5
- **Tailwind CSS** 4
- **ESLint** 9

## Estructura del Proyecto

```
app/
├── assets/          # Archivos estáticos (imágenes, fuentes, etc.)
├── components/      # Componentes reutilizables de React
├── context/         # Providers de React Context
├── hooks/           # Custom hooks
├── pages/           # Páginas y rutas de la aplicación
├── services/        # Lógica de servicios y llamadas a APIs
├── styles/          # Estilos globales y módulos CSS
├── utils/           # Funciones utilitarias y helpers
├── layout.tsx       # Layout raíz de la aplicación
├── page.tsx         # Página principal
└── globals.css      # Estilos globales de Tailwind
```

> Los archivos `delete-me.txt` dentro de cada carpeta son placeholders para que Git mantenga las carpetas vacías. Elimínalos cuando agregues archivos reales.

## Inicio Rápido

1. **Clona el template**

   ```bash
   git clone <url-del-repositorio> nombre-del-proyecto
   cd nombre-del-proyecto
   ```

2. **Instala las dependencias**

   ```bash
   npm install
   ```

3. **Inicia el servidor de desarrollo**

   ```bash
   npm run dev
   ```

4. **Abre** [http://localhost:3000](http://localhost:3000) en tu navegador.

## Scripts Disponibles

| Comando         | Descripción                          |
| --------------- | ------------------------------------ |
| `npm run dev`   | Inicia el servidor de desarrollo     |
| `npm run build` | Genera el build de producción        |
| `npm run start` | Inicia el servidor en producción     |
| `npm run lint`  | Ejecuta ESLint para análisis de código |

## Configuración Incluida

- **Path aliases**: Usa `@/` para importaciones absolutas desde la raíz (ej. `import { cn } from "@/app/utils/cn"`)
- **Tipografía**: Fuentes Geist Sans y Geist Mono pre-configuradas
- **PostCSS + Tailwind**: Listo para estilos utilitarios
- **TypeScript strict mode**: Habilitado por defecto

## Personalización Inicial

Al crear un nuevo proyecto con este template:

1. Actualiza el `name` en `package.json`
2. Configura `title` y `description` en `app/layout.tsx`
3. Reemplaza `public/vercel.svg` con los assets de tu proyecto
4. Elimina los archivos `delete-me.txt` conforme agregues contenido a cada carpeta
