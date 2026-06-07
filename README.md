# 🧾 FacturaCR

Sistema de facturación personal hecho para Costa Rica. Sin servidores, sin cuentas, sin suscripciones — corre 100% en el navegador.

## ¿Qué hace?

Permite emitir facturas electrónicas con formato profesional costarricense, gestionar clientes y productos, y llevar el control de cuentas por cobrar a crédito.

## Módulos

### 📄 Facturas
- Crear facturas electrónicas con numeración automática
- Cliente desde el catálogo **o ingreso manual** (con opción de guardarlo)
- Líneas de detalle desde el catálogo o ingresadas a mano
- IVA 13% opcional
- Colones (₡) o Dólares ($)
- Condición de pago: contado o crédito (15, 30, 60 días o personalizado)
- Fecha de vencimiento automática según la condición
- Notas y observaciones
- Vista previa, **descarga en PDF** e impresión

### 💳 Créditos
- Listado de todas las facturas emitidas a crédito
- Muestra: total, abonado y saldo pendiente por factura
- Barra de progreso visual del cobro
- Registro de abonos con fecha, monto y descripción
- Historial de abonos por factura
- Marcado automático de facturas **vencidas** y **canceladas**
- Filtro: todos / con saldo pendiente / cancelados
- Estadísticas globales: total créditos, total cobrado, por cobrar

### 📦 Productos
- Catálogo reutilizable de productos y servicios
- Tipo: Producto o Servicio
- Precio unitario base
- Descripción adicional opcional

### 👤 Clientes
- Directorio de clientes con nombre, cédula, correo, teléfono y dirección
- Editable en cualquier momento

### ⚙️ Mi Empresa
- Datos del emisor: nombre/razón social, cédula jurídica, dirección, teléfono, correo, actividad económica
- Se imprimen automáticamente en todas las facturas

## Stack

HTML · CSS · JavaScript vanilla · [jsPDF](https://github.com/parallax/jsPDF) — cero dependencias propias, cero build, cero backend.

## Datos y persistencia

Todo se guarda en `localStorage` del navegador. Los datos persisten aunque cerrés el navegador o reiniciés el equipo. No hay sincronización entre dispositivos.

## Uso

Abre `index.html` en cualquier navegador moderno. No necesita servidor.

O accedé a la versión en línea: https://factura-electronica-jky.vercel.app

## Limitaciones conocidas

- Sin sincronización entre dispositivos (localStorage es local)
- El envío de correo no está disponible sin backend
- No es un sistema homologado por el Ministerio de Hacienda de Costa Rica — es para uso personal y control interno

## Autor

Hecho para uso personal por **Janrosky** Alejandro Chacón Garita 🇨🇷 · Cartago, Costa Rica
