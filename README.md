# 📌 Hito 17 – Pizzería Mamma Mía

Este proyecto corresponde al **Hito 17 – Pizzería Mamma Mía** del bootcamp **Desafío Latam**, donde se aplican los conocimientos de **Introducción a React** y creación de componentes reutilizables para construir una mini tienda de pizzas.

---

## 🚀 Objetivo del desafío
- Crear un proyecto React con Vite.js.  
- Implementar componentes: **Navbar**, **Footer**, **Home**, **Header** y **CardPizza**.  
- Usar **props** y **variables internas** para mostrar información dinámica (pizzas, precios, estado de usuario).  
- Aplicar condicionales en JSX para mostrar botones según la variable `token`.  
- Mostrar el total de la compra con separador de miles usando `toLocaleString`.  

---

## ✅ Requerimientos cumplidos
- **App.jsx**: muestra los componentes **Navbar**, **Home** y **Footer**.  
- **Header.jsx**: componente dentro de `Home.jsx` con título y descripción.  
- **Navbar.jsx**: menú con botones 🍕 Home, 🔓 Profile, 🔒 Logout, 🔐 Login, 🔐 Register y 🛒 Total: $; botones Home y Total siempre visibles; condicionales según `token`.  
- **CardPizza.jsx**: muestra nombre, precio, ingredientes e imagen de cada pizza usando props; tres instancias en `Home.jsx`:
  - Napolitana, 5950, ["mozzarella", "tomates", "jamón", "orégano"]  
  - Española, 6950, ["mozzarella", "gorgonzola", "parmesano", "provolone"]  
  - Pepperoni, 6950, ["mozzarella", "pepperoni", "orégano"]  
  - Botones **Ver más** y **Añadir** incluidos sin funcionalidad.
- **Footer.jsx**: contiene `© 2021 - Pizzería Mamma Mia! - Todos los derechos reservados` y se llama en `App.jsx`.  

---

## 🛠️ Tecnologías utilizadas
- React con Vite.js  
- Bootstrap (opcional)  
- HTML5 y CSS3  
- JavaScript moderno (props, JSX, condicionales)  
- Git para control de versiones  

## ▶️ Cómo ejecutar el proyecto

1. Clona este repositorio:
```bash
git clone https://github.com/NicoMunozJS/desafio-17-formularios-react
