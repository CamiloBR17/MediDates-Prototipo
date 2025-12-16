# 🩺 MediDates – Prototipo UI/UX  
**Plataforma médica multi-rol (Paciente · Médico · Administrador)**

MediDates es un **prototipo web UI/UX no funcional** desarrollado para el curso **Diseño y Gestión de Sistemas** en la  
**Universidad del Valle de México (UVM)**.

El proyecto simula visualmente una plataforma médica moderna orientada a la **gestión de citas, historial clínico y perfiles de usuario**, aplicando una **metodología ágil basada en sprints** para mostrar su evolución progresiva.

---

## 📌 Objetivo del proyecto

Diseñar y documentar la **experiencia de usuario, navegación y arquitectura visual** de un sistema médico digital, mostrando:

- Flujo completo de navegación
- Diferenciación clara de roles
- Diseño profesional y consistente
- Preparación para una futura implementación funcional

⚠️ **Este prototipo no cuenta con backend ni base de datos.**  
Toda la funcionalidad es simulada con fines académicos.

---

## 👥 Roles del sistema

MediDates contempla **tres tipos de usuario**, cada uno con su propio dashboard y flujo:

### 🧑‍⚕️ Paciente
- Dashboard principal
- Mis citas
- Agendar cita
- Historial médico
- Mis médicos
- Perfil del usuario

### 🩺 Médico
- Dashboard médico
- Mis citas
- Pacientes
- Perfil del médico

### 🛠️ Administrador
- Dashboard administrativo
- Gestión de usuarios
- Gestión de médicos
- Gestión de citas
- Configuración del sistema

---

## 🗂️ Estructura del proyecto

📁 MediDates
├── index.html / login.html
├── register.html
├── forgot-password.html
├── dashboard.html # Paciente
├── mis-citas.html
├── mis-medicos.html
├── agendar-cita.html
├── historial.html
├── perfil.html
│
├── doctor/
│ ├── dashboard-doctor.html
│ ├── mis-citas.html
│ ├── pacientes.html
│ └── perfil.html
│
├── admin/
│ ├── dashboard-admin.html
│ ├── usuarios.html
│ ├── medicos.html
│ ├── citas.html
│ └── configuracion.html
│
├── css/
│ └── styles.css # Estilos globales premium
│
├── img/
│ ├── logo-medidates.png
│ ├── avatars/
│ ├── doctors/
│ └── illustrations/
│
└── README.md


---

# 🚀 Avances por Sprint

## 🔵 Sprint 1 – Planeación y estructura base
- Identificación de pantallas necesarias
- Definición del flujo general
- Bocetos iniciales (wireframes)
- Decisión del prototipo web
- Asignación de roles del equipo

---

## 🟣 Sprint 2 – Diseño visual inicial
- Login profesional
- Dashboard del paciente
- Header fijo premium
- Iconografía base
- Quick actions
- Integración del logo MediDates
- Navegación básica Login → Dashboard

---

## 🔵 Sprint 3 – Navegación interna y pantallas completas
- Mis citas (filtros visuales)
- Mis médicos (tarjetas profesionales)
- Perfil del usuario
- Agendar cita con validaciones visuales
- Historial médico
- Footer unificado
- Alertas visuales (éxito y error)
- Microinteracciones UI
- Corrección de imágenes, tamaños y espaciados

---

## 🟢 Sprint 4 – Multi-rol y navegación completa
En este sprint se consolidó el sistema a nivel profesional:

### ✔ Login con selección de rol
- Paciente / Médico / Administrador
- Validaciones visuales
- Redirección automática por rol
- Recuperación de contraseña
- Cerrar sesión funcional

### ✔ Dashboards por rol
- Dashboard independiente para:
  - Paciente
  - Médico
  - Administrador
- Navegación completa entre todas las vistas
- Botones funcionales (simulados)

### ✔ UX/UI avanzado
- Ilustraciones médicas en español
- Avatares diferenciados
- Diseño consistente por rol
- Responsive design
- Paleta basada en el branding MediDates

📌 **El alcance del Sprint 4 se centra en experiencia de usuario y arquitectura visual.**

---

## 🔜 Sprint 5 – Planeado
- Simulación de lógica real en frontend:
  - Agendar, reprogramar y cancelar citas
  - Citas activas, pasadas y canceladas
  - Detalles del historial médico
  - Flujo completo paciente ↔ médico
- Preparación para integración con backend

---

## 🖥️ Cómo ejecutar el prototipo

1. Clonar o descargar el repositorio
2. Abrir la carpeta en **Visual Studio Code**
3. Ejecutar cualquier archivo `.html` con **Live Server**
4. Navegar usando los botones del prototipo

---

## 👥 Equipo MediDates

| Integrante | Rol | Responsabilidad |
|-----------|------|----------------|
| **Juan Camilo Bedoya Restrepo** | Director de Sistemas | Arquitectura UI, integración visual y lógica de navegación |
| Erick | UI/UX Designer | Diseño gráfico y componentes |
| Joel | Análisis y Finanzas | Modelo de negocio |
| Josué | Backend conceptual | Flujo futuro del sistema |
| Nelly | Documentación | Evidencia y reportes |

---

## 📬 Contacto
Proyecto académico – Universidad del Valle de México  
Desarrollado por **Juan Camilo Bedoya Restrepo**

---

# 💙 MediDates
Prototipo académico desarrollado con metodología ágil  
para fines educativos y de demostración visual.
