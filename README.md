# Sellder - Cotizador para Línea Blanca

Sellder es una aplicación web sencilla y eficiente diseñada para gestionar productos y generar cotizaciones de línea blanca (electrodomésticos). Permite a los vendedores crear cotizaciones profesionales de manera rápida y exportarlas como imágenes para enviarlas fácilmente a los clientes.

## 🚀 Características Principales

- **Gestión de Productos**: Agregar, visualizar y eliminar productos del inventario con sus respectivos precios y categorías.
- **Asistente de Cotización (Wizard)**: Un flujo paso a paso intuitivo para crear nuevas cotizaciones:
  1. Datos del Cliente
  2. Selección de Productos (con cálculo de subtotales)
  3. Servicios Adicionales (Armado/Instalación)
  4. Despacho a Domicilio
  5. Resumen Final
- **Historial de Cotizaciones**: Registro de todas las cotizaciones generadas.
- **Exportación a Imagen**: Capacidad de descargar el resumen de la cotización como una imagen (.png) con un diseño profesional listo para compartir con el cliente.
- **Almacenamiento Local**: Los datos (productos, historial y estado de sesión) se guardan en el `localStorage` del navegador, por lo que no requiere de una base de datos externa para funcionar.

## 🛠️ Tecnologías Utilizadas

- **HTML5** y **JavaScript Vanilla**: Lógica de la aplicación y estructura.
- **Tailwind CSS**: Estilos modernos y responsivos (cargado vía CDN).
- **Lucide Icons**: Iconografía elegante e intuitiva.
- **html2canvas**: Librería para renderizar y exportar el resumen de la cotización a imagen.

## 📦 Instalación y Uso

Dado que es una aplicación estática (Client-side), no requiere instalación compleja ni configuración de servidores backend.

1. Clona o descarga este repositorio.
2. Puedes abrir directamente el archivo `index.html` en tu navegador web de preferencia.
3. Para una mejor experiencia (especialmente para evitar problemas de CORS con la exportación de imágenes locales), se recomienda usar un servidor local como [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) en VSCode, o `npx live-server` desde la terminal:
   ```bash
   npx live-server
   ```

## 🔐 Acceso de Demostración

La aplicación cuenta con una pantalla de inicio de sesión de prueba. 

- **Usuario:** `demo`
- **Contraseña:** `demo`

---
*Desarrollado para facilitar las ventas de línea blanca.*
