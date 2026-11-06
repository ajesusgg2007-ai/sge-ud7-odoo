# Proceso de Venta: De Presupuesto a Factura

Detalle cronológico de las operaciones comerciales de PlasteeCups ejecutadas por los roles correspondientes:

## 1. Creación del Presupuesto
- Usuario responsable: antonio.gomez@plasteecups.test`
- **Referencia del documento:** `S0001`
- **Cliente asociado:** Alejandro Pérez Gómez
- **Detalle de líneas:**
  - 1x Bolsa de Vasos de plástico tamaño Grande 2,30€
  - 1x Bolsa vasos de plástico de chupito 1,20€
  - 1x Candado U-Lock Antirrobo Pro — Bolsa de vasos de plástico estandar 0,90€
- **Condiciones:** Plazo de pago a 30 días / Validez de 15 días.
- **Estado inicial:** Presupuesto enviado.
- **Evidencia adjunta:** venta/presupuesto.pdf

## 2. Confirmación del Pedido de Venta
- **Usuario responsable:** `ventas@plasteecups.test` 
- **Referencia del documento:** `S00012`
- **Acción:** Conversión de presupuesto a pedido firme.
- **Estado:** Pedido de Venta Confirmado .

## 3. Validación de Salida en Inventario
- **Usuario responsable:** `ventas@plasteecups.test`
- **Referencia de la orden de entrega:** `WH/OUT/00001`
- **Acción:** Validación de cantidades y control de salida de stock físico.
- **Estado:** Hecho / Entregado .

## 4. Facturación y Registro de Cobro
- **Usuario responsable:** `admin@plasteecups.test` 
- **Referencia de factura:** `INV/2026/00001`
- **Estado final:** Publicada y **Pagada**.
- **Evidencia adjunta:** `venta/factura.pdf`