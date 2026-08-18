# I. BASE — Dominio, Fundación y Resiliencia

[← Volver al manifiesto](README.md)

Toda gran visión exige un suelo firme. Los sistemas de alta escala y disponibilidad no aceptan improvisos y nacen del entendimiento profundo del negocio.

## Principios

* **Comprensión del negocio como premisa:** No existe arquitectura fuerte sin dominio del contexto. Entender los dominios de negocio que el software toca es el primer paso para determinar cómo debe diseñarse y construirse.
* **La estabilidad precede a la innovación:** Ningún algoritmo avanzado sustituye un cimiento frágil. La infraestructura y el modelado de datos deben diseñarse para soportar alta carga, concurrencia severa y crecimiento exponencial.
* **Aislamiento y previsibilidad:** Los componentes deben ser autónomos y tolerantes a fallos. La infraestructura de base debe ser estrictamente determinista, observable y resiliente, garantizando que fallos puntuales jamás comprometan el ecosistema.
* **Arquitectura en todos los niveles:** Todo profesional de TI necesita conocer arquitectura, en profundidades distintas según su función. Del conocimiento más superficial al más profundo, cada capa amplía la calidad de las decisiones.

## Arquitectura en todos los niveles

La arquitectura no es un oficio reservado a quien tiene el cargo en la credencial. Es alfabetización: todo profesional de TI la necesita, en grados distintos. Quien ve el sistema más allá de su propia tarea elige mejor, conversa mejor y se equivoca menos.

La profundidad cambia con la función. Lo que no cambia es el efecto: incluso un recorte superficial ya mejora la decisión; un recorte profundo hace posible la orientación.

### Ejemplos por profundidad

**Desarrollador junior** — querer saber cómo llega una petición (cliente → red → API → servicio → datos) ya localiza el propio trabajo en el sistema, sea back o front. Ese mapa mínimo reduce el “código en el vacío”: la persona entiende de dónde viene el dato, hacia dónde va el error y por qué existe un contrato.

**Designer** — un poco de arquitectura amplía ideas y posibilidades. Saber que existen latencia, caché, estados de carga o límites de un contrato de API cambia lo que vale la pena diseñar — y lo que vale la pena defender. Sin ese recorte, el diseño compite con el sistema; con él, el diseño usa el sistema.

**Profesional de arquitectura** — necesita un conocimiento mucho más profundo para decidir y orientar. Trade-offs, límites, evolución y riesgo no caben en un diagrama de alto nivel: exigen criterio. Sin esa profundidad, la orientación se vuelve opinión; con ella, se vuelve responsabilidad.
