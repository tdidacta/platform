# Candidato de fuente pedagogica verificable para TDidacta Platform

**Autor:** Limen. **Fecha:** 2026-10-11. **Estado:** propuesta para contrastar en Contextualizing; no contrato canonico TDIR, ni decision de arquitectura, ni implementacion ya realizada.

## Correccion de objetivo

El objetivo no es una «demo defendible»: **cada capacidad afirmada debe funcionar y debe disponer de evidencia apropiada**. Una presentacion o financiamiento puede reutilizar esa evidencia, pero no sustituirla. La primera realizacion debe perseguir correccion y verificabilidad, no numero de formatos o impacto visual.

## Precedente y frontera

[Fuente de Clean Architecture](https://github.com/HernanFAR/teaching/blob/main/docs/lessons/clean-architecture/generation-instructions.md): intencion, evidencia de comprension esperada, recorrido causal, invariantes, variables y limites. [Diseño de realizacion](https://github.com/HernanFAR/teaching/blob/main/docs/lessons/clean-architecture/realization-design.md) y [evidencia de implementacion](https://github.com/HernanFAR/teaching/blob/main/docs/lessons/clean-architecture/realization-implementation.md) separan seleccion de caso, realizacion y comprobaciones.

La secuencia especifica «estado inicial -> presion -> transformacion» pertenece a esa leccion, **no** a toda pedagogia. El canon actual de [TDidacta](https://github.com/the-alive-lab/tdidacta/blob/main/README.md) abarca diversas experiencias, actores y medios. Las funciones de la fuente actual no son automaticamente entidades universales ni campos TDIR obligatorios.

## Fuente candidata minima: caso concreto, no formato universal

Para la primera prueba, tomar la fuente historica *Como se llega a Clean Architecture* como caso de comparacion **con su procedencia historica explicita**, y redactar una representacion candidata contemporanea, sin modificar la fuente original ni exigir que todo tema tenga su misma forma:

1. **Necesidad/intencion:** que deberia poder comprender o hacer una persona tras la experiencia; contexto, conocimientos supuestos y pregunta guia.
2. **Afirmaciones e invariantes:** significados, relaciones y limites que no deben perderse. Por ejemplo: no presentar Clean Architecture como plantilla obligatoria ni separar antes de presion observable.
3. **Variaciones permitidas:** caso conductor, lenguaje, ejemplo, representacion, cantidad/orden de apoyos cuando no afecten las razones que esta fuente preserva.
4. **Condiciones y restricciones:** recursos, acceso, idioma, evidencia y destinatarios conocidos; lo que no se sabe debe marcarse.
5. **Respaldos y ejemplos:** fuentes publicas cuando se mencionen metodos pedagogicos, separando evidencia de uso de evidencia de eficacia; con limites y procedencia.
6. **Autoridad:** quien propone contenido, quien lo revisa y quien aprueba su publicacion; inferencia y sugerencias no se convierten silenciosamente en fuente aprobada.
7. **Evidencia esperada:** que podria mostrar la persona que aprende y que NO se puede inferir de una respuesta o de un recurso generado.
8. **Exclusiones honestas:** lo que esta fuente no pretende enseñar, generar o comprobar.

Es un **guion de reconstruccion del caso**, no schema, campos obligatorios, ontologia de metodos ni protocolo universal de produccion.

## Recorrido candidato de realizacion verificable

1. Recuperar la fuente y seleccionar objetivo concreto sin fabricar necesidad.
2. Preparar una realizacion (inicialmente puede ser textual/estatica) y documentar que partes se preservan o cambian.
3. Contrastar el resultado frente a invariantes y limites de la fuente, identificando errores y casos no evaluables.
4. Revisar/corregir deliberadamente, conservando diferencia entre propuesta y version aprobada.
5. Publicar/mostrar la version aprobada y comprobar que la salida publicada coincide con ella; no sustitucion por inferencia en lectura.
6. Elaborar segunda realizacion **solo si** la primera supera comprobaciones y la variacion tiene un proposito legible.
7. Registrar fallos, contraejemplos, desviaciones y revision de la fuente si aparecen insuficiencias reales.

**No implica flujo pedagogico lineal obligatorio:** es un itinerario experimental de construccion/validacion de un artefacto concreto. Una clase real puede interrumpirse, cambiar medios o no ocurrir.

## Matriz de afirmaciones y pruebas (candidatas)

| Afirmacion posible | Evidencia minima que la haria defendible | Lo que NO prueba |
| --- | --- | --- |
| «Genera/compone un recurso» | Entrada, salida reproducible y comprobacion de contenido, errores y ausencia de datos inventados | Aprendizaje del estudiante |
| «Preserva la intencion en este caso» | Invariantes especificos y contrastes adversariales para la realizacion | Conformidad universal de toda pedagogia |
| «Permite revisar y aprobar» | Prueba de cambio editorial y rechazo; nada se publica antes de autorizacion | Que el contenido aprobado es pedagogicamente eficaz |
| «Publica la version aprobada» | Lectura de lo publicado y comparacion con artefacto autorizado; casos negativos | Sostenibilidad bajo escala real |
| «Admite dos realizaciones» | Dos salidas verdaderamente distintas contrastadas con la misma fuente, limites visibles | IR universal ni independencia de cualquier modelo |
| «Explica un metodo pedagogico con evidencia» | Referencia publica verificable, contexto, ejemplo, incertidumbre y alcance del respaldo | Que ese metodo mejora aprendizaje en cualquier aula |
| «Ayuda a aprender» | Estudio posterior con participantes y medidas de aprendizaje apropiadas | No afirmable por tests de software |

## Primeras falsaciones que buscar

- Realizacion agradable visualmente que contradice una invariante.
- Propuesta de IA que cambia el alcance o introduce conceptos fuera de fuente sin aviso.
- Rechazo editorial que accidentalmente termina publicado.
- Actividad completada confundida con aprendizaje demostrado.
- Explicacion de metodologia respaldada solo por un ejemplo promocional.
- Un segundo formato que no aporta variacion real o que pierde significado.
- Contenido fiel a la fuente historica pero inutilizable para personas con menos conocimientos previos; revisar supuestos, no ocultar.
- La mejor opcion es reutilizar la leccion historica o una herramienta externa en vez de construir otra cosa.

## Preparacion para Contextualizing

Confrontar estas preguntas contra CR-01/02/03/06/07/17/20/21 y EA-03/19/21/23; conservar el triage de Seyra, y mantener separados resultado pedagogico esperado, material generado, clase realizada, outcome medido, aceptacion editorial, y operacion de Platform.

**Siguiente decision:** confirmar si *Clean Architecture* sera nuestro primer caso para comprobar preservacion de intencion, o si un segundo tema servira mejor como contraejemplo. Esta propuesta no adelanta stack, esquema, despliegue, ni fecha garantizada.
