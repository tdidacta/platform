# TDidacta Platform

**Plataforma abierta de TDidacta para crear, publicar y explorar experiencias educativas, preservando la intención pedagógica y facilitando distintas formas de enseñanza y aprendizaje.**

## Propósito

TDidacta Platform facilita que las personas creen, compartan y exploren experiencias educativas sin requerir conocimientos técnicos especializados.

No reemplaza a quienes enseñan ni establece una única forma correcta de aprender. Ofrece medios para convertir intenciones pedagógicas en experiencias concretas, preservando la capacidad de revisarlas, adaptarlas y mejorarlas.

Es una realización operacional de [TDidacta](https://github.com/the-alive-lab/tdidacta), no la definición completa del sistema. Las fuentes canónicas conservan la autoridad sobre los conceptos que les pertenecen.

## Compromisos iniciales

### Autoridad pedagógica

Quienes elaboran material educativo conservan la autoridad sobre su contenido. Toda generación asistida requiere autorización previa dentro de los permisos definidos por el docente o responsable. Ninguna propuesta generada modifica o publica automáticamente material aprobado.

Las exploraciones habilitadas y sus límites pedagógicos pueden expresarse mediante los contratos de la fuente educativa. Las respuestas inferidas, dentro o fuera de la aplicación, son **material auxiliar**, no contenido oficial automáticamente. Esto no elimina responsabilidades de privacidad, seguridad y operación.

### Diversidad de realizaciones

Una misma intención pedagógica puede expresarse mediante textos, guías, ejercicios, experiencias interactivas y otros formatos por descubrir. La plataforma no debe imponer una representación ni un mecanismo de inferencia únicos.

### Exploración accesible

El acceso al aprendizaje no debe presuponer recursos económicos abundantes, conocimientos de programación, infraestructura propia ni suscripciones a IA.

La inferencia es opcional. Además de integraciones con proveedores, debe investigarse la preparación de instrucciones copiables para que una persona explore usando un servicio de LLM disponible para ella. El material aprobado debe seguir teniendo valor sin inferencia.

### Sostenibilidad de la plataforma y de sus participantes

La presión operacional principal es permitir que el acceso público crezca sin comprometer la sostenibilidad económica de Alive Lab.

Se investigará cómo preservar la lectura de material pedagógico aprobado cuando sea necesario restringir temporalmente capacidades dinámicas de creación, administración o generación. Una posible distribución estática de contenido es una **hipótesis de realización**, no una arquitectura ya seleccionada; su recuperación y continuidad deberán probarse.

La sostenibilidad también incluye a quienes crean y mantienen el proyecto: accesibilidad educativa y remuneración digna no son objetivos necesariamente opuestos. Permanecen abiertas la licencia y las modalidades concretas de financiamiento.

## Caso real de partida

La lección [Cómo se llega a Clean Architecture](https://github.com/HernanFAR/teaching/tree/main/docs/lessons/clean-architecture) aporta una fuente pedagógica en [`generation-instructions.md`](https://github.com/HernanFAR/teaching/blob/main/docs/lessons/clean-architecture/generation-instructions.md) y una realización existente.

En ella se distinguen intención pedagógica, recorrido causal, invariantes, restricciones del caso, variables de realización y exploraciones soportadas. Se utilizará como **evidencia para descubrir contratos mínimos**; no demuestra que TDIR o Framework ya estén formalizados.

El repositorio [HernanFAR/teaching](https://github.com/HernanFAR/teaching) conserva la realización operacional actual. No se presupone migración ni sustitución.

## Preguntas iniciales

1. ¿Cómo facilitar la creación, revisión y autorización de fuentes pedagógicas, potencialmente mediante `.tdir`, para docentes sin conocimientos técnicos?
2. ¿Qué información necesita un realizador para producir experiencias distintas sin depender de una realización publicada previamente?
3. ¿Qué responsabilidades corresponden a Platform y cuáles a TDidacta Docs Standard, Framework o las especificaciones de TDIR?
4. ¿Qué realizaciones y exploraciones pueden ofrecerse sin exigir un proveedor de inferencia integrado?
5. ¿Cómo conservar el acceso al material aprobado ante restricciones económicas y recuperar las capacidades suspendidas?

Favorecemos **caso real → presión observable → responsabilidad → mecanismo mínimo → realización → observación → revisión**.

## Estado y límites

**Exploración inicial.** Este documento no selecciona arquitectura, lenguaje, base de datos, proveedor de infraestructura, proveedor de inferencia, licencia ni modelo comercial. Tampoco establece la semántica normativa de TDIR o la partición definitiva de productos TDidacta.

La investigación de conformidad semántica de realizaciones conserva su propia autoridad y trayectoria, aunque pueda aportar evidencia relacionada.

No crear recursos pagados ni publicar datos privados a partir de esta orientación.
