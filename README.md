# Rincón Sabanero – Sistema POS para Restaurante

Una aplicación móvil y página web desarrolladas, que simulan un sistema de punto de venta (POS) para un restaurante de comida típica. Su propósito es gestionar pedidos, roles de usuarios y operaciones internas mediante la integración con servicios BaaS (Backend as a Service) para almacenar información e imágenes en la nube.

## Descripción

Rincón Sabanero busca optimizar la atención y administración en restaurantes, ofreciendo una herramienta digital que facilita la interacción entre clientes, chefs y cajeros.
El sistema permite que:

- Clientes realicen pedidos y visualicen el menú desde la app o la web, pudiendo utilizar la cámara para el escaneo de códigos QR.

- Chefs reciban los pedidos en tiempo real y actualicen su estado, además de poder subir información e imagenes de los productos ofrecidos utilizando la cámara del teléfono.

- Cajeros gestionen cobros, facturación y el cierre de órdenes.

## Objetivos

Desarrollar una plataforma funcional y moderna para la gestión de ventas en restaurantes.

Implementar roles diferenciados para cada tipo de usuario.

Integrar servicios en la nube (Firebase y Supabase) para el manejo eficiente de datos e imágenes.

Crear una interfaz simple, intuitiva y adaptable a distintos dispositivos (móvil y web).

## Roles del Sistema
### Cliente

Registro e inicio de sesión.

Visualización del menú con imágenes y precios.

Selección de productos y generación de pedidos.

Seguimiento del estado del pedido (en preparación, listo, entregado).

### Chef

Subida de los productos ofrecidos a la base de datos.

Acceso al panel de pedidos activos.

Actualización del estado de cada pedido.

Visualización de detalles: productos, cantidad, observaciones del cliente.

### Cajero

Revisión de pedidos completados.

Registro de pagos y generación de facturas.

Control del historial de ventas diarias.

## Tecnologías y Herramientas

Frontend: React Native (para app móvil y visualización web)

Backend as a Service:

Firebase Authentication: Manejo de registro e inicio de sesión.

Firestore: Base de datos para pedidos, usuarios y chats.

Supabase: Almacenamiento de imágenes de productos.

Desarrollo y compilación móvil: Expo
