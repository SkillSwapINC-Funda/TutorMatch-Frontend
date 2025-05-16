
# 📘 TutorMatch – Plataforma de Tutorías Académicas

## 📌 Descripción del Proyecto

**TutorMatch** es una plataforma que conecta estudiantes con tutores académicos calificados, diseñada exclusivamente para la comunidad universitaria **UPC**. Permite a los estudiantes acceder a apoyo académico personalizado y a los tutores ofrecer sus servicios de enseñanza.

Presentamos sus características clave, tecnologías utilizadas, guía de instalación, estructura del proyecto y cómo contribuir.

> 🎯 Objetivo: Facilitar la conexión entre estudiantes y tutores, optimizando el aprendizaje y mejorando el rendimiento académico.

---

## 🚀 Características Principales

- 🧑‍🏫 **Sistema de Perfiles**: Perfiles completos para tutores y estudiantes con fotos, info académica y contacto.
- 🗂️ **Gestión de Tutorías**: Crear, editar y eliminar ofertas de tutoría fácilmente.
- 🕒 **Disponibilidad Horaria**: Selección intuitiva de franjas horarias.
- 📩 **Sistema de Contacto**: Comunicación vía correo o WhatsApp.
- 🌙 **Interfaz Moderna**: Diseño atractivo con **modo oscuro**.
- 🆘 **Centro de Soporte**: Formulario de contacto para consultas o reportes.

---

## 🛠️ Tecnologías Utilizadas

| Área        | Tecnología                           |
|-------------|---------------------------------------|
| **Frontend** | React 18 + TypeScript                |
| **Build**    | Vite (desarrollo rápido)             |
| **Estado**   | Context API                          |
| **Estilos**  | TailwindCSS (responsive y personalizable) |
| **UI**       | PrimeReact (componentes avanzados)   |
| **Auth**     | Sistema seguro con recuperación de contraseña |
| **Media**    | Soporte para imágenes de perfil y tutorías |

---

## ⚙️ Instalación y Configuración

1. **Clona el repositorio**
   
   git clone https://github.com/SkillSwapINC-Funda/TutorMatch-Frontend
   cd TutorMatch-Frontend


2. **Instala las dependencias**

   ```bash
   npm install
   ```

3. **Configura variables de entorno**

   * Crea un archivo `.env.local` basado en `.env.example`
   * Completa las variables necesarias para conexión con el backend

4. **Ejecuta el servidor de desarrollo**

   ```bash
   npm run dev
   ```

---

## 📁 Estructura del Proyecto

```
📂 src
 ┣ 📁 user/         → Gestión de usuarios y autenticación
 ┣ 📁 tutoring/     → Gestión de tutorías
 ┣ 📁 course/       → Cursos y semestres
 ┣ 📁 dashboard/    → Interfaz principal del usuario
 ┣ 📁 public/       → Páginas públicas y componentes compartidos
 ┗ 📁 support/      → Sistema de soporte y ayuda
```

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Sigue estos pasos:

1. Haz un **fork** del repositorio
2. Crea una nueva rama:

   ```bash
   git checkout -b feat/mi-funcionalidad
   ```
3. Realiza tus cambios y haz commit:

   ```bash
   git commit -m "Add mi funcionalidad"
   ```
4. Sube tu rama:

   ```bash
   git push origin feat/mi-funcionalidad
   ```
5. Abre un **Pull Request**

---

## 📬 Contacto y Soporte

Para consultas o soporte técnico:

* ✉️ Correo: [rlopezhuaman321@gmail.com](mailto:rlopezhuaman321@gmail.com)
* 🕘 Horario de atención: Lunes a Viernes, 9:00 a.m. – 6:00 p.m.


