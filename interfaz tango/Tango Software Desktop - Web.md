# 🖥️ Interfaz de Usuario: Navegación y Estructura en Tango Software

> 🧭 Guía descriptiva sobre la anatomía visual y funcional del entorno de trabajo principal de Tango. Detalla la disposición de sus barras de acceso, paneles laterales de módulos y el centro lógico de operaciones.

## 🔑 Conceptos Clave: Anatomía de la Pantalla Principal

Toda la pantalla principal del sistema está seccionada lógicamente para optimizar los tiempos de trabajo. Se divide en cinco grandes bloques de interacción:

### 1. Barra de Herramientas Superior (Acceso Rápido)
Franja horizontal superior que concentra íconos para acceder a funciones globales sin importar en qué módulo te encuentres parado:
* ⭐ **Mis Favoritos**: Acceso directo y personalizable a los procesos más utilizados por el usuario.
* 📊 **Tablero**: Enlace a la pantalla de indicadores de gestión (KPIs) para vistazos rápidos del negocio.
* ⚡ **Live (`F7`)**: Gatillo rápido para abrir la herramienta de consultas dinámicas y reportes en vivo.
* ☁️ **Menú Web / Nexo**: Puerta de entrada a los servicios en la nube y todas las integraciones digitales desarrolladas por Axoft.
* 🔔 **Notificaciones (`F4`)**: Centro de alertas sobre avisos pendientes o informaciones automáticas del sistema.

### 2. Panel de Módulos (Columna Lateral Izquierda)
Barra vertical que actúa como selector de las "áreas" o departamentos de la empresa. Al hacer clic en cualquiera de ellos, el sistema adapta el menú central a la especialidad elegida:
* **Ventas**: Carga de clientes, facturación y análisis de cuentas corrientes deudoras.
* **Stock**: Configuración de depósitos, artículos y auditoría de inventario.
* **Compras e Importaciones**: Trato con proveedores y carga de órdenes/recepciones.
* **Tesorería**: Administración financiera (cajas, bancos, flujo de fondos y cheques).
* **Contabilidad**: Núcleo de asientos contables rutinarios, libros diarios y balances.
* **Sueldos / Control de Personal**: Espacio para legajos de empleados y liquidación de haberes mensuales.

### 3. Menú de Exploración de Procesos (Panel Central)
Es el "corazón operativo" de la interfaz. Representado habitualmente mediante un árbol de carpetas que se despliega según el Módulo seleccionado a la izquierda:
* 📂 **Archivos**: Zona donde se declaran los datos "maestros" estructurales (ej. Alta de Clientes, porcentajes de Alícuotas de IVA, Condiciones fijas de venta).
* ⚙️ **Operaciones (Ej. Facturación)**: Componentes para ejecutar la rutina diaria administrativa, como la emisión de comprobantes o notas de crédito.
* 📒 **Cuentas Corrientes**: Área destinada a registrar cobranzas y auditar los saldos adeudados.
* 🖨️ **Consultas / Informes**: Herramientas de extracción de información final, como el cruce del Libro de IVA o resúmenes masivos de cuenta.

### 4. Barra de Estado (Franja Inferior)
Pie de página del programa que muestra permanentemente tres variables elementales para evitar errores de carga por confusión de entorno:
* 👤 **Usuario**: Muestra qué operador está activo y verificando el registro (ej. *"Supervisor"*).
* 🏢 **Empresa**: Señala la razón social o Base de Datos en la que se están guardando los movimientos (útil en entornos Multi-Empresa).
* 📅 **Fecha de Trabajo**: Variable determinística esencial, ya que define en qué periodo se imputará contablemente el próximo movimiento a procesar.

### 5. Paneles de Recientes y Favoritos (Ventanas Laterales Ocultables)
Bloques complementarios que se abren a los costados del núcleo central. Muestran el historial de los **últimos procesos operados** o los marcadores configurados como **"Mis Favoritos"**, evitando que el usuario deba buscar manualmente repetidas veces dentro del árbol de carpetas para hacer siempre la misma tarea.

> **💡 Tip de Navegación:** 
> Acostumbrarse a utilizar los atajos de teclado como **Live (`F7`)** y **Notificaciones (`F4`)** agiliza la visualización de datos sin necesidad de levantar las manos del teclado ni usar el ratón para hacer múltiples clics mientras se están procesando datos duros.