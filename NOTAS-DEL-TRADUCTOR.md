# Notas del traductor de Bad Apple en español
**Qué es:** lo que conviene saber para jugar Bad Apple con este parche: qué se tradujo, qué se dejó como estaba y por qué, y las referencias que en inglés se entienden solas. **Cuándo leerlo:** si algo del juego te suena raro o quieres saber de dónde sale una referencia. Sin destripes de la trama.
**Estado:** VIVO — comprobado el 22-nov-2026.
**Fuente de verdad:** `fuente/` de este proyecto (lo que lleva el parche). **Sirve para:** entender las decisiones de la traducción sin leer el original.

Bad Apple es un mod de Team Starlight, basado en el fanfic de Umbruhh, para Snoot Game (Cavemanon). Esta traducción es un parche no oficial hecho por fans, sin ánimo de lucro: no incluye ni modifica ningún archivo del mod ni del juego.

## Qué está traducido
- Todo el diálogo y la narración de los seis capítulos (arcos «La Torre» y «Los Enamorados»).
- El menú de arcos y capítulos, los nombres de los personajes secundarios y los textos que aparecen sueltos en pantalla.
- El nombre y la descripción del mod en el menú de mods.
- Las tarjetas de capítulo y el cartel final llevan un subtítulo en español; la imagen original no se toca.

## Qué se dejó como en el original, a propósito
- **Los títulos de los capítulos** (*Fade to Black*, *Carousel of Agony*, *Can’t Break Free*, *Maybe It’s A Dream*, *Slipping Through The Cracks*, *Step Into The Light*). Van dibujados en las tarjetas y funcionan como títulos de canción; traducidos perderían la referencia.
- **La letra de la canción** que Anon recibe por mensaje en el capítulo 2: se muestra en inglés, como en el mod.
- **Los nombres de marcas y locales**, que son parodias: DVS (CVS), Stoka Cola, 11-Up, PachyStation, Xrox, iStone, Snootcord, SnootTube, MissingLinkedIn, Hadro Civic, Stegsung, Hot Tropic, GameRock, Bubb Lee, Glory Hole Donuts, Lotus Land Arcade.
- **Los títulos de anime y de juegos**, con el nombre con que se conocen en Latinoamérica (*Attack on Titan*, *My Hero Academia*, *Sword Art Online*, *Fullmetal Alchemist: Brotherhood*, *Demon Slayer*, *Vinland Saga*…).
- **La voz de la máquina de peleas** del arcade (`KO!`, `ROUND ONE. FIGHT!`): un arcade suena así.
- **El francés de la familia Baudelaire** y el japonés de Stella: en el original tampoco se traducen.
- **Las cartas del tarot dibujadas** y los créditos finales: son arte de los autores.

## Tres cosas que cambian al pasar al español
1. **El español de Rosa.** En el original Rosa habla inglés y suelta palabras y frases en español; de ahí que el narrador diga cosas como «murmura algo en español» o que alguien «no entiende ni una palabra». En esta traducción todo está en español, así que ese contraste no se oye: cuando el texto hable de «el español de Rosa», piensa que los demás la oyen cambiar de idioma. Así lo resolvió también la traducción oficial de Snoot Game.
2. **«An-on».** Rosa y su madre pronuncian así el nombre de Anon. Se conserva.
3. **Fang y los pronombres.** Casi todos hablan de Fang en femenino. Trish no: usa el pronombre neutro y se enfada si alguien no lo hace. En español va con «elle» y terminaciones en «-e», igual que en la traducción oficial del juego base.

## Pequeño diccionario
| En el juego | Qué es |
|---|---|
| skinnie | insulto de los dinosaurios hacia los humanos |
| trigga | insulto hacia los triceratops |
| carfe | la droga del universo de Snoot Game (café muy cargado) |
| estego | forma corta de «estegosaurio»; así llama Anon a Stella |
| Jesús Raptor | la figura religiosa del mundo del juego |
| la férula | el aparato ortopédico que Anon lleva en la pierna |
| bobo | el mote cariñoso que Fang le daba a Anon (*dweeb*) |
| Lucy | el nombre que Fang dejó de usar; algunos mayores todavía la llaman así |
| otaku, waifu, normie, vidya | jerga de foros; *vidya* son los videojuegos |
| derramar el espagueti | meme de foros: hacer el ridículo por los nervios |
| una Karen | la clienta que exige «hablar con el gerente» |

## Referencias que se entienden mejor sabiendo esto
- **Los arcos llevan nombre de carta del tarot:** La Torre (derrumbe), Los Enamorados y, anunciado para más adelante, La Fuerza. Las tarjetas que aparecen cuando cambia quien narra también son cartas: XIII La Muerte (Anon), XV El Diablo (Trish) y XVII La Estrella (Stella).
- **Parasaurna 4 Arena Ultimate**, el juego del arcade, es una parodia de *Persona 4 Arena Ultimax*; por eso el locutor anuncia a «Eliza».
- **Lotus Land Arcade** alude a *Lotus Land Story*, el juego de la saga Touhou del que viene la canción «Bad Apple!!», que da nombre al mod y suena en varias versiones.
- **Anon Y. Mous** es *anonymous* partido en nombre y apellido; de ahí que Stella lo llame «señor Mouse».
- **Bubb Lee**, el local de té de burbujas, mezcla *bubble* con Bruce Lee.
- **Glory Hole Donuts** tiene en inglés un doble sentido subido de tono que el nombre conserva.
- **Volcaldera's Got Talent** es el concurso de talentos de la ciudad, al estilo de *Got Talent*.

## Frases en francés (para quien quiera saber qué dicen)
| Francés | Español |
|---|---|
| mon cher / ma chérie | querido / querida mía |
| désolé / nous sommes désolés | lo siento / lo sentimos |
| c'est pas grave | no pasa nada |
| oui / non / merci / au revoir | sí / no / gracias / hasta luego |
| le père | el padre |
| après la pluie, le beau temps | después de la lluvia sale el sol |

## Si algo se ve mal
- **No sale la caja de diálogo y aparece el texto `Couldn't find file 'gui/textbox_long.webp'.`** No es de Bad Apple ni de este parche: ocurre cuando el mod Age After Beauty 1.1 está activado a la vez, porque busca una imagen que Patch 14 no trae. Arreglo: con el juego cerrado, entra en `game\gui\`, haz una copia de `textbox_long.png` y ponle a la copia el nombre `textbox_long.webp` (se deshace borrando esa copia). O desactiva Age After Beauty en el menú de mods (casilla a su izquierda y «Recargar Mods») mientras juegas otra cosa.
- **Todo sale en inglés:** comprueba que el idioma del juego sea Español y que la carpeta `es` esté dentro de `game\mods\BadAppleMod\`.

## Cómo está hecha
Traducción al español latinoamericano hecha con ayuda de inteligencia artificial (Claude), con una guía de estilo común para todos los capítulos, revisión posterior y comprobación en el propio motor del juego: se recorrió el mod entero en español para confirmar que cada línea aparece traducida y cabe en el cuadro de diálogo. No es una traducción profesional humana y puede tener fallos: si encuentras uno, avisa en la página donde descargaste el parche (apartado de avisos, «Issues»).
