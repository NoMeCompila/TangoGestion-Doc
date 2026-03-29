# 📚 TangoGestion-Doc

Bienvenido al repositorio **TangoGestion-Doc**. Este proyecto tiene como objetivo centralizar, estructurar y mantener documentación formal sobre la suite de módulos y utilidades de **Tango Software**.

La particularidad arquitectónica de este repositorio es que toda su documentación ha sido estandarizada a través de Inteligencia Artificial (Antigravity), guiada específicamente mediante una **Habilidad (Skill)** a medida para esta causa.

---

## 🤖 Sobre el Agente y su Skill: "Documentador de Tango Software"

Dentro de este proyecto se encuentra alojada la inteligencia del agente configurada a través del sistema de habilidades de Antigravity.

* **Directorio Principal:** `.agents/skills/documentador-tango/SKILL.md`
* **Misión Fundamental:** El agente actúa como redactor técnico especializado. Está diseñado para ingerir texto no estructurado (apuntes rápidos, anotaciones de clases, lluvia de ideas u oraciones inconexas) referidos a procesos del ecosistema de Tango, para luego procesarlos y escupirlos debidamente jerarquizados con lenguaje profesional.
* **Componente de Estilo:** Aplica una convención de Markdown estricta usando viñetas, alertas y emojis semánticos. El texto que devuelve este agente siempre está preparado para hacer un *"copiar y pegar"* limpio e indoloro hacia plataformas documentales y bases de conocimientos externas como **Notion** o repositorios de **GitHub**.

---

## 🛠️ Tutorial: ¿Cómo utilizar esta Skill?

Si tienes a **Antigravity** corriendo en este mismo entorno y directorio local, utilizar el *"Documentador de Tango"* es muy rápido.

### Paso 1: Prepara tus Notas
Copia cualquier bloque de texto en crudo, incluso si tiene errores de redacción, oraciones cortadas o falta de ortografía.

### Paso 2: Invoca al Agente en el Chat
Escribe el comando directo en tu panel o chat pidiendo explícitamente el uso de la *skill*. Utiliza el siguiente formato de instrucción (Prompt):

> "Usa la habilidad Documentador de Tango Software en el siguiente texto: 
> *[ Pega aquí todos tus apuntes ]*"

### Paso 3: Guarda el Archivo
El agente limpiará la gramática, estructurará el paso a paso, detectará los módulos y te responderá **únicamente** con el bloque Markdown terminado. Cópialo y añádelo a la carpeta del repositorio correspondiente (ej: `Módulos/`, `Características/`, etc.).

---

## 📝 Ejemplo de Uso Práctico

A continuación se demuestra la capacidad real de interpretación de la *Skill* partiendo de apuntes de muy baja calidad redaccional hacia un texto académico.

### 📥 1. Notas Proporcionadas (Input del Usuario)
```text
módulo de tesorería
se gestiona toda la plata de la empresa
varias representaciones: efectivo, cupones d tarj, cheques, plata en cuentas bancarias
todos los movimientos de dinero se registran en modulo tesorería y se relaciona con el modulo de integración, por ejemplo si se hace una cobranza en el módulo de ventas, eso se refleja en modulo tesorería se va a incrementar el capital
conciliacion automática desde cuentas y cheques: porque se pueden producir desfases, Cada banco te permite exportar un extracto luego cargarlo en tango y los match masivamente.
```

### 📤 2. Resultado Procesado (Output del Agente)
```markdown
# 🏦 Módulo de Tesorería: Gestión Financiera Integral

> 💰 El **Módulo de Tesorería** centraliza y administra todo el flujo de dinero de la empresa en sus distintas modalidades, interactuando como el núcleo financiero.

## 🔑 Conceptos Clave

* 💵 **Gestión de Valores**: El sistema permite registrar y controlar de manera transversal todos los activos financieros: dinero en efectivo, cupones de tarjetas, cheques y saldo bancario.
* 🔗 **Integración Inter-Módulos**: Funciona interconectada en tiempo real. Por ejemplo, al asentar un cobro en el **Módulo de Ventas**, el capital se incrementa instantáneamente sin requerir recarga manual.

## 🛣️ Procedimientos y Auditoría

### Conciliación Bancaria Masiva
El sistema soluciona los desfases regulares de acreditación mediante 3 pasos operativos:
1. Exportar el *extracto bancario* emitido oficialmente por tu entidad bancaria.
2. Cargar directamente en Tango la respectiva planilla o archivo descargado.
3. El sistema realizará un **"match masivo"**, empatando de manera lógica los movimientos preexistentes con la información del extracto.
```
