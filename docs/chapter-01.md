# Capítulo I: Introducción

---
## 1.1. Startup Profile

---

### 1.1.1. Descripción de la Startup

**VET-Smart** es una *startup* tecnológica enfocada en la optimización operativa y financiera del sector veterinario. Nuestro producto principal, **VetCare**, es una plataforma integral de gestión empresarial (ERP) y clínica (EHR) diseñada para centralizar y automatizar las operaciones de centros veterinarios modernos. El ecosistema permite a los **médicos veterinarios** gestionar historiales clínicos, citas y el control de inventario en tiempo real, mientras proporciona a los **administradores** herramientas avanzadas de inteligencia de negocios, control de flujos de caja y procesamiento de pagos integrados para maximizar la rentabilidad de la clínica.

| Atributo | Declaración Estratégica |
| :--- | :--- |
| **Misión** | Impulsar la eficiencia de las clínicas veterinarias mediante una plataforma integral que unifique la gestión clínica, administrativa y financiera, permitiendo a los profesionales enfocarse en la salud animal mientras aseguran la sostenibilidad y el crecimiento de su negocio. |
| **Visión** | Consolidarse como el estándar tecnológico en la gestión de centros veterinarios a nivel regional, transformando clínicas tradicionales en empresas digitales, rentables y centradas en la excelencia del servicio médico. |

#### Valor Agregado de la Plataforma:
* **Gestión Clínica Operativa:** Registro ágil de pacientes, consultas y procedimientos médicos.
* **Control de Inventario Inteligente:** Descuento automático de insumos y productos tras cada cita médica.
* **Administración Financiera:** Seguimiento detallado de ingresos y egresos con reportes visuales (dashboards) para la toma de decisiones.
* **Pasarela de Pagos Integrada:** Gestión de transacciones directamente desde la plataforma para facilitar el flujo de caja.

### 1.1.2. Perfiles de integrantes del equipo

| Nombre y Apellido | Nuñez Soto, Andy Arturo - U20231E795 |
| :--- | :--- |
| **Descripción** | Especialista en el control de calidad, testing y despliegue del producto final. Se encarga de supervisar que el código cumpla con las convenciones establecidas por el equipo para el correcto funcionamiento de VetCare en todos sus entornos. |
| **Foto** | _(Pendiente)_ |

<br>

| Nombre y Apellido | Roman Zevallos, Sebastian Jared - U202419009 |
| :--- | :--- |
| **Descripción** | Especialista en el modelado, manejo y estructuración de la información. Su labor consiste en diseñar el esquema de persistencia de datos y apoyar en el desarrollo de los servicios internos, garantizando que los registros se almacenen de forma segura y eficiente. |
| **Foto** | <img src="../assets/member_Zevallos_Sebastian.png" alt="Foto Sebastian" width="150" /> |

<br>

| Nombre y Apellido | Romero Vilela, Dario Alberto - U202419286 |
| :--- | :--- |
| **Descripción** | Desarrollador Back-End centrado en la implementación de la lógica de negocios y la integración entre los sistemas del lado del servidor. Es responsable de construir y documentar las APIs que nutren de información a toda la plataforma clínica. |
| **Foto** | <img src="../assets/member_Romero_Dario.png" alt="Foto Dario" width="150" /> |

<br>

| Nombre y Apellido | Sanchez Benavente, Leonardo Matias - U20241B184 |
| :--- | :--- |
| **Descripción** | Lidera la construcción de la interfaz interactiva (Front-End) de VetCare. Su misión es transformar los diseños visuales de la aplicación en pantallas y componentes completamente funcionales, asegurando un rendimiento fluido y una comunicación estable. |
| **Foto** | <img src="../assets/member_Sanchez_Leonardo.jpg" alt="Foto Leonardo" width="150" /> |

<br>

| Nombre y Apellido | Sejuro Medina, Mario Gabriel - U20241C198 |
| :--- | :--- |
| **Descripción** | Responsable de conceptualizar y construir la experiencia visual y de usuario (UI/UX) de la plataforma VetCare. Su principal objetivo es asegurar que la aplicación sea intuitiva, atractiva y que cumpla con los estándares de accesibilidad para todo tipo de usuarios. |
| **Foto** | <img src="../assets/member_Sejuro_Mario.png" alt="Foto Mario" width="150" /> |

## 1.2. Solution Profile

**VetCare** es una plataforma integral de gestión empresarial (ERP) y clínica (EHR) diseñada para centralizar la operativa de los centros veterinarios. Nuestra solución elimina la fragmentación administrativa al unificar en un solo ecosistema el historial clínico digital, la gestión de citas, el control de inventarios con descuento automático y la administración financiera avanzada. Al proporcionar dashboards de inteligencia de negocios y pasarelas de pago integradas, VetCare permite que los administradores tomen decisiones basadas en datos reales para maximizar la rentabilidad, mientras los médicos optimizan su tiempo mediante procesos clínicos automatizados.

### 1.2.1. Antecedentes y Problemática

En el sector veterinario actual, la mayoría de los centros operan con sistemas desconectados o procesos manuales que generan ineficiencias críticas. La falta de integración entre el área médica y el área financiera provoca fugas de capital, errores en el stock de insumos y una visión incompleta de la salud financiera del negocio. Según Digitalization of Veterinary Practice Management (2025), las clínicas que no automatizan su flujo administrativo pierden una parte significativa de su capacidad operativa debido a la duplicidad de tareas.

Al analizar esta situación con la metodología de las **5 W’s y 2 H’s** se identifican los siguientes elementos:

**Who (Quiénes)**
Principalmente **administradores de clínicas veterinarias** que necesitan control total sobre el flujo de caja y la rentabilidad, y **médicos veterinarios** que requieren una herramienta ágil para gestionar historiales clínicos sin complicaciones administrativas.

**What (Qué)**
La problemática radica en la **fragmentación de la información operativa**. Las veterinarias carecen de una plataforma única que conecte lo que sucede en el consultorio (consumo de insumos) con la contabilidad y el almacén, dificultando la gestión del inventario y el control de ingresos reales.

**When (Cuándo)**
El desafío es constante en el flujo de trabajo diario, desde la programación hasta el cobro. Según Operational Efficiency in Health Facilities (2026), la ineficiencia se agudiza al no contar con sistemas que sincronicen el uso de materiales con el registro financiero en tiempo real.

**Where (Dónde)**
En la **infraestructura operativa de las clínicas veterinarias** urbanas. El problema se localiza en el "back-office" del negocio, donde la falta de herramientas de inteligencia de negocios (BI) impide una toma de decisiones estratégica.

**Why (Por qué)**
Las causas principales son:
* **Sistemas aislados:** Uso de herramientas manuales para inventarios que no se comunican con el historial médico.
* **Fugas de inventario:** Falta de un sistema que descuente automáticamente los insumos utilizados en cada cita médica.
* **Carencia de analítica:** Los administradores no cuentan con reportes visuales en tiempo real para identificar la rentabilidad real de sus servicios.

**How (Cómo)**
Se manifiesta en una administración reactiva, pérdida de stock, procesos de pago lentos y una carga administrativa excesiva. Según Digitalization of Veterinary Practice Management (2025), esto reduce drásticamente el tiempo que el profesional dedica a la atención médica efectiva.

**How Much (Cuánto)**
* La automatización de flujos administrativos reduce la carga de trabajo manual en un **40%**, según Digitalization of Veterinary Practice Management (2025).
* La implementación de sistemas integrados presenta una correlación de **$r = 0.703$** con la mejora de la eficiencia operativa, según Operational Efficiency in Health Facilities (2026).
* El uso de inteligencia de negocios y reportes financieros automáticos puede incrementar la retención de clientes y la salud financiera en un **86%**, según The Impact of Business Intelligence (2025).
### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

---

El mercado peruano exige la modernización de los servicios de salud animal. Según CPI (2023), la mayoría de hogares urbanos tiene mascotas, elevando la demanda veterinaria. Sin embargo, gremios como la Cámara de Comercio de Lima (2022) advierten que, pese a la apertura de más clínicas, persisten desafíos de gestión y falta de digitalización que limitan su eficiencia y rentabilidad.

Dentro de este panorama, VET-Smart concentrará su fase inicial en dos segmentos clave:

* **Médicos veterinarios en clínicas de mediano a alto flujo** que carecen de herramientas integradas. La gestión manual de historiales e inventarios consume un tiempo crítico. Ante la alta demanda, requieren una plataforma clínica (EHR) en tiempo real para optimizar consultas, controlar medicamentos y mejorar la atención al paciente, reduciendo su dependencia de procesos analógicos.

* **Administradores de centros veterinarios**, usualmente entre 30 y 55 años, enfocados en la eficiencia operativa y financiera. La plataforma (ERP) les brindará herramientas de inteligencia de negocios, control de flujo de caja y pagos integrados mediante reportes claros, facilitando decisiones para maximizar la rentabilidad.

Esta selección prioriza usuarios con una necesidad crítica de optimización y mayor disposición tecnológica. Esto permitirá una implementación ágil y generará evidencia de impacto para, en el futuro, expandirse hacia otros segmentos del mercado del cuidado animal.
