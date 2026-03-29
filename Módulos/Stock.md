Created modulos.md

# Módulo Stock: Funcionalidades Generales

> Introducción al módulo de **Stock** en Tango Software, orientado a la administración integral de bienes, auditorías de inventario y trazabilidad avanzada de artículos.

## Conceptos Clave

* **Gestión de Bienes**: Administración consolidada tanto para "bienes de cambio" y "servicios", como así también para la gestión de "bienes de uso".
* **Movimientos de Inventario**: Capacidad de registrar ingresos y egresos (stock in/out) de manera manual o masiva. Todos estos movimientos pueden estar **valorizados**.
* **Transferencias entre Depósitos**: Movilidad de la mercadería entre diferentes espacios de almacenamiento físico confirmando y registrando el valor exacto de la carga movilizada.
* **Trazabilidad por Serie**: Funciona como un "ID único" utilizado para identificar a un artículo en particular y realizarle un seguimiento o rastreo individualizado.
* **Trazabilidad por Partidas**: Procedimiento para vincular y agrupar un lote de artículos basado en características o atributos productivos comunes.
* **Sistema de Armado (Kits)**: Funcionalidad que permite la fabricación o la estructuración de un producto final que está orgánicamente compuesto por diferentes materias primas o insumos.

## Procedimientos

### Toma y Regularización de Inventario
El sistema permite unificar el stock "físico" y el stock "lógico" mediante los siguientes pasos:
1. Realizar un conteo o relevamiento físico manual del stock en los depósitos.
2. Importar los registros logrados directamente a través de planillas de **Excel** o utilizando la aplicación **Tango Conectora**.
3. Analizar las diferencias y ejecutar los ajustes para actualizar el inventario operativo, saldando posibles desfases por mercadería extraviada durante la operatoria diaria.

### Configuración del Costo Final en Sistemas de Armado
El proceso de armado no solo vincula piezas, sino que concentra valores para obtener el margen real:
1. Definir la "Fórmula" o la receta técnica de qué elementos componen el artículo final. 
2. Asignar los valores directos e indirectos correspondientes al proceso. 
> **💡 Ejemplo Práctico (Computadora):** Si ensamblamos una computadora, además de consolidar las piezas de hardware (CPU, Motherboard, Memoria), se deben cargar los gastos o costos extras por el proceso de *"armado"* o *"mantenimiento"*. Sumando todas estas variables, el **Módulo de Stock** arrojará el Costo Final real del producto terminado.