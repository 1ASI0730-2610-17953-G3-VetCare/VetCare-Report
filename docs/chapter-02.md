# Capítulo II: Requirements Elicitation & Analysis

---

## 2.1. Competidores

---

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

---

### 2.2.1. Diseño de entrevistas

#### Segmento 1: Médico Veterinario
1. En tu día a día, ¿qué tareas administrativas sientes que te quitan más tiempo de la atención a las mascotas? 
2. Cuando atiendes a un paciente, ¿cómo registras actualmente la información médica? 
3. ¿Te ha pasado que pierdes información o no encuentras rápidamente el historial de una mascota? ¿Cómo lo solucionas? 
4. ¿Cuánto tiempo dirías que dedicas a llenar datos o registros después de cada consulta? 
5. ¿Qué tan fácil o difícil es para ti gestionar las citas y organizar tu agenda diaria? 
6. Cuando tienes varios pacientes al mismo tiempo, ¿qué es lo más complicado de manejar? 
7. ¿Te ha ocurrido olvidar algún detalle importante como medicación, vacuna o seguimiento? ¿Por qué crees que pasa? 
8. ¿Qué herramientas o sistemas usas actualmente? ¿Qué es lo que más te frustra de ellos? 
9. Si pudieras eliminar o mejorar una parte de tu trabajo administrativo, ¿cuál sería y por qué? 
10. ¿Cómo te gustaría que un sistema ideal te ayude durante una consulta para que sea más rápida y ordenada? 

#### Segmento 2: Administrador / Propietario de Veterinaria
1. ¿Cómo gestionas actualmente los ingresos, gastos y pagos dentro de tu clínica? 
2. ¿Te resulta fácil saber cuánto estás ganando realmente al final del mes? ¿Por qué? 
3. ¿Qué problemas has tenido con el control de pagos o facturación? 
4. ¿Te ha pasado que se te escapan cobros o servicios no registrados? ¿Con qué frecuencia? 
5. ¿Cómo controlas el inventario de medicamentos y productos? ¿Es un proceso confiable? 
6. ¿Cuánto tiempo dedicas a tareas administrativas en comparación con la gestión del negocio? 
7. ¿Qué tan difícil es obtener reportes claros sobre el rendimiento de tu clínica? 
8. ¿Qué herramientas utilizas actualmente y qué limitaciones encuentras en ellas? 
9. ¿Qué impacto crees que tiene la desorganización administrativa en tus ingresos? 
10. Si pudieras automatizar una parte del negocio hoy, ¿cuál sería y qué beneficio esperas obtener?

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

---

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

## 2.4. Big Picture EventStorming

---

## 2.5. Ubiquitous Language

---

#### 1. Core Domain (Conceptos Generales del Negocio)
* **Clinic (Clínica):** El establecimiento físico o centro veterinario donde se brindan los servicios médicos, estéticos y administrativos para los animales.
* **Pet Owner (Propietario / Cliente):** La persona física responsable legal y financieramente del animal, quien solicita y autoriza los servicios de la clínica.
* **Patient (Paciente):** El animal que recibe la atención médica o los servicios dentro del establecimiento veterinario.
* **Veterinarian (Médico Veterinario):** El profesional colegiado de la salud animal encargado de evaluar, diagnosticar, tratar y prescribir medicamentos a los pacientes.
* **Staff (Personal):** Empleados de la clínica que no realizan actos médicos, encargados de la recepción, asistencia administrativa o mantenimiento.

#### 2. Clinical Module (Módulo Clínico - EHR)
* **Electronic Health Record (Historial Clínico):** Documento digital unificado e inmutable que centraliza toda la información de salud de un paciente a lo largo del tiempo, incluyendo alergias, vacunas, peso y atenciones previas.
* **Triage (Triaje):** Evaluación inicial de los signos vitales (peso, temperatura, frecuencia cardíaca) y el motivo de consulta del paciente para determinar el nivel de urgencia antes de la atención médica.
* **Consultation (Consulta Médica):** El acto médico principal en el que el veterinario examina al paciente, emite un diagnóstico y establece un plan de tratamiento.
* **Diagnosis (Diagnóstico):** La conclusión clínica oficial sobre la patología, enfermedad o condición que padece el paciente, determinada por el veterinario.
* **Medical Exam (Examen Médico):** Pruebas complementarias de laboratorio o diagnóstico por imágenes (radiografías, ecografías, análisis de sangre) solicitadas para apoyar el diagnóstico clínico.
* **Prescription (Receta Médica):** Indicación terapéutica oficial formulada por el médico veterinario que detalla los medicamentos, dosis, frecuencia y duración del tratamiento que debe seguir el paciente.
* **Vaccination Schedule (Cronograma de Vacunación):** Calendario preventivo programado que indica las fechas en las que el paciente debe recibir sus vacunas y desparasitaciones periódicas.

#### 3. Administrative & Financial Module (Módulo de Gestión - ERP)
* **Appointment (Cita):** Espacio de tiempo específico reservado y confirmado en la agenda de la clínica para que un médico veterinario evalúe a un paciente o se le realice un servicio.
* **Inventory (Inventario):** Catálogo general y registro actualizado de todos los medicamentos, insumos médicos, alimentos y productos de venta disponibles en la clínica.
* **Stock (Existencias):** La cantidad física y real disponible de un producto o medicamento específico dentro de la clínica en un momento determinado.
* **Supplier (Proveedor):** La empresa o entidad comercial externa que abastece a la clínica de medicamentos, equipamiento o productos de venta.
* **Service (Servicio):** Cualquier actividad intangible ofrecida por la clínica que genera un costo, como consultas, cirugías, baños o cortes de pelo.
* **Invoice (Factura / Boleta):** Documento comercial y tributario que detalla los servicios prestados o productos vendidos al propietario del paciente, indicando el monto total a pagar.
* **Payment (Pago):** La transacción económica realizada por el propietario para liquidar la deuda generada por la factura de los servicios o productos adquiridos.
* **Cash Flow (Flujo de Caja):** El registro y monitoreo del movimiento de dinero dentro de la clínica, contabilizando los ingresos por atenciones y los egresos por gastos operativos.
