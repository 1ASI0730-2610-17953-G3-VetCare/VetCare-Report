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

**VET-SmartDiet** es una plataforma de gestión clínica integral (Practice Management Software - PMS) diseñada para digitalizar y automatizar el control nutricional en centros veterinarios. El ecosistema vincula el diagnóstico médico con una red de dispositivos IoT que actúan como terminales de captura de datos en tiempo real. Al centralizar la información de ingesta y evolución del paciente en una base de datos unificada, la plataforma permite que los administradores optimicen recursos, reduzcan el error humano en el seguimiento post-consulta y generen nuevas líneas de ingresos mediante servicios de monitoreo preventivo de alta precisión.

### 1.2.1. Antecedentes y Problemática

En la actualidad, la gestión de las clínicas veterinarias enfrenta desafíos críticos en la trazabilidad de los tratamientos externos y la eficiencia operativa. Aunque la digitalización de historias clínicas ha avanzado, persiste una "brecha informativa" una vez que el paciente abandona el consultorio, lo que impacta directamente en la rentabilidad del negocio y en la reputación de la clínica.

La gestión veterinaria tradicional depende de reportes subjetivos de los dueños, lo que genera diagnósticos imprecisos y una atención reactiva ante emergencias que podrían haberse detectado proactivamente. Según proyecciones del mercado de software veterinario para el periodo 2025-2026, la falta de integración entre dispositivos médicos y sistemas de gestión reduce la eficiencia del personal en un 40% debido a tareas de seguimiento manual ineficientes.

Al analizar esta situación con la metodología de las **5 W’s y 2 H’s** se identifican los siguientes elementos:

**Who (Quiénes)**
Administradores de clínicas veterinarias que buscan optimizar la rentabilidad y el control de inventarios de alimentos terapéuticos; médicos veterinarios especialistas que requieren datos precisos para validar sus protocolos; y personal técnico que necesita automatizar el flujo de datos para reducir la carga administrativa.

**What (Qué)**
La problemática radica en la carencia de herramientas tecnológicas integradas que capturen telemetría real (consumo, frecuencia, peso) fuera de la clínica. Esto dificulta que el administrador gestione eficientemente el ciclo de vida del paciente y genera una pérdida de ingresos por falta de recurrencia y baja adherencia a los tratamientos prescritos.

**When (Cuándo)**
El desafío es actual y creciente, manifestándose en la operativa diaria y volviéndose crítico durante el seguimiento de patologías crónicas. Investigaciones sobre gestión de instalaciones inteligentes indican que la ventana de intervención oportuna se pierde sin un monitoreo constante, forzando a la clínica a realizar una gestión de crisis en lugar de una atención programada.

**Where (Dónde)**
A nivel operativo, el problema se localiza en la desconexión entre el entorno doméstico del paciente y el sistema central de la clínica. En zonas urbanas con alta densidad de pacientes, la falta de automatización satura la agenda médica con consultas de control que podrían gestionarse de forma remota mediante flujos de datos automatizados.

**Why (Por qué)**
Las causas principales identificadas son:
* **Fragmentación de datos:** Los sistemas actuales son estáticos y no reciben información en tiempo real desde nodos externos.
* **Dependencia del factor humano:** El flujo de datos depende totalmente de la disciplina del cuidador, no de la supervisión médica automatizada.
* **Inexistencia de alertas tempranas:** La administración no cuenta con indicadores de anomalías que permitan anticipar la necesidad de una consulta o reabastecimiento de insumos.

**How (Cómo)**
Se manifiesta en un bajo porcentaje de casos con seguimiento exitoso fuera del consultorio, una gestión ineficiente del tiempo clínico y la ausencia de plataformas que faciliten la analítica predictiva sobre la evolución de los pacientes.

**How Much (Cuánto)**
* Estudios sobre *Smart Veterinary Facilities* (2026) muestran que la eficiencia operativa presenta una correlación positiva fuerte ($r = 0.703$) en centros que adoptan gestión basada en datos e IoT.
* La automatización del flujo de datos externos reduce la carga de trabajo administrativo en un **40%** (*The Role of ICT in Veterinary*, 2025).
* La adopción de tecnologías de monitoreo remoto tiene el potencial de incrementar la retención de clientes en un **86%** al transformar la clínica en un gestor de salud constante y proactivo.

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
