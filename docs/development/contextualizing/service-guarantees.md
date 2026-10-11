# Contextualizing: garantias de servicio

Autor: Limen. Estado: candidatos a contrastar, no capacidades implementadas ni SLA. Origen: objetivo de Hernan, canon TDidacta, evidencia de Understanding.

## Regla de separacion

**Contextualizing define comportamientos y limites. Planning selecciona infraestructura y mecanismos que los cumplan.** La publicacion independiente del generador no implica automaticamente independencia del alojamiento, red, dispositivo o recursos remotos.

## Garantias candidatas

| ID | Comportamiento comprobable | Limites y prueba candidata |
| --- | --- | --- |
| SG-01 | El contenido publico aprobado continua accesible cuando se detiene el generador, si la distribucion sigue disponible | Publicar, detener generacion y consumir desde el canal separado |
| SG-02 | La lectura esencial no depende de servicios de autoria ni inferencia cuando se declara autonoma | Auditar llamadas y recursos de una publicacion |
| SG-03 | Al perderse servicios dinamicos, las funciones independientes siguen operativas; dependencias indisponibles se explican | Simular caida del servicio remoto |
| SG-04 | Cuando se declara soporte offline, delimitar recursos y funciones disponibles sin red | Preparar copia, desconectar y probar; no prometer offline universal |
| SG-05 | Solo una version aprobada puede publicarse, sin sustitucion silenciosa | Probar propuesta rechazada, aprobacion y comparacion de version publicada |
| SG-06 | Actualizacion y retiro respetan autoridad, licencias y limites reales de copias distribuidas | Simular reemplazo/revocacion; copias offline no son revocables instantaneamente |
| SG-07 | Un artefacto publicable puede ser servido/consumido sin el backend que lo creo | Probar canal separado con generador detenido |
| SG-08 | Dependencias y costos operacionales se hacen examinables | Documentar conexiones, recursos y mecanismos; medir antes de prometer cifras |
| SG-09 | La degradacion no elimina injustificadamente acceso al contenido esencial | Evaluar accesibilidad, medios alternativos y lectura basica en escenarios de fallo |
| SG-10 | Fuente pedagogica, TDIR, propuesta, realizacion y version aprobada conservan procedencia y diferenciacion | Pruebas de invariantes, atribucion, estado editorial y resultados no evaluables |

## Casos que Contextualizing debe contrastar

1. Generador activo, distribucion activa.
2. Generador detenido, distribucion activa.
3. Inferencia remota caida, contenido autonomo accesible.
4. Distribucion caida, sin alternativa: no asumir disponibilidad absoluta por usar contenido estatico.
5. Dispositivo desconectado: solo funciones **explicitamente declaradas offline**.
6. Publicacion actualizada, retirada o no autorizada.

La primera realizacion candidata parte de intencion Clean Architecture, TDIR base generado por Platform, realizacion generada por Platform, revision/aprobacion y publicacion autonomamente consumible. Su secuencia es de **produccion**, no un flujo universal de aprendizaje. El objetivo de TDIR no autoriza por si solo un schema general.

## Fronteras de decision

- **Contextualizing**: decidir que garantias aplican al primer caso, que es una funcion autonoma, que depende de tercero, que ocurre al fallar, quien autoriza publicar y retirar y como se comprueba.
- **Planning**: evaluar hosting estatico separado, CDN, almacenamiento, PWA/offline, empaquetado portable, generacion local/remota, autenticacion y despliegue. Seleccionar despues de fijar las garantias.
- **Validating**: ejecutar fallos intencionales, verificar continuidad de lectura, integridad, procedencia y accesibilidad, sin afirmar por ello aprendizaje estudiantil.

Todas las SG estan **pendientes de contraste y seleccion**. No hay implementacion o compromiso de disponibilidad absoluta. La capacidad de distribuir estaticamente y de funcionar offline son alternativas a evaluar segun el comportamiento exigido, no elecciones tecnicas adelantadas.
