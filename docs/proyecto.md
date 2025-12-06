# Proyecto Integrador

## 1. Introducción
El comercio online cada vez es más usado, pero muchas tiendas tienen precios diferentes y ofertas complicadas que confunden al cliente.  
El proyecto consiste en crear una tienda online donde todos los productos cuesten 10€, haciendo la compra más fácil y rápida. Los usuarios podrán ver los productos organizados por categorías, añadirlos al carrito y completar la compra de forma sencilla.  
Esta tienda busca ofrecer una experiencia clara y práctica, con productos económicos al alcance de todos.

## 2. Análisis de la problemática
Muchas tiendas online tienen precios y ofertas diferentes que confunden al cliente, lo que hace que comprar sea más lento y difícil.  
El proyecto busca mejorar esto creando una tienda donde todos los productos cuesten 10€, con categorías claras, páginas de detalle profesionales, carritos de compra claros, etc. Así, la navegación será más fácil y la compra más rápida.

## 3. Objetivos
- Crear una tienda online con todos los productos a 10€, fácil de usar y atractiva visualmente.  
- Organizar los productos en categorías claras para que el usuario encuentre lo que busca rápidamente.  
- Permitir añadir productos al carrito y realizar pagos reales mediante PayPal de forma segura.  

**Alcance:** Solo productos con precio fijo de 10€ y funcionalidades básicas de compra.  
**Límites:** No se incluirán envíos reales.

## 4. Fases o etapas del proyecto
1. **Planificación del diseño y funcionalidades de la web (1 semana)**  
   Diseño definitivo en Figma de la web con navegación, funcionalidad y diseño.  

2. **Desarrollo del backend (4 semanas)**  
   Implementación de la lógica del servidor, comprobación con Postman.  

3. **Desarrollo del frontend (3 semanas)**  
   Creación de la interfaz de la web y enlace con el backend.  

4. **Retoques estéticos (1 semana)**  
   Mejoras visuales, animaciones y ajustes de diseño.  

5. **Pruebas y ajustes finales (1-2 semanas)**  
   Comprobación de funcionalidad completa y optimización del código.

## 5. Herramientas y tecnologías
**Frontend:** Figma, Angular, HTML, CSS, JavaScript, IDE: IntelliJ IDEA o VS Code  
**Backend:** Node.js (Nest.js), Base de datos: MongoDB, Postman  
**Otros:** Herramientas de edición y pruebas según necesidad

## 6. Fechas propuestas
- Planificación y diseño: primera semana de noviembre  
- Desarrollo del backend: noviembre – primera mitad de diciembre  
- Desarrollo del frontend: diciembre  
- Retoques y pruebas finales: finales de diciembre – enero  

## 7. Plan de despliegue

El despliegue del Proyecto Integrador (tienda online con productos a 10€) se realizará en dos partes: el **backend** y el **frontend**. En esta sección explicamos de forma sencilla cómo se pondrá en marcha el proyecto usando las tecnologías trabajadas en clase.

### 1. Despliegue del Backend

El backend estará hecho con **Nest.js** y se conectará a una base de datos **MongoDB**.

Para desplegarlo en un servidor Debian (o máquina local) seguiremos estos pasos:

```bash
# Clonar el repositorio del backend
git clone <URL-del-backend>
cd backend

# Instalar dependencias
npm install

# Iniciar el servidor
npm run start

# Comprobar funcionamiento
# Abrir en navegador o Postman
http://localhost:3000

# Clonar el repositorio del frontend
git clone <URL-del-frontend>
cd frontend

# Instalar dependencias
npm install

# Iniciar el servidor de desarrollo
ng serve

# Abrir en el navegador
http://localhost:4200
