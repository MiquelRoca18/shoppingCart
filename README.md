# 🛒 Tienda React - E-commerce

Este proyecto es una aplicación web de una tienda en línea creada con **React**. Permite a los usuarios explorar productos, filtrarlos según precio y categoría, agregar productos al carrito de compras, y ajustar la cantidad deseada para cada artículo en el carrito.

## 🖥️ Funcionalidades principales

1. **Listado de productos**: Muestra todos los productos disponibles de un archivo JSON, permitiendo a los usuarios explorar las distintas opciones.

2. **Filtrado por precio y categoría**: Los usuarios pueden:
   - Filtrar los productos por rango de precios (de menor a mayor o viceversa).
   - Filtrar por categorías específicas para encontrar más fácilmente el tipo de producto que buscan.

3. **Carrito de compras**:
   - Los productos se pueden agregar al carrito, donde el usuario puede:
     - Aumentar o disminuir la cantidad de un producto en el carrito.
     - Ver un resumen del total de productos seleccionados.
     - Eliminar productos del carrito.

4. **Gestión de cantidades**: Permite al usuario especificar la cantidad de cada producto que desea comprar, con la posibilidad de modificar esta cantidad desde el carrito.

## 🛠️ Tecnologías utilizadas

- **React**: Framework de JavaScript para construir la interfaz.
- **Hooks**: Manejo de estado y efectos dentro de los componentes funcionales.
- **JSON**: Archivo con los datos de los productos simulando una base de datos.
- **Tailwind**: Estilos básicos para la interfaz del usuario.

## 🚀 Instrucciones para la instalación

1. Clona el repositorio:

    ```bash
    git clone https://github.com/MiquelRoca18/shoppingCart.git
    ```

2. Instala las dependencias:

    ```bash
    cd shoppingCart
    npm install
    ```

3. Ejecuta la aplicación:

    ```bash
    npm run dev
    ```

## 🌟 Futuras mejoras

- Agregar paginación para una mejor experiencia de usuario en el listado de productos.
- Implementar integración con una API para manejar productos de forma dinámica.
- Incluir un sistema de autenticación y perfiles de usuario.
