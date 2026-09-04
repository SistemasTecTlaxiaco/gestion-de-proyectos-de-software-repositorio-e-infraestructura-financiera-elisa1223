# FINANCIAMIENTO — Stellar Community Fund y Drips

## 1. Proyecto

**Plataforma comunitaria para la preservación y transmisión de la lengua materna de Santa María Cuquila**

**Asignatura:** Gestión de Proyectos de Software  
**Competencia:** 1  
**Fecha de consulta:** 31 de agosto de 2026

---

## 2. Stellar Community Fund (SCF)

El Stellar Community Fund (SCF) es un programa del ecosistema Stellar que proporciona financiamiento a proyectos que desarrollan soluciones relacionadas con la red Stellar.

Para el SCF Build Award se contemplan apoyos de hasta **150,000 USD equivalentes en XLM**, sujetos a las condiciones de la convocatoria.

### Requisitos y criterios considerados

Entre los principales aspectos de evaluación se encuentran:

- Product Market Fit.
- Criterios específicos del track.
- Calidad de la propuesta.
- Uso de Stellar.
- Plan de integración.
- Preparación para construir.
- Presupuesto y tramos de financiamiento.

El proyecto debe explicar claramente el problema que busca resolver, demostrar que existe una necesidad y presentar una propuesta técnicamente viable.

### Aplicación al proyecto


Nuestro proyecto busca preservar y transmitir la lengua materna de Santa María Cuquila mediante una plataforma comunitaria para consultar palabras, expresiones, pronunciaciones y conocimiento cultural. A si también enseñarle a las nuevas generaciones sobre esta lengua y buscar su preservación mediante este mecanismo.

Una posible integración futura con Stellar podría utilizarse para mecanismos transparentes de apoyo y financiamiento del proyecto.

Actualmente el proyecto todavía se encuentra en una etapa de planificación y desarrollo, por lo que no afirmamos contar con financiamiento aprobado.

**Fuente oficial:**  
https://communityfund.stellar.org/awards

**Fecha de consulta:** 31 de agosto de 2026.

---

## 3. Drips Protocol

Drips es un protocolo basado en Ethereum y redes compatibles con EVM que permite proporcionar financiamiento continuo a proyectos de código abierto.

A diferencia de una transferencia única, un **stream** permite distribuir fondos progresivamente durante un periodo determinado.

### ¿Cómo funciona?

El usuario configura un flujo de fondos hacia un receptor o proyecto. El protocolo registra la configuración y permite que el receptor reclame los fondos disponibles.

También pueden configurarse mecanismos de distribución hacia diferentes destinatarios.

### ¿Qué necesita un proyecto?

Para reclamar un proyecto de código abierto mediante Drips se requiere:

1. Un repositorio de código abierto.
2. Realizar el proceso de reclamación.
3. Una dirección compatible con Ethereum.
4. Verificar la propiedad del repositorio.
5. Configurar el archivo FUNDING.json cuando corresponda.
6. Contar con ETH para cubrir las operaciones que requieran gas.

Cuando participan varias personas, puede utilizarse una wallet multisig para administrar los fondos.

### Límites y condiciones

Drips no entrega fondos automáticamente. Es necesario configurar y verificar el proyecto.

También deben considerarse:

- Costos de gas.
- Verificación de propiedad del repositorio.
- Configuración correcta de los receptores.
- Administración de las direcciones.
- Compatibilidad con Ethereum/EVM.
- Una Drip List puede manejar hasta 200 receptores.

Drips y Stellar son tecnologías diferentes: Drips utiliza infraestructura Ethereum/EVM, mientras que Stellar utiliza su propia red.

**Fuentes oficiales:**

https://docs.drips.network/

https://docs.drips.network/get-support/claim-your-repository/

https://docs.drips.network/the-protocol/advanced/drips-inner-workings/

**Fecha de consulta:** 31 de agosto de 2026.

---

## 4. Fuentes primarias

### Stellar Development Foundation

Stellar Development Foundation. (2026). *Stellar Community Fund — Build Awards.*

https://communityfund.stellar.org/awards

### Stellar Development Foundation

Stellar Development Foundation. (2026). *Stellar Community Fund.*

https://communityfund.stellar.org/

### Drips Network

Drips Network. (2026). *Drips Documentation.*

https://docs.drips.network/

### Drips Network

Drips Network. (2026). *Claim your open-source project.*

https://docs.drips.network/get-support/claim-your-repository/

### Drips Network

Drips Network. (2026). *Drips inner workings.*

https://docs.drips.network/the-protocol/advanced/drips-inner-workings/

Las fuentes de Stellar y Drips fueron consultadas directamente en inglés y posteriormente explicadas con palabras propias.

---

## 5. Backlog por fases y financiamiento

La problemática seleccionada por el equipo es:

**PROB-01 — Preservación y transmisión de la lengua y memoria cultural de Santa María Cuquila**

Estado actual:

**Elegida**

| Fase | Actividades | Posible financiamiento |
|---|---|---|
| Inicio | Constitución del equipo | Recursos propios / académico |
| Planificación | Acuerdo, repositorio, investigación, HU-01 y HU-02 | Recursos propios / preparación de propuesta |
| Ejecución | Desarrollo de HU-03 y HU-04 | Posible primer tramo SCF |
| Seguimiento | Auditoría, concordancia del mapa, HU-05 y HU-06 | Posibles tramos posteriores |
| Cierre | Publicación y mantenimiento | SCF / Drips / otras fuentes |

### Posibles tramos

**Tramo 1 — MVP**

- Plataforma funcional.
- Consulta de palabras y expresiones.
- Pronunciaciones.
- Organización de contenidos.
- Primera validación con usuarios.

**Tramo 2 — Integración y pruebas**

- Evaluar una integración con Stellar.
- Crear un prototipo si realmente aporta valor.
- Realizar pruebas técnicas.

**Tramo 3 — Operación**

- Publicación estable.
- Mantenimiento.
- Crecimiento del contenido.
- Seguimiento de usuarios.

La asignación anterior es una propuesta del equipo y no significa que el SCF haya aprobado dichos tramos para este proyecto.

---

## 5.1 Historias de usuario priorizadas

A partir del backlog definido para el proyecto, se establecen las siguientes historias de usuario con el propósito de identificar las principales necesidades de los usuarios y establecer un orden de prioridad para el desarrollo del sistema.

| ID | Historia de usuario | Prioridad | Fase |
|---|---|---|---|
| HU-01 | Como usuario quiero consultar palabras de la lengua materna para conocer su significado. | Alta | Planificación |
| HU-02 | Como usuario quiero escuchar la pronunciación de las palabras para aprender a pronunciarlas correctamente. | Alta | Planificación |
| HU-03 | Como usuario quiero consultar expresiones de Santa María Cuquila para conocer su uso y significado. | Alta | Ejecución |
| HU-04 | Como usuario quiero consultar información cultural relacionada con las palabras para conocer su contexto. | Media | Ejecución |
| HU-05 | Como administrador quiero agregar y actualizar palabras para mantener disponible el contenido de la plataforma. | Alta | Seguimiento |
| HU-06 | Como administrador quiero revisar y validar el contenido antes de publicarlo para mantener la calidad de la información. | Media | Seguimiento |

### Criterio de priorización

Las historias de usuario fueron priorizadas considerando su importancia para la construcción del Producto Mínimo Viable (MVP). Las funciones relacionadas con la consulta de palabras y la pronunciación tienen una prioridad alta debido a que representan las funciones principales de la plataforma.

Las funciones relacionadas con la consulta de expresiones e información cultural se consideran necesarias para complementar el contenido y proporcionar un contexto adecuado al usuario. Finalmente, las funciones administrativas de actualización y validación permiten mantener la calidad y disponibilidad de la información conforme el proyecto crezca.

La priorización permite organizar el desarrollo de manera gradual, comenzando por las funcionalidades esenciales y posteriormente incorporando características complementarias y administrativas.

## 6. Hueco honesto

Actualmente el proyecto **NO cumple todavía todos los requisitos técnicos necesarios para presentarse como un proyecto listo para recibir financiamiento on-chain**.

### Requisitos pendientes

- MVP funcional terminado.
- Integración implementada con Stellar.
- Pruebas sobre Stellar/Soroban.
- Wallet del proyecto.
- Repositorio reclamado en Drips.
- Configuración de FUNDING.json.
- Evidencia suficiente de usuarios.
- Presupuesto definitivo.
- Plan técnico definitivo de blockchain.

Por lo tanto, el equipo no afirma ser beneficiario del Stellar Community Fund ni de Drips.

### Plan para cerrar las brechas

| Pendiente | Acción | Fecha estimada |
|---|---|---|
| MVP | Desarrollar y probar la primera versión | Octubre 2026 |
| Validación | Realizar pruebas con usuarios | Octubre–Noviembre 2026 |
| Stellar | Investigar y desarrollar prototipo | Noviembre 2026 |
| Wallet | Definir responsable y administración | Noviembre 2026 |
| Drips | Analizar reclamación del repositorio | Noviembre 2026 |
| Presupuesto | Elaborar costos y entregables | Noviembre 2026 |
| Postulación | Evaluar convocatoria disponible | Después de validar el MVP |

---

## 7. Conclusión

La investigación permitió identificar dos mecanismos diferentes de financiamiento y apoyo para proyectos de código abierto.

El Stellar Community Fund puede apoyar proyectos relacionados con Stellar que cumplan sus criterios de evaluación y presenten avances verificables.

Drips permite establecer flujos de financiamiento continuo para proyectos de código abierto mediante infraestructura Ethereum/EVM.

Para nuestro proyecto, primero es necesario desarrollar y validar el MVP. Después se podrá determinar si una integración con Stellar o Drips realmente aporta valor.

El equipo identifica de manera explícita las brechas actuales y establece acciones para cerrarlas antes de considerar una solicitud formal de financiamiento.

---

## Bibliografía

1. Stellar Development Foundation. (2026). *Stellar Community Fund — Build Awards.*  
   https://communityfund.stellar.org/awards

2. Stellar Development Foundation. (2026). *Stellar Community Fund.*  
   https://communityfund.stellar.org/

3. Drips Network. (2026). *Drips Documentation.*  
   https://docs.drips.network/

4. Drips Network. (2026). *Claim your open-source project.*  
   https://docs.drips.network/get-support/claim-your-repository/

5. Drips Network. (2026). *Drips inner workings.*  
   https://docs.drips.network/the-protocol/advanced/drips-inner-workings/
