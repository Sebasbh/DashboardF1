# F1 Dashboard - Proyecto Full Stack

## Descripción
Dashboard interactivo de Fórmula 1 que permite visualizar datos de pilotos, escuderías y carreras de la temporada 2025.  
El proyecto está diseñado como ejemplo de buenas prácticas en **desarrollo full-stack**, con frontend en React y Material UI, y backend en Node.js con Express.

---

## Características
- Visualización de pilotos y escuderías en tablas interactivas (`DataGrid` de Material UI)  
- Estadísticas y comparativas mediante gráficos interactivos (Recharts)  
- Filtros y búsqueda por piloto, escudería y circuito  
- Área de favoritos (requiere autenticación JWT)  
- Responsive y accesible (Roles ARIA, navegación con teclado)  
- Modo oscuro usando Material UI ThemeProvider  

---

## Stack Tecnológico

### Frontend
- **React** con Hooks y React Router  
- **Material UI** para diseño y componentes preconstruidos  
- **Axios** para consumir API backend  
- **Recharts** para gráficos interactivos  
- **React Testing Library** para pruebas de componentes  

### Backend
- **Node.js** con **Express.js**  
- **JWT** para autenticación (opcional)  
- **Axios** para consumo de API externa (Ergast API)  
- **MongoDB/MySQL** para persistencia de favoritos o datos de usuario  

### DevOps / Deployment
- Frontend: **Vercel** o **Netlify**  
- Backend: **Google Cloud** o **Render**  
- Base de datos en la nube: **MongoDB Atlas** o **MySQL Cloud**  
- CI/CD con **GitHub Actions**  

---

## Estructura del Proyecto

f1-dashboard/
├─ backend/
│  ├─ controllers/
│  ├─ routes/
│  ├─ models/
│  ├─ middleware/
│  └─ server.js
├─ frontend/
│  ├─ src/
│  │  ├─ components/
│  │  ├─ pages/
│  │  ├─ services/
│  │  └─ App.jsx
├─ README.md
└─ package.json

---

## Instalación y Ejecución

### Backend
cd backend
npm install
npm run dev

Frontend

cd frontend
npm install
npm start


⸻

Uso
	•	Navega por el dashboard para ver:
	•	Clasificación de pilotos y escuderías
	•	Resultados de cada carrera
	•	Comparativa de estadísticas
	•	Favoritos y personalización (si autenticación habilitada)

⸻

Contribuciones

Este proyecto puede ser extendido con:
	•	Más estadísticas históricas
	•	Integración con noticias de F1
	•	Funcionalidad en tiempo real usando WebSockets

⸻

Autor

Sebas - Tu GitHub￼

⸻

Licencia

MIT License

---
