# 📈 Módulo de Contabilidad: Gestión Patrimonial e Inflacionaria

> 📊 El **Módulo de Contabilidad** centraliza la estructura del modelo contable de la empresa, gestionando el plan de cuentas, los procesos de ajustes monetarios (inflación y divisas) y la emisión de Balances automatizados.

## 🔑 Conceptos Clave

* 🗂️ **Plan de Cuentas Avanzado**: Permite la parametrización de múltiples cuentas analíticas. Se utiliza este diseño multi-nivel para poder segmentar, seguir y analizar el detalle patrimonial exhaustivamente.
* 📝 **Contabilización Diferida**: El sistema soporta la generación de asientos en lotes o en formato diferido (línea a línea), desvinculando, cuando es necesario, el instante de la transacción operativa con el momento puntual del asiento financiero confirmatorio.
* 📈 **Ajuste por Inflación**: Potente motor automático que ejecuta la generación iterativa de los asientos (como el RECPAM) necesarios para que la contabilidad refleje el desgaste del poder adquisitivo o reexpresión de saldos, cumpliendo normativas contables e impositivas.
* 📦 **Resultados por Tenencia (RxT)**: Función integrada para registrar el movimiento y las variaciones directas del valor de aquellos bienes que componen el capital de trabajo (ej. existencias o stock), medidos por el simple paso del tiempo y contexto.
* 💱 **Ajuste por Varianza de Divisas (Diferencia de Cambio)**: Rutina de re-valuación indispensable para organizaciones multimoneda. Calcula la variación que sufren los saldos correspondientes ante movimientos en las distintas cotizaciones del mercado de divisas.
* 📑 **Automatización de Balances**: Proceder final que consolida en un solo panel o reporte el "Estado de Situación Patrimonial", logrando emitir el balance contable final con mínimo esfuerzo manual.

## 🛣️ Flujo de Consolidación de Ejercicio

El proceso general dentro del módulo de Contabilidad para lograr informes transparentes requiere transitar ciertos eventos:
1. El sistema agrupa toda la integración contable que ocurrió en los módulos satélites (Compras, Ventas, Sueldos y Tesorería).
2. Se procesan todas las líneas contables aplicando, en caso de corresponder, la contabilización diferida.
3. Se ejecutan sistemáticamente los cálculos estacionales de **Ajuste por Inflación**, de **Variación en Tenencia**, y de **Diferencias de Divisas**.
4. Se emite el **Balance Contable Automatizado** como foto consolidada de la salud patrimonial e indicadores organizacionales.

> **💡 Tip de Organización:** 
> Un diseño correcto y granular al crear las "Múltiples Cuentas" en tu plan inicial, garantiza que luego la herramienta de "Balance Automatizado" no requiera manipulación externa para presentar un estado de resultados detalladísimo y útil para la alta mesa de toma de decisiones.