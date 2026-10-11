# Cierre acotado de Understanding y condiciones de entrada a Contextualizing

**Autor:** Limen. **Fecha:** 2026-10-11. **Estado:** evaluacion de frontera y propuesta de secuencia, sin cierre formal ni cambio de fase. **Origen nuevo:** precisiones de Hernan en conversacion.

## Direccion confirmada por Hernan

El primer ejercicio debe **replicar la intencion verificable** del caso de Clean Architecture desde **un `.tdir` base generable mediante TDidacta Platform**. El `.tdir` debe ser fuente para un **artefacto realizable por la propia Platform**, y los artefactos realizados deben poder **publicarse y mantener su comportamiento autonomo declarado sin depender de que la Platform generadora siga activa**.

Esto establece un objetivo de capacidad a investigar y realizar, no significa que existan ya especificacion TDIR, generador, publicador, artefacto ejecutable, CI ni prueba de independencia. No confundir un export manual con generacion real desde Platform o una pagina estetica con preservacion semantica.

## Contraste con el protocolo y Understanding existente

El [metaprotocolo de software development](https://github.com/vslices/planifications/blob/feat/software-development-meta-protocol/protocols/software-development/README.md) plantea que Understanding reconstruya trabajo real, actores, condiciones, resultados y desconocidos, y que Contextualizing relacione esos trabajos con dominios, sistemas y responsabilidades. No exige resolver mecanismo, stack o arquitectura en Understanding.

Base suficiente:
- [Classroom Reality](classroom-reality-contextualizing-inventory.md): 21 candidatos; realizacion educativa no es sesion lineal ni evidencia automatica de aprendizaje.
- [Educational Adoption](educational-adoption-contextualizing-inventory.md): 23 candidatos; acceso y uso, impacto y sostenibilidad son diferentes.
- [Evaluacion integrada de Seyra](seyra-integrated-handoff-triage.md): precisiones existentes, sin nuevos candidatos.
- [Caso pedagogico historico](https://github.com/HernanFAR/teaching/blob/main/docs/lessons/clean-architecture/generation-instructions.md): intencion, invariantes, condiciones y contrafactuales documentados.
- [Canon actual de TDidacta](https://github.com/the-alive-lab/tdidacta/blob/main/README.md): diversidad de participantes/realizaciones, sin TDIR normativo.
- [README de Platform](https://github.com/tdidacta/platform/blob/main/README.md): autoridad editorial, inferencia opcional, sostenibilidad y acceso publico; no existe codigo de la nueva Platform verificado.

## Distinciones por resolver para justificar cierre acotado

| ID | Frontera pendiente de Understanding | Criterio para considerarla suficientemente comprendida | Lugar de resolucion |
| --- | --- | --- | --- |
| U-01 | Necesidad primaria frente a solucion imaginada | Registrar quien necesita convertir una intencion en recursos y para que, separando necesidad de `.tdir` como medio propuesto | Understanding |
| U-02 | Propuesta `.tdir` vs contrato semantico | Especificar **que informacion debe preservarse** al reconstruir la intencion del caso sin fijar schema ni universalidad | Understanding -> Contextualizing |
| U-03 | Material, realizacion publicada y ensenanza efectiva | Distinguir artefacto producido, experiencia publicable y acto de ensenar/aprender; nombrar resultado verificable de cada uno | Understanding |
| U-04 | Independencia operacional | Precisar que significa «Platform inactiva» y que comportamiento independiente se espera conservar | Understanding -> Contextualizing |
| U-05 | Autoridad editorial y de publicacion | Identificar quien puede producir propuesta, revisar, autorizar y retirar una publicacion y que no puede hacer IA unilateralmente | Understanding -> Contextualizing |
| U-06 | Garantias y evidencia | Diferenciar verificaciones mecanicas, conformidad pedagogica del caso y evidencia de aprendizaje humano | Understanding -> Contextualizing |
| U-07 | Alcance de diversidad | Registrar que Clean Architecture es primer caso y necesita contraejemplo futuro; no inferir dominio universal ni cobertura de todos los grupos | Understanding |
| U-08 | Derechos/privacidad y terceros | Registrar que una fuente publicable necesita permisos de uso, alcance de datos y dependencias; resolver mecanismos cuando existan casos | Understanding -> Contextualizing |

**Juicio:** U-01/U-03/U-06/U-07 tienen base documental suficiente, sujetas a una reconstruccion focalizada; U-02/U-04/U-05/U-08 son **fronteras para Contextualizing**, no excusas para exigir diseno tecnico anticipado. No es necesario ejecutar R0a/R0b o estudios con usuarios para este cierre acotado. Hay evidencia suficiente para **proponer cierre delimitado de Understanding**, pero el acto formal de cierre aun no se registra.

## Entrada propuesta a Contextualizing

1. **Reconstruir caso fuente:** diferenciar el contrato historico de Clean Architecture, las responsabilidades propias del sistema actual TDidacta y el mecanismo `.tdir` propuesto. La nueva fuente no se presume copia sintactica de `generation-instructions.md`.
2. **Distinguir responsabilidades y limites:** creacion/asistencia, verificacion semantica, realizacion concreta, revision/autorizacion, publicacion/distribucion, consumo autonomo, funciones dinamicas opcionales. La enumeracion es **pregunta de frontera**, no arquitectura por componentes.
3. **Definir «artefacto realizable» por un caso acotado:** entradas permitidas, salida examinable y evidencia de que Platform efectivamente lo realizo. Evitar exigir motor general.
4. **Definir autonomia observable:** publicado y servido sin requerir que el proceso de autoria/generacion este online. Aclarar dependencia de hosting/distribucion independiente, recursos remotos, autenticacion, inferencia y almacenamiento antes de expresar niveles de servicio. No prometer «funciona sin Internet» sin prueba.
5. **Contrastar cuatro escenarios:** Platform activa; Platform generadora detenida pero distribucion disponible; servicio dinamico externo inaccesible; publicacion revocada/actualizada. Distinguir disponibilidad, integridad, autorizacion y continuidad. Elegir garantias futuras por valor/costo y evidencia, no enumerarlas como requisitos inevitables.
6. **Contrastar contra inventarios y alternativas:** CR-01/02/03/06/07/17/20/21; EA-03/07/08/09/10/16/19/21/23 y la opcion de aprovechar material de Teaching existente o herramienta alternativa. La segunda materia pedagogica puede tensionar extrapolaciones cuando proceda.

## Invariantes candidatos para futura validacion, NO contratos vigentes

- El origen pedagogico de un artefacto y la realizacion se pueden relacionar y revisar.
- Ninguna variacion aceptada altera silenciosamente las invariantes especificas del caso.
- Una publicacion no ocurre a partir de propuesta no autorizada.
- Una publicacion independiente conserva la version aprobada aunque se detenga su generador, **bajo supuestos explicitos sobre el canal que la sirve**.
- Las partes que requieren inferencia, sesion o servicio remoto distinguen sus dependencias y su comportamiento ante fallo.
- Las verificaciones tecnicas no se atribuyen como prueba de aprendizaje humano.

## Lo que NO se determina todavia

Esquema TDIR, serializacion, parser, versionado, licenciamiento concreto, engine de realizaciones, stack, framework, hospedaje, cache/CDN, gestion de identidades, SLAs, escenarios penitenciarios como feature, catalogo universal de metodologias, modelo de costos, garantia de 100% uptime o soporte offline universal.

## Decisiones siguientes y responsables

- **Limen:** preparar cierre de Understanding **limitado al problema y primer caso** con evidencia y pendientes; contrastar frontera de productos con sus fuentes propietarias; formular entrada concreta a Contextualizing.
- **Hernan:** confirmar cualquier compromiso de producto o alcance que exceda el objetivo expresado. Su indicacion actual autoriza analizar, no significa aprobar stack ni construir a ciegas.
- **Research/Seyra:** mantener evidencia y preguntas propias; retorno solo si aparecen vacios empiricos sustantivos.
- **Contextualizing:** resolver suficiencia semantica del primer `.tdir`, fuentes/realizadores/publicacion, dependencias y garantias candidatas. **Planning** transformara las decisiones seleccionadas en incrementos, pruebas y mecanismos justificables.

**Posicion de Limen:** no comenzar por codigo ni por un documento de SLA; comenzar por la frontera de Understanding y avanzar a Contextualizing cuando el cierre acotado sea reconstruible.
