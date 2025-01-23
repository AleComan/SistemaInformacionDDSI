# Sistema de Información de una Licorería.

Este sistema de información tiene como objetivo gestionar eficientemente las operaciones clave de una licorería. El sistema está diseñado para ser modular, componiéndose de cinco subsistemas principales, cada uno encargado de diferentes aspectos de la operación del negocio.

## Tabla de Contenidos

- [Descripción General](#descripción-general)

- [Subsistemas](#subsistemas)

  - [Gestión de Inventario](#subsistema-de-gestión-de-inventario)
  
  - [Gestión de Ventas](#subsistema-de-gestión-de-ventas)
  
  - [Gestión de Clientes](#subsistema-de-gestión-de-clientes)
  
  - [Gestión de Proveedores](#subsistema-de-gestión-de-proveedores)
    
  - [Informes y Análisis](#subsistema-de-informes-y-análisis)
    
- [Requisitos del Sistema](#requisitos-del-sistema)
  
- [Sentencias SQL](#sentencias-sql-para-crear-la-base-de-datos)

- [Autor](#autor)

---

## Descripción General

El sistema permite:
- Control de inventarios, asegurando que los productos estén disponibles para satisfacer la demanda.
- Gestión de ventas, facturación y promociones.
- Seguimiento de clientes, sus compras y preferencias.
- Relación eficiente con proveedores, incluyendo pedidos y devoluciones.
- Generación de informes detallados y análisis de datos para la toma de decisiones.

Cada subsistema está diseñado para integrarse de manera fluida con los demás, asegurando una experiencia robusta y eficiente para los usuarios.

---

## Subsistemas

### Subsistema de Gestión de Inventario
Gestión eficiente de productos en inventario:
- **RF1.1:** Registrar productos (alta).
- **RF1.2:** Modificar stock.
- **RF1.3:** Consultar stock.
- **RF1.4:** Generar alertas por bajo stock.
- **RF1.5:** Dar de baja productos (descatalogar).

### Subsistema de Gestión de Ventas
Control completo del ciclo de ventas:
- **RF2.1:** Registrar ventas.
- **RF2.2:** Generar recibos o facturas.
- **RF2.3:** Aplicar descuentos y promociones.
- **RF2.4:** Consultar historial de ventas.
- **RF2.5:** Gestionar devoluciones.

### Subsistema de Gestión de Clientes
Facilita la interacción y gestión de datos de clientes:
- **RF3.1:** Dar de alta clientes.
- **RF3.2:** Consultar historial de compras.
- **RF3.3:** Editar datos de clientes.
- **RF3.4:** Enviar notificaciones (email/SMS).
- **RF3.5:** Dar de baja clientes.

### Subsistema de Gestión de Proveedores
Optimiza la relación con los proveedores:
- **RF4.1:** Registrar nuevos proveedores.
- **RF4.2:** Realizar pedidos.
- **RF4.3:** Consultar historial de compras.
- **RF4.4:** Cancelar pedidos.
- **RF4.5:** Marcar pedidos como completados.
- **RF4.6:** Dar de baja proveedores.

### Subsistema de Informes y Análisis
Herramientas avanzadas para la toma de decisiones:
- **RF5.1:** Generar informes de ventas por intervalo.
- **RF5.2:** Análisis de productos más vendidos.
- **RF5.3:** Análisis de ingresos por producto.
- **RF5.4:** Informes de pedidos por intervalo.
- **RF5.5:** Análisis de ventas por familias de productos.

---

## Requisitos del Sistema
- **Lenguaje de programación:** Python y SQL
- **Dependencias:** Librería `oracledb` para conectarse a la base de datos.
- **Base de datos:** Cualquier base de datos SQL, con la que poder conectarse mediante la librería `oracledb`
- **Configuración mínima:** Jupyter Notebook, entorno de python con librería `oracledb`

## Sentencias SQL para crear la base de datos
Además del código en python en `sistemaLicoreria.ipynb`, contamos con los siguientes archivos SQL:
- **Tablas:** para crear las tablas del sistema de información.
- **Disparadores:** para crear los distintos disparadores usados en este sistema de información.
- **Secuencias:** usadas principalmente para formato en los códigos de venta, detalle de venta, ...

## Autor

**Alejandro Coman Venceslá**  
Estudiante de Ingeniería Informática, Universidad de Granada.  
