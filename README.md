# hacka_jebi

Aplicación web full-stack construida con Next.js y PostgreSQL.

## Características

- API REST
- Autenticación con JWT
- Base de datos PostgreSQL
- UI/Dashboard
- Sistema de seguridad

## Tecnologías

- **Frontend/Framework:** Next.js
- **Base de datos:** PostgreSQL
- **Autenticación:** JWT
- **Runtime:** Node.js

## Requisitos

- Node.js 18+
- PostgreSQL 14+

## Instalación

```bash
npm install
```

## Ejecutar en desarrollo

```bash
npm run dev
```

La aplicación estará disponible en `http://localhost:3000`

## Variables de entorno

Crear archivo `.env.local`:

```env
DATABASE_URL=postgresql://user:password@localhost:5432/dbname
JWT_SECRET=tu_secret_aqui
```

## Build para producción

```bash
npm run build
npm start
```

## Estructura del proyecto

```
├── src/
│   ├── app/              # Next.js App Router
│   ├── components/      # Componentes React
│   ├── lib/             # Utilidades y configuración
│   ├── pages/           # Páginas API
│   └── styles/          # Estilos globales
├── public/              # Archivos estáticos
└── ...
```

## Licencia

MIT