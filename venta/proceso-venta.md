# Proceso de Venta: De Presupuesto a Factura

Detalle cronológico de las operaciones comerciales de PlasteeCups ejecutadas por los roles correspondientes:

## 1. Creación del Presupuesto
- Usuario responsable: antonio.gomez@plasteecups.test`
- **Referencia del documento:** `S0001`
- **Cliente asociado:** Alejandro Pérez Gómez
- **Detalle de líneas:**
  - 1x Bolsa de Vasos de plástico tamaño Grande 2,30€
  - 1x Casco Inteligente Lumina — 89,99 € (con **10% de descuento** aplicado)
  - 1x Candado U-Lock Antirrobo Pro — 54,99 €
- **Condiciones:** Plazo de pago a 30 días / Validez de 15 días.
- **Estado inicial:** Presupuesto enviado (`Quotation Sent`).
- **Evidencia adjunta:** `venta/presupuesto.pdf`

## 2. Confirmación del Pedido de Venta
- **Usuario responsable:** `ventas@ecobikestudio.test` (Responsable de Ventas)
- **Referencia del documento:** `S00012`
- **Acción:** Conversión de presupuesto a pedido firme.
- **Estado:** Pedido de Venta Confirmado (`Sales Order`).

## 3. Validación de Salida en Inventario
- **Usuario responsable:** `ventas@ecobikestudio.test` (Gestión de Almacén)
- **Referencia de la orden de entrega:** `WH/OUT/00015`
- **Acción:** Validación de cantidades (Hechas = Pedidas) y control de salida de stock físico.
- **Estado:** Hecho / Entregado (`Done`).

## 4. Facturación y Registro de Cobro
- **Usuario responsable:** `admin@ecobikestudio.test` (Administración / Facturación)
- **Referencia de factura:** `INV/2026/00008`
- **Acción:** Creación de factura desde pedido, publicación formal y registro manual del cobro por transferencia.
- **Estado final:** Publicada y **Pagada** (`Paid`).
- **Evidencia adjunta:** `venta/factura.pdf`