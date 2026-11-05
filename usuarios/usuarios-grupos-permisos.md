# Gestión de Usuarios, Grupos y Privilegios

## 1. Matriz de Usuarios y Roles

| Usuario | Puesto en la Empresa | Tipo de Usuario | Módulos Acceso | Justificación de Privilegios |
| :--- | :--- | :--- | :--- | :--- |
| antonio.@plasteeCups.test | Comercial Junior | Interno | Ventas, Contactos | Solo gestiona sus presupuestos y clientes asignados mediante el grupo personalizado. Sin acceso a contabilidad. |
| ventas@plasteecups.test | Responsable de Ventas | Interno | Ventas, Inventario | Supervisa presupuestos del equipo, confirma pedidos y valida salidas de stock en almacén. |
| admin@plasteecups.test | Administración y Facturación | Interno | Facturación, Contabilidad | Gestiona facturas de clientes y registro de pagos, sin permisos de creación de presupuestos comerciales. |
| alejandro.perez@cliente.test | Cliente Particular | Portal | Portal web de cliente | Visualización exclusiva de sus propios documentos aprobados vía acceso web seguro. |

## 2. Detalle del Grupo Propio Creado
- Nombre del Grupo: PlasteeCups/Comercial Junior Avanzado / Comercial Junior Avanzado
- **Herencia:** Hereda de Ventas /
 Usuario: solo mostrar documentos propios.
- **Derechos de Acceso sobre Modelos:**
  - sale.order: Lectura, Escritura, Creación .
  - res.partner: Lectura, Escritura, Creación , Eliminación.