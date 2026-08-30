<h1 align="center">¡Tokens! El juego de cartas</h1> <br>

En PANICOSA las aguas están revueltas. Los jefes se han puesto nerviosos y quieren que implementéis una plataforma de IA en la empresa «para ayer», o echarán a todo el Departamento de Informática. Total, han oido que, en menos de seis meses, los programadores no harán falta.

Tu misión es liderar al equipo que debe entregar las 3 fases del proyecto (MVP, Producción y Escalado) antes de que la deuda técnica os como vivos, usando todas las medidas a tu alcance y las habilidades de tus compañeros.

No sabemos a dónde nos llevará todo esto, pero como decía Edsger Dijkstra, «Si la informática trata sobre ordenadores y código, entonces la astronomía es la disciplina de manejar telescopios».

TOKENS es un juego cooperativo **para 1 a 4 jugadores**, que puede jugarse en **partidas rápidas de entre 5 y 10 minutos** con 3 niveles de dificultad. Pero, sobre todo, es una gran excusa para empezar una conversación con tus compañeros de partidas. Sobre la IA o la vida. Eso te lo dejamos a ti.

### CONTENIDO

La caja contiene un mazo de 71 cartas, dividas en 51 de operaciones (21 Modelos, 20 Contramedidas y 10 Técnicos), 17 de malware (16 Malware normales y 1 Prompt Injection multicolor) y 3 de proyectos (MVP, Producción y Escalado):

**PARA HUGO**: (dibujar una tabla parecida a la que aparece en las instrucciones de Virus, en las que además se ponga el número de cartas de cada modelo), pero en vez de Organos, Virus, Medicinas y Tratamientos, iremos con Modelos, Malware, Contramedidas y Técnicos)

<p align="center">
    <img alt="Tokens" title="Tokens" src="https://github.com/tarugoconf/tokens-reglas/blob/main/tabla_cartas.png?raw=true" height="300">
</p>

### PREPARACIÓN

1. Colocad las cartas de Proyecto en este orden: MVP, Producción y Escalado. Prototipo es el Proyecto inicial.
2. Barajad por separado el mazo de Operaciones y el mazo de Malware.
3. Elegid una dificultad y revelad el número correspondiente de cartas de Operaciones. Estas cartas forman el Contexto compartido:

| Dificultad | Contexto | Recomendación           |
| ---------- | -------: | ----------------------- |
| Vibecoder      | 8 cartas | Primera partida         |
| Junior     | 7 cartas | Experiencia recomendada |
| Senior    | 6 cartas | Equipos experimentados  |


4. Dejad espacio para:
* Una Plataforma IA de hasta 5 Modelos
* El Malware pendiente
* El Malware resuelto
* Los descartes de Operaciones

### OBJETIVO

Trabajáis como un único equipo. No existen manos personales ni turnos individuales. Todas las cartas están a la vista y todas las decisiones pertenecen al equipo.

Para ganar debéis completar, por orden, los tres Proyectos:
1. MVP
2. Producción
3. Escalado

Cada Proyecto exige desplegar determinados Modelos y proteger algunos de ellos con Contramedidas.

Mientras trabajáis irán apareciendo cartas de Malware. Si al comprobar la saturación hay 6 o más Malwares pendientes, perdéis la partida.

### CONCEPTOS BÁSICOS

**Contexto**: fila de cartas de Operaciones disponibles para todo el equipo. Su tamaño depende de la dificultad.

**Plataforma**: zona común donde se despliegan los Modelos. Puede contener un máximo de 5.

**Modelo operativo**: Modelo desplegado sin ninguna Contramedida.

**Modelo protegido**: Modelo con una Contramedida instalada. Cada Modelo admite como máximo una.

**Malware pendiente**: amenaza revelada que continúa sobre la mesa. El Malware no se coloca sobre ningún Modelo concreto: representa un riesgo para toda la Plataforma.

**Malware resuelto**: Malware que ha sido contenido. Permanece en una pila separada hasta que termina el Proyecto.

### COMO SE JUEGA

El juego consta de una serie de rondas, hasta que el equipo complete los sucesivos proyectos o pierda la partida. Cada ronda se resuelve siguiendo siempre estos 5 pasos:

1. Revelar Malware

Robad del mazo de Malware la cantidad indicada por el Proyecto actual y colocad las cartas boca arriba como Malware pendiente.

2. Realizar Operaciones

El equipo puede realizar, como máximo, el número de Operaciones indicado por el Proyecto.

Cada acción o técnico utilizado cuesta normalmente 1 Operación. El equipo puede realizar menos Operaciones si lo desea.

3. Comprobar la saturación

Contad el Malware que continúa pendiente.

Si hay 6 o más, la deuda técnica os satura y perdéis la partida.

La saturación no se comprueba al revelar el Malware, sino después de realizar las Operaciones. Por tanto, si al inicio de la ronda llegáis a 6, todavía podéis utilizar las Operaciones de esa ronda para reducir el peligro a 5 o menos.

4. Comprobar la entrega

Si no estáis saturados, comprobad los objetivos del Proyecto.

Si se cumplen todos, completáis el Proyecto.

La saturación se comprueba siempre antes que la entrega. Si en la misma ronda cumplís el objetivo, pero quedan 6 o más Malware pendientes, perdéis.

5. Reponer el Contexto

Si el Proyecto continúa (ni lo habéis superado ni habéis perdidos), robad Operaciones hasta recuperar el tamaño correspondiente a la dificultad: 8, 7 o 6 cartas.

El Contexto no se repone después de cada Operación. Las cartas utilizadas dejan huecos hasta el final de la ronda, excepto cuando una acción o un Técnico indique expresamente que debéis reponerlo inmediatamente.

LAS 5 OPERACIONES

Cada una de las siguientes acciones cuesta 1 Operación.

1. Desplegar un Modelo

Elegid un Modelo del Contexto y colocadlo en la Plataforma.

La Plataforma puede contener un máximo de 5 Modelos. Si ya está llena, podéis retirar uno de sus Modelos —junto con su Contramedida, si la tiene— y desplegar el nuevo como parte de la misma Operación.

Las cartas retiradas van al descarte de Operaciones.

2. Instalar una Contramedida

Elegid una Contramedida compatible del Contexto y colocadla sobre un Modelo de la Plataforma que no tenga otra instalada.

Ese Modelo pasa a estar protegido.

Instalar una Contramedida no contiene automáticamente ningún Malware. Sirve para cumplir los objetivos de los Proyectos y para reservar esa defensa para una ronda posterior.

3. Contener Malware

Elegid un Malware pendiente y descartad una Contramedida compatible.

La Contramedida puede proceder:

Directamente del Contexto.

De un Modelo que ya la tuviera instalada.

Si utilizáis una Contramedida instalada, el Modelo permanece en la Plataforma, pero deja de estar protegido.

Colocad la Contramedida en el descarte de Operaciones y pasad el Malware a la pila de Malware resuelto.

No es necesario instalar previamente una Contramedida para utilizarla contra un Malware.

4. Activar un Técnico

Elegid un Técnico del Contexto, aplicad completamente su efecto y descartadlo.

Los Técnicos se explican más adelante.

5. Refrescar el Contexto

Descartad hasta 3 cartas del Contexto y reponedlo inmediatamente hasta recuperar su tamaño normal.

Refrescar cuesta 1 Operación, independientemente del número de cartas descartadas.

### FABRICANTES Y COMPATIBILIDAD

Cada fabricante comparte un color y un símbolo:

| Fabricante    | Modelo    | Malware          | Contramedida               |
| ---------- | --------- | ---------------- | -------------------------- |
| Rojo   | Gepeto    | Alucinación      | Toma de tierra (RAG)       |
| Naranja   | Claudio   | Prompt Leak      | Cortafugas (Policy Engine) |
| Azul       | Deep Geek | Data Poisoning   | Data Detox                 |
| Verde    | Croc      | Devoratokens     | Token Bucket               |
| Multicolor | Miñanai   | Prompt Injection | Full Stack Defense         |

**PARA HUGO**: (la tabla puede ser puro texto, pero con cada linea del color que le corresponda o visual, con imágenes de las cartas que corresponden)

#### Modelos normales

Un Modelo normal acepta:
* Una Contramedida de su propiao fabricante.
* Una Full Stack Defense multicolor.

#### Miñanai

Miñanai puede recibir una Contramedida de cualquier fabricante.

Sin embargo, Miñanai cuenta como un quinto fabricante propio. No copia el fabricante de la Contramedida instalada ni la de otro Modelo.

Una Contramedida normal instalada sobre Miñanai conserva su color y sus propiedades originales.

Por ejemplo, una Data Detox azúl instalada sobre Miñanai puede utilizarse contra Data Poisoning azúl, pero no contra cualquier Malware.

#### Malware normal

Un Malware normal puede contenerse utilizando:
* Una Contramedida de su mismo fabricante.
* Una Full Stack Defense multicolor.

#### Prompt Injection

Prompt Injection es el Malware multicolor. Puede contenerse de dos maneras:
* Utilizando una Full Stack Defense.
* Utilizando conjuntamente 2 Contramedidas normales de fabricante diferentes.

Las 2 Contramedidas deben gastarse en una única Operación. Pueden proceder del Contexto, estar instaladas sobre Modelos o combinar ambos lugares.

Dos Contramedidas normales del mismo color no sirven.

### LOS TÉCNICOS

**PARA HUGO**: (es muy importante que junto al título de cada técnico pongamos el dibujo de la carta correspondiente o al menos el icono, para que pueda reconocerse inmediatamente durante las partidas:

Los Técnicos realizan acciones especiales. Jugarlos cuesta 1 Operación.

#### Developer

Desplegad hasta 2 Modelos del Contexto utilizando una sola Operación.

Podéis desplegar solamente uno. Debéis respetar siempre el máximo de 5 Modelos de la Plataforma y retirar previamente los que sea necesario sustituir.

#### Model Hacker

Revelad hasta 5 cartas del mazo de Operaciones.
* Si aparece algún Modelo, desplegad uno de los Modelos revelados y descartad las demás cartas.
* Si no aparece ningún Modelo, añadid una de las cartas reveladas al Contexto y descartad el resto.

Las cartas descartadas no regresan al mazo hasta que termine el Proyecto.

#### Red Teamer

Contened un Malware pendiente sin gastar ninguna Contramedida.

Puede contener cualquier Malware, incluido Prompt Injection.

El Malware contenido pasa a la pila de resueltos.

#### Context Engineer

Descartad este Técnico y tantas cartas adicionales del Contexto como queráis.

Reponed inmediatamente el Contexto hasta recuperar el tamaño correspondiente a la dificultad.

#### Solutions Architect

Descartad este Técnico y elegid en el Contexto:
* Un Modelo.
* Una Contramedida compatible con ese Modelo.

Desplegad ambos juntos. El Modelo entra directamente protegido y toda la acción cuesta una única Operación.

Si la Plataforma está llena, retirad antes un Modelo y su Contramedida instalada.
