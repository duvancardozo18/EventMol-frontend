# EventMol 

Este repositorio contiene el frontend de EventMol, un **Sistema de Gestión de Eventos con Planificación Automática**.  
La interfaz está desarrollada con **React** y proporciona una experiencia intuitiva para administradores y participantes.

---

## 🚀 Características del Frontend

- 📅 Visualización y gestión de eventos.
- 👥 Registro y administración de participantes.
- 🛠️ Administración de recursos (espacios, comida, transporte).
- 🔔 Notificaciones en tiempo real.
- 💻 Interfaces modernas y responsivas usando React.
- 🌐 Consumo de la API RESTful del backend (Express.js).

---

## 🛠️ Tecnologías Utilizadas

- **React.js** (Frontend)
- **Axios** (Consumo de API)
- **Tailwind CSS** (Estilos)
- **Vite** 
- **Dockerfile** (Opcional, para despliegue)

---
## 📂 Estructura del Proyecto

```bash
eventmol-frontend/
├── public/               # Archivos públicos
├── src/
│   ├── components/       # Componentes reutilizables
│   ├── pages/            # Páginas principales
│   ├── services/         # Servicios para consumir API
│   ├── context/          # Contextos de React (ej. autenticación)
│   ├── hooks/            # Custom hooks
│   ├── App.jsx            # Componente principal
│   └── main.jsx           # Punto de entrada
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md
```

---

### Instrucciones 
1. **Clonar o descargar** el repositorio del proyecto.  
2. **Establecer variables de entorno.**  
   - Copiar `.env.example` y renombrar como `.env`
   - Abrir una nueva terminal en el proyecto raiz del **Backend** y levantar servidor, posteriormente copiar la url del servidor corriendo, ejemplo: http://127.0.0.1:8000/
   - Establecer la **Conexion del Frontend con el Backend** en el archivo `.env` estructura de ejemplo: VITE_API_BASE_URL=http://127.0.0.1:8000/

4. **Instalar Dependencias**  
   Abrir una terminal en el directorio raíz del proyecto y ejecute:  
   ```bash
   npm install
4. **Levantar servidor**  
   ```bash
   npm run dev
---


---
## 🚀 Credenciales

- **Correo:** `admin@example.com`  
- **Contraseña:** `123456#` 
---

