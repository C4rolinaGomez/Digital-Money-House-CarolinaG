# Digital Money House

1. [Descripción](#descripción)
2. [Tecnologías Utilizadas](#tecnologías-utilizadas)
3. [Estructura de carpetas](#estructura-de-proyecto)
4. [Funcionalidades principales](#funcionalidades-principales)
5. [Instalación y ejecucion](#instalación)

**Digital Money House** es una billetera digital que permite a los usuarios realizar transferencias, administrar tarjetas, visualizar su actividad financiera y más. El proyecto fue desarrollado como parte del desafío profesional de la certificación **Front-End Developer** en Digital House.

## 💡 Tecnologías utilizadas

- **Next.js** (Framework de React)
- **TypeScript** (Tipado estático)
- **Tailwind CSS** (Estilos Responsive)
- **React Hook Form + Yup** (Manejo de formularios y validaciones)
- **Zustand** (Manejo de estado global)
- **React Query** (Manejo de consultas asíncronas)
- **Sonner** (Notificaciones)


🛠️ 📌 Funcionalidades principales

- ✅ Registro e inicio de sesión con autenticación mediante token.
- 💳 Administración de tarjetas asociadas y datos de cuenta.
- 💸 Realización de pagos de servicios y carga de dinero..
- 📊 Visualización de actividad con paginación, busqueda y filtros.
- 📱 Diseño responsive y accesible.
- 📋 Copia rápida de alias y CVU.

🔧 📦 Instalación y ejecución

### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/tu-usuario/digital-money-house.git
cd digital-money-house
```

### 2️⃣ Instalar dependencias
```bash
npm install
```

### 3️⃣ Configurar variables de entorno
Crea un archivo `.env.local` en la raíz del proyecto y agrega las siguientes variables:
```env
NEXT_PUBLIC_API_URL= "https://digitalmoney.digitalhouse.com/api";
NEXT_PUBLIC_API_URL_SERVICE="https://digitalmoney.digitalhouse.com"
```

### 4️⃣ Ejecutar el proyecto
```bash
npm run dev





