# 🛒 Módulo de Compras: Registro y Gestión de Proveedores

> 📝 El **Módulo de Compras** centraliza la relación comercial con proveedores, automatizando el registro de comprobantes, la actualización de precios, la homologación de inventario y la emisión estructurada de pagos.

## 🔑 Conceptos Clave

* 🧾 **Gestión de Comprobantes**: Permite registrar y administrar eficientemente todas las facturas, notas de crédito y notas de débito emitidas por los proveedores de la empresa.
* 📊 **Precios por Proveedor**: Capacidad del sistema para administrar listas de precios diferenciales por cada proveedor. Permite importar y actualizar masivamente estos valores utilizando planillas de **Excel**.
* 🤝 **Homologación de Artículos (Sinónimos)**: Funcionalidad que resuelve discrepancias de codificación vinculando el "ID" o código que utiliza el proveedor (ej. `Art X`) con la codificación interna que usa nuestro negocio en Tango Software (ej. `Art Y`).
* 📱 **Tango Colectora**: Aplicación móvil complementaria que habilita el registro de comprobantes de forma descentralizada, como cargar un *Remito de Compras* desde la zona de recepción.
* 🛡️ **Gestión de Autorizaciones**: Esquema de seguridad financiera que somete la emisión de pagos a un proceso de aprobación. Habilita configurar distintos *niveles de autorización* basados en rangos de importe.
* 💸 **Retenciones Impositivas**: Capacidad del sistema para automatizar el cálculo de retenciones (ej. ARBA) durante el proceso formal de emisión de pagos.

## 🛣️ Flujos y Procedimientos

### 📍 Puntos de Inicio para el Registro de Compras
El circuito de compras es flexible y puede iniciarse desde tres instancias documentales diferentes:
1. 📦 **Desde la Orden de Compra**: Se envía el pedido formal. Una vez que el proveedor envía la mercadería, se registra la recepción impactando en el circuito de compras.
2. 🚚 **Desde el Remito**: Se inicia el registro en el sistema al recibir físicamente la mercadería mediante el documento de remito.
3. 🧾 **Desde la Factura**: Se carga en el sistema directamente la factura emitida por el proveedor de forma aislada.

### 💳 Circuito de Emisión de Pagos de Cuentas Corrientes
1. Se estructura la orden en el módulo de Cuentas Corrientes.
2. El pago debe atravesar obligatoriamente la regla de **Autorización** (según cruce de usuario e importe).
3. El sistema aplica automáticamente el **cálculo de retenciones** correspondientes.
4. Se ejecuta el pago, el cual puede realizarse de forma individual, o mediante un **pago masivo y programado** (por ejemplo, seleccionando todas las facturas a pagar con vencimiento a cierta fecha futura).
5. Todos los movimientos registran la información contable correspondiente de manera automática con cada movimiento que se hace mediante tango software.

> **💡 Tip de Organización:** 
> Utilizar la función de **Sinónimos para Homologar Artículos** es fundamental. Evita alterar toda la matriz de códigos internos de nuestra empresa cada vez que integramos un proveedor nuevo que utiliza su propio catálogo.