# TDidacta Platform — Software Development Run State

**Run ID:** `tdidacta-platform-initial-development`  
**Estado:** active — startup registrado, desarrollo aún sin incremento aprobado.  
**Repositorio consumidor:** [tdidacta/platform](https://github.com/tdidacta/platform) (`main`).  
**Protocolo:** [VSlices Software Development Meta-Protocol](https://github.com/vslices/planifications/tree/feat/software-development-meta-protocol/protocols/software-development), rama candidata `feat/software-development-meta-protocol`, observada 2026-10-11; no encontrado bajo el mismo recorrido en `main` al iniciar.  
**Fecha de inicio:** 2026-10-11.

## Orientation — por qué existe esta ejecución

Crear una plataforma que apoye a docentes y estudiantes para crear, autorizar, publicar, organizar y explorar experiencias educativas, sin imponer conocimientos técnicos ni un proveedor de inferencia. [README del producto](../../README.md). La plataforma debe preservar la autoridad docente sobre el material aprobado, distinguir apoyo inferencial de contenido oficial y estudiar continuidad económica ante crecimiento de uso.

Esta ejecución aplica el metaprotocolo como **candidato en un caso real**. Su eficacia no se presume demostrada.

### Alcance de producto conversado — evidencia de intención, aún por reconstruir como trabajo observable

- Creación asistida desde una intención pedagógica con amplio control docente; `.tdir` es una representación candidata, no un contrato ya validado.
- Publicación de lecciones: públicas prioritarias; privadas con autorización como objetivo de v1, admitiendo indisponibilidad temporal de privadas en contingencia, no divulgación accidental.
- Cinco exploraciones candidatas habilitables por lección: Otro caso, Profundizar, Aplicarlo a mi caso, Ponme a prueba y Apoyo conceptual (esta última experimental). La navegación/transición automática entre exploraciones queda diferida.
- Guías para agrupar lecciones, sin asumir marketplace, contratación de docentes, seguimiento académico avanzado ni inscripción institucional.
- Inferencia opcional: integración de proveedor o instrucciones copiables para servicio LLM externo. Generación y publicación editorial requieren autorización docente; respuestas generadas son material auxiliar.
- Presión económica: el crecimiento de consultas públicas no debería forzar costos operacionales insostenibles; hipótesis de continuidad del contenido público aprobado mediante distribución desacoplada de funciones dinámicas.

Estas declaraciones proceden de la conversación de inicio y el README. No constituyen pruebas de necesidades de terceros, especificaciones técnicas finales ni alcance comercial aprobado.

### Evidencia primaria y límites

- [Definición canónica de TDidacta](https://github.com/the-alive-lab/tdidacta/blob/main/README.md): sistema educativo más amplio; las fronteras de productos y TDIR permanecen abiertas.
- [Plataforma existente de referencia](https://github.com/HernanFAR/teaching): lecciones/guías publicadas en la realización previa, no migrada.
- [Instrucciones pedagógicas de Clean Architecture](https://github.com/HernanFAR/teaching/blob/main/docs/lessons/clean-architecture/generation-instructions.md): caso real, no esquema normativo de TDIR.
- [Metaprotocolo](https://github.com/vslices/planifications/blob/feat/software-development-meta-protocol/protocols/software-development/README.md) y [contrato de estado](https://github.com/vslices/planifications/blob/feat/software-development-meta-protocol/protocols/software-development/state.md), ambos candidatos.
- [Anexo de distribución Chat/local](https://github.com/vslices/planifications/blob/feat/software-development-meta-protocol/protocols/software-development/annexes/tdidacta-platform-execution-placement.md).

Observación al inicio: en `tdidacta/platform/main` solo existía `README.md`; no había `.vslices/developments/` ni ejecución equivalente observada. No existe código, build, pruebas, CI o despliegue verificado para **este repositorio**. La implementación anterior de `HernanFAR/teaching` es evidencia distinta.

## Situación de trabajo

**Fase actual:** Understanding — siguiente movimiento, no declarada completada.  
**Modalidad provisional:** Problem-First, porque se conoce la intención de producto pero faltan actores, condiciones, procesos y resultados verificables para el primer incremento. Revisable con evidencia.  
**Continuidad principal:** intención/autoridad docente y experiencia docente–estudiante → trabajo observable → responsabilidades justificables, antes de proponer arquitectura.

**Próxima acción acotada:** reconstruir con evidencia un solo recorrido real de creación, revisión, autorización y publicación de una lección, contrastándolo con la experiencia de la lección Clean Architecture, y explicitar actor, disparador, pasos, resultados, variantes y preguntas pendientes. No generar todavía esquema TDIR ni seleccionar stack. La definición de exploraciones, privacidad y guías sigue disponible como contexto, no como obligación de implementarlas simultáneamente.

**Comprobación esperada:** el recorrido permite a un tercero distinguir decisiones autorizadas, generación auxiliar, artefactos aprobados y acceso estudiantil sin introducir un diseño técnico como si fuese parte del problema.

**Bloqueos y riesgos:** no se han verificado requisitos oficiales, plazos ni criterios de Tools Competition; no incorporarlos como restricciones hasta contar con fuente oficial. Las fronteras semánticas de TDIR / Docs Standard / Framework permanecen abiertas y pertenecen a sus responsables. Faltan evidencia de docentes externos, criterios detallados de v1 y comprobación del modo de continuidad económica. Ninguno bloquea la reconstrucción inicial; sí puede bloquear compromisos o implementaciones posteriores.

## Autoridad y Execution Placement

Decisión confirmada para esta ejecución: **Chat es el entorno principal**; no migrar a Work por avanzar de fase. Limen participa en comprensión, modelado, diseño, alternativas, decisiones técnicas autorizadas, elaboración y revisión de código y análisis de evidencia. Hernán ejecuta manualmente comandos que dependan de su entorno local. Operaciones GitHub autorizadas pueden realizarse desde Chat. Resultados locales cuentan como observados solo tras recibir y examinar salidas reales.

Hernán conserva las decisiones organizacionales, financieras y de aprobación de alcance que le correspondan; los responsables pedagógicos y los repositorios propietarios conservan la autoridad sobre sus conceptos. La ejecución técnica local no otorga automáticamente autoría o autoridad universal. Revisar la distribución solo ante presión o cambio explícito.

## Startup realizado y continuidad

Se consultó el metaprotocolo candidato (README, state y how-to-start), se comprobó ausencia de ejecución en el repositorio consumidor, se contrastó la definición canónica de TDidacta, el README del producto y el anexo operacional, y se inicializó **este único estado**.

**Frontera alcanzada:** startup y Orientation mínimos registrados; **no se ha concluido Understanding**, no se ha ejecutado un prototipo ni verificado comportamiento pedagógico. La próxima presión es reconstruir la actividad humana concreta antes de derivar requerimientos o implementar.

Actualizar este archivo solo ante cambios materiales de fase, evidencia, decisiones, delegación, riesgo o siguiente presión. Referenciar artefactos propietarios en lugar de duplicarlos.
