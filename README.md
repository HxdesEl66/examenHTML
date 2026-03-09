# 🛍️ StyleStore – E-commerce de Ropa

Proyecto Front-End que simula una experiencia de compra moderna para una tienda de ropa online.
El objetivo es construir una **interfaz simple, visual y confiable**, priorizando el descubrimiento de productos, la comparación rápida y una ruta clara hacia el checkout.

---

# 📌 Información del Proyecto

**Desarrollador:** Kevin Andres Castillo Pabón
**Trainer / Profesor:** Jholver Pardo

Este proyecto fue desarrollado como práctica de **Front-End con HTML y CSS nativo**, siguiendo un diseño basado en un wireframe de Figma.

---

# 🎯 Objetivo

Construir una experiencia de compra simple, visual y confiable para ropa, priorizando:

* Descubrimiento de productos
* Comparación rápida
* Navegación clara hasta el proceso de compra

La interfaz está diseñada para ser **intuitiva y limpia**, enfocada en mejorar la experiencia del usuario.

---

# ⚠️ Problemática

Muchos e-commerce de moda suelen ser recargados o poco intuitivos.
Esto provoca que los usuarios se confundan, tarden más en encontrar productos o abandonen la compra.

Este proyecto busca **reducir la fricción en la navegación**, utilizando:

* UI limpia
* Tarjetas de producto (product cards)
* Calificaciones visibles
* Variaciones de talla y color
* Jerarquías visuales claras

Todo esto ayuda a que el usuario **encuentre y decida más rápido**.

---

# 👥 Público Objetivo

El diseño está pensado principalmente para:

### 📱 Compradores Mobile-First

Usuarios que navegan principalmente desde dispositivos móviles y desean explorar productos fácilmente.

### 🤔 Usuarios Indecisos

Usuarios que necesitan señales de confianza como:

* Precios visibles
* Calificaciones
* Información clara del producto

### 🔁 Usuarios Recurrentes

Clientes que esperan:

* Acceso rápido al carrito
* Interacciones claras
* Feedback visual inmediato

⚠️ Importante:
Todas las interacciones se representan visualmente.
**No existe lógica funcional ni JavaScript.**

---

# 🚀 Funcionalidades Principales

## 1️⃣ Página de Inicio

La página principal permite explorar productos rápidamente.

Incluye:

* Saludo personalizado con **nombre del usuario y avatar**
* **Barra de búsqueda** para encontrar productos
* Categorías de productos:

  * Vestidos
  * Camisetas
  * Pantalones
* **Tarjetas de producto** con:

  * Imagen
  * Botón de favoritos
  * Título
  * Categoría
  * Precio
  * Calificación
* **Menú móvil** con acceso a:

  * Inicio
  * Carrito
  * Favoritos
  * Perfil

---

## 2️⃣ Página de Detalle del Producto

Vista enfocada en la información del producto.

Contiene:

* Imagen principal del producto
* Botón **Atrás**
* Botón **Añadir a favoritos**
* Información del producto:

  * Título
  * Calificación
  * Número de visualizaciones
* Selector de **cantidad**
* Botón **Read More** para mostrar descripción completa
* Opciones de personalización:

  * Tallas
  * Colores
* Botón de compra que muestra el **precio total dinámico (visual)**

---

## 3️⃣ Página de Checkout (Carrito)

Página final del proceso de compra.

Incluye:

* Navegación superior con:

  * Botón **Atrás**
  * Menú hamburguesa
  * Título **Checkout**

### Detalle del producto

Tarjetas con:

* Imagen
* Título
* Categoría
* Precio
* Cantidad
* Controles para modificar cantidad

### Información de pago

Sección que muestra:

* Método de pago (tarjeta)
* Total de productos
* Costo de envío
* Descuentos
* Subtotal

### Botón de pago

Botón **Pay** que simula la confirmación de compra mediante un **modal visual**.

---

# 🧰 Tecnologías Utilizadas

Este proyecto fue desarrollado utilizando únicamente:

* **HTML5**
* **CSS3**

Características implementadas:

* Responsive Design
* Media Queries
* Layout moderno con Flexbox / Grid
* Arquitectura organizada de archivos
* UI basada en diseño de Figma

⚠️ No se utilizaron:

* JavaScript
* Frameworks
* Librerías externas

---

# 📂 Arquitectura del Proyecto

```
app_de_ecommerce_de_ropa/

│
├── css/
│   ├── style.css
│   ├── detail.css
│   ├── checkout.css
│   └── variables.css
│
├── storage/
│   ├── font/
│   │   └── encode_sans/
│   │
│   └── img/
│
├── views/
│   ├── detail.html
│   └── checkout.html
│
└── index.html
```

La estructura permite separar claramente:

* **Estilos**
* **Vistas**
* **Recursos (assets)**

Esto mejora la **mantenibilidad y escalabilidad del proyecto**.

---

# 🎨 Recursos Utilizados

## Diseño

Figma (Wireframe base del proyecto)

## Otros Recursos

* Barra de búsqueda (Inicio)
* Menú hamburguesa (Checkout)

Algunos recursos eran **opcionales**, mientras que otros eran **obligatorios según el documento del proyecto**.

En caso de no utilizarlos, se debían buscar alternativas similares que **no afectaran el diseño original**.

---

# ⚙️ Restricciones Técnicas

El proyecto debía cumplir con las siguientes condiciones:

* Uso exclusivo de **HTML y CSS nativo**
* No usar librerías ni frameworks
* Diseño **responsive usando media queries**
* Fidelidad visual al diseño de Figma
* Estructura de carpetas definida
* Uso de **Git y GitHub**

Control de versiones utilizando **Conventional Commits**.

La rama **main** se utiliza como rama de presentación.

---

# 📦 Resultado Esperado

El proyecto debe entregarse mediante un:

Repositorio **GitHub privado** que incluya:

* Código fuente del proyecto
* Estructura de carpetas requerida
* Navegación entre las tres vistas
* Diseño responsive
* Fidelidad visual al diseño de Figma

Opcionalmente:

* Deploy en **GitHub Pages**

---

# ✨ Vista General del Proyecto

El sistema incluye tres vistas principales:

* 🏠 Página de Inicio
* 👗 Página de Detalle del Producto
* 💳 Página de Checkout

Cada una diseñada para ofrecer una **experiencia clara, moderna y centrada en el usuario**.

---

# 👨‍💻 Autor

**Kevin Andres Castillo Pabon**

Proyecto desarrollado como práctica de **Front-End Development**.

---

# 📚 Agradecimientos

A mi trainer **Jholver Pardo** por la guía durante el desarrollo del proyecto y por proporcionar la estructura y lineamientos del ejercicio.

---
