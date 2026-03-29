# 🏦 Módulo de Tesorería: Gestión Financiera Integral

> 💰 El **Módulo de Tesorería** centraliza y administra todo el flujo de dinero de la empresa en sus distintas modalidades, interactuando como el núcleo financiero integrado al resto de los procesos del sistema.

## 🔑 Conceptos Clave

* 💵 **Gestión de Valores**: El sistema permite registrar y controlar de manera transversal todos los activos financieros del negocio, contemplando representaciones como: dinero en efectivo, transacciones en cuentas bancarias, cupones de tarjetas y administración de cheques.
* 🔗 **Integración Inter-Módulos Automática**: Tesorería funciona interconectada en tiempo real. Por ejemplo, al asentar un cobro en el **Módulo de Ventas**, el capital se incrementa instantáneamente; a la inversa, al concretar un desembolso en el **Módulo de Compras / Proveedores**, los fondos correspondientes disminuyen sin necesidad de realizar un asiento manual extra.
* ⚡ **Modelos de Ingreso de Comprobantes**: Funcionalidad que permite dejar estructurados y predefinidos plantillas o "modelos" de datos fijos. Esto dinamiza los tiempos a la hora de realizar la carga repetitiva de la operatoria diaria.
* 📲 **Tango Banking**: Ecosistema dentro de Tango capaz de conectarse vía interbanking para auditar y gestionar operaciones bancarias con la mayor de las fluidez.
* 💳 **Integración con Terminales POS**: Capacidad del sistema para enlazar terminales de pago electrónico inteligente (ej. *Payway*, *Clover*, etc.) de forma nativa.

## 🛣️ Procedimientos de Auditoría

### 1. Conciliación Bancaria Masiva
Uno de los mayores desafíos es regularizar desfases de origen y acreditación (por ejemplo, entre que se emite un cheque y el momento en donde realmente impacta en el banco). El sistema soluciona esto en 3 pasos:
1. Exportar el *extracto bancario* emitido oficialmente por la plataforma financiera.
2. Cargar de forma directa la respectiva planilla o archivo descargado en Tango.
3. El sistema analizará, recalculará y realizará un **"match masivo"**, empatando de manera lógica los movimientos preexistentes con la información validada por el banco, actualizando y auditando los saldos finales.

### 2. Cierre de Lotes y Cupones
Las transacciones realizadas mediante tarjeta de crédito o débito pasan por un circuito específico:
1. Los ingresos son procesados individualmente mediante la integración con los diferentes terminales físicos (POS).
2. Se ejecuta el proceso de **"Cierre de Lote"**.
3. El sistema ejecuta una **conciliación automática y directa** que transfiere formalmente la representatividad de ese "cupón" hacia un ingreso real estructurado en la cuenta bancaria designada.

> **💡 Tip de Eficiencia:** 
> Utilizar la función de los **Modelos de Ingreso de Comprobantes** no solo agiliza el trabajo manual al evitarte teclear datos que se repiten siempre, sino que sirve como una barrera extra para evitar errores de tipeo o distracción durante operaciones altamente sensibles donde ingresa plata en efectivo a la caja general.