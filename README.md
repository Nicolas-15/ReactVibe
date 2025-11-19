# ReactVibe 🎨⚡

**ReactVibe** es una aplicación frontend desarrollada con **React.js**, diseñada como una interfaz moderna y responsiva para visualizar productos (cartas TCG u otros artículos). Su objetivo es ofrecer una UI limpia, rápida y fácil de integrar con cualquier API backend —incluyendo tus microservicios de Spring Boot.

---

## 🚀 Tecnologías Utilizadas

- **React.js**
- **JavaScript (ES6+)**
- **Bootstrap / CSS**
- **Axios** (para consumo de APIs)
- **React Router DOM**
- **Node.js + npm / yarn**

---

## 📂 Estructura del Proyecto

src/
│
├── components/ # Componentes reutilizables
├── pages/ # Páginas principales (Home, Productos, Detalle, Carrito)
├── services/ # Funciones para consumir APIs externas
├── assets/ # Imágenes y recursos estáticos
│
├── App.js # Componente raíz
└── index.js # Punto de entrada del proyecto
---

## 🧩 Funcionalidades Principales

- ✔ Mostrar un catálogo completo de productos  
- ✔ Ver detalles de cada artículo  
- ✔ Filtrar por categoría / tipo  
- ✔ Integración con backend mediante REST API  
- ✔ Navegación multipágina con React Router  
- ✔ Interfaz minimalista orientada a ecommerce  

---

## ▶️ Cómo Ejecutar el Proyecto

1️⃣ **Clonar el repositorio**

```bash
git clone https://github.com/Nicolas-15/ReactVibe.git
2️⃣ Acceder al proyecto

bash
Copiar código
cd ReactVibe
3️⃣ Instalar dependencias

bash
Copiar código
npm install
# o
yarn install
4️⃣ Ejecutar la aplicación

bash
Copiar código
npm start
# o
yarn start
5️⃣ Abrir en el navegador

arduino
Copiar código
http://localhost:3000
🌐 Integración con Backend (Opcional)
Puedes conectarlo fácilmente a tus APIs hechas en Spring Boot, por ejemplo:

js
Copiar código
import axios from "axios";

export const getProductos = () =>
  axios.get("http://localhost:8080/api/productos");
Tu aplicación queda lista para funcionar como frontend de un ecommerce minimalista.

📌 Estado del Proyecto
En desarrollo, expandiéndose para incluir:

Sistema de carrito

Autenticación de usuarios

Integración con pasarela de pago

Dashboard administrativo

Conexión a múltiples microservicios

📄 Licencia
Proyecto de uso libre para fines educativos y de práctica.

👤 Autor
Nicolás López
💼 Estudiante de Ingeniería en Informática
🔗 GitHub: Nicolas-15
