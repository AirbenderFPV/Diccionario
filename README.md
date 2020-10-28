# Diccionario FPV

En esta sección les explico que significa uno que otro término y acrónimo utilizado en drones.  
La organice por tema en vez de abecedario para que sea mas fácil de leer para alguien nuevo.  

### Controladora de vuelo

FC: Esta es tu controladora de vuelo.

AIO: Las controladoras AIO, normalmente contienen OSD, PDB y tu controladora en un solo circuito integrado.

Tower / Torre: Generalmente estas controladoras de vuelo vienen segmentadas en 2 o 3 partes, pero contienen todo lo que necesitas, desde ESC, VTX, PDB y controladora de vuelo.

Led: Diodo emisor de luz, también es un puerto por el cual puedes agregar control a los leds que se agregan al drone.

Overclock: Cuando haces que tu procesador trabaje a una velocidad mayor a la que fue diseñado. Corres el riesgo de quemar algo.

Firmware: Es el software de algún componente ya sea controladora de vuelo o ESC.

UART: Estos son los puertos que se utilizan para sacar o recibir comunicación, ya sea ibus, fport, sbus, smartport, smartaudio, ppm, etc.

Ibus: Protocolo de comunicación por la cual tu FC recibe información de tu receptor. Normalmente usado por FlySky

Sbus: Protocolo de comunicación por la cual tu FC recibe información de tu receptor. Normalmente usado por FrSky

SmartPort: Protocolo de comunicación que transmite telemetría por medio de tu receptor. Normalmente usado por FrSky.

Fport: Protocolo de comunicación por la cual tu FC recibe información y transmite telemetría por medio de tu receptor. Normalmente usado por FrSky, este protocolo sustituye sbus+smartport

SmartAudio: Es un puerto que se utiliza para cambiar parámetros de tu VTX, como potencia y canal.

PPM: Protocolo de comunicación antiguo que usan algunos receptores baratos. Suficientemente bueno, pero ya esta algo obsoleto.

OSD: Es un chip que agrega información a tu señal de video, de tal modo que puedas ver cosas como voltaje o tiempo sobrepuesta en la imagen que recibes en tus gafas.

F1 / F3 / F4 / F7: Es el procesador que se utiliza en la controladora de vuelo, los F1 ya estan obsoletos. Lo que se usa hoy en dia son los F4 y F7.

MPU6000: Este es el numero de parte del giroscopio, solo llega a 8khz.

ICM20###: Este es el numero de parte del giroscopio, permite el uso de 32khz.

Barómetro: Sensor que permite saber la altura a través de los cambios de presión en el aire.

Magnetómetro: Sensor que permite saber hacia donde esta orientado el drone

Acelerómetro: Sensor que permite saber el angulo de inclinación que tiene el drone.

Giroscopio: Sensor que permite saber la velocidad a la que esta girando el drone.

Angle Mode: Es un modo en el que tienes asistencia de nivelacion con el horizonte.

Horizon Mode: Es un modo similar a angle mode, pero que permite hacer giros de 360°.

Acro Mode: Es un modo de vuelo en el que no tienes asistencia, el cual permite movimientos avanzados.

Airmode: No es un "modo", es una función que te permite tener control de tu drone aun cuando tu acelerador esta en la mínima potencia.

### Receptor
Telemetría: Es información que tiene tu controladora de vuelo que puede ser enviada al usuario a través de tu mando o tu OSD.

RSSI: Esta es la intensidad con la que la señal de tu mando llega a tu receptor, generalmente cuando esta en un valor de 40 ya estas próximo a perder la señal.

FrSky: Es el protocolo utilizado por FrSky o Taranis. Es de los mas confiables y populares.

2.4Ghz: Es la frecuencia a la que operan normalmente los mandos y receptores.

900Mhz: Es la frecuencia a la cual operan los mandos y receptores de larga distancia.

### Variador
ESC: Conocidos en español como variadores, son los componentes que traducen la señal de comando de tu controladora de vuelo a movimiento en tus motores.

SimonK: Este es un firmware antiguo de los ESC... ya es obsoleto asi que no compres ESC con este firmware.

BLHeli_S: Este firmware es open source y generalmente tiene lo ultimo en programación.

BLHeli_32: Este firmware es gratis para el usuario, pero cuesta para el que lo manufactura por lo que es un poco mas costoso. Tardan mas tiempo en traer funciones que en BLHeli_S, pero tiene mayor potencial, por lo que pronto sera el lider en el mercado.

BEC: Incluyen un regulador de voltaje para conectar tu controladora de vuelo. Esto ya no se utiliza hoy en día.

UBEC: Incluyen un regulador de voltaje para conectar tu controladora de vuelo. Esto ya no se utiliza hoy en día.

OPTO: No incluyen regulador de voltaje, esto es lo que mas se utiliza hoy en dia.

4 in 1: Este tipo contiene los 4 ESC's que normalmente utilizas en un solo circuito.

DSHOT: Es un protocolo de comunicación entre tu FC y tu ESC. Es el más popular y el que recomiendo ya que tiene un alta velocidad, fidelidad y permite comandos especiales como anti-turtle.

Multishot: Es un protocolo de comunicación entre tu FC y tu ESC igual de bueno y rápido que DSHOT, pero no permite comandos especiales.

OneShot: Un protocolo de comunicación entre tu FC y tu ESC, rápido pero que ya quedo obsoleto.

PWM: Un protocolo de comunicación entre tu FC y tu ESC lento que ya esta obsoleto.

 

### Transmisor de video
VTX: Este es el componente que transmite tu señal de video, normalmente transmite en 5.8 Ghz.

Antena linear: Estas son las antenas que solo son un palo, son las peores y no debes usarlas.

Antena de champiñon: Es una antena que te da buena señal en todas las direcciones, este tipo es el que debes usar.

Antena clover: Es una antena que te da buena señal en todas las direcciones, este tipo es el que debes usar.

Antena omnidireccional: Es una antena que recibe buena señal en todas las direcciones, este tipo es el que debes usar.

Antena stubby: Es una antena omni direccional pequeña, no tiene tanto alcance pero por el peso es muy popular en drones de carreras.

Antena pagoda: Es una antena omni direccional mediana. Tiene buen alcance y bajo tamaño y peso. Es muy popular en carreras y freestyle.

Antena Lollipop: Esta antena tiene lo mejor de todos los mundos, es pequeña como una stubby, pero su recepcion es similar a la de una pagoda, por lo que es la preferida de muchos y esta creciendo en popularidad.

RHCP: Antena de video con polarización derecha.

LHCP: Antena de video con polarización izquierda.

DB o DBi: Esto muestra que tan sensible es el equipo a recibir la señal. Entre mas grande sea el numero, mejor. Hay sus excepciones pero una antena de 1.5 db tiene "mala" recepción. Una antena entre 2 y 2.4 tiene buena recepción. Una antena arriba de 2.4 db tiene muy buena recepción.

### Cámara
FOV: Este valor te dice cuantos grados puedes ver, normalmente se mide en diagonal, sin embargo a veces te dan este valor horizontal y vertical.

4:3 Esta es la proporción en la cual obtienes la imagen. Esta proporción es similar a la que había en las televisiones antiguas o una fotografía.

16:9 Esta proporción es similar a la que tenemos en una pantalla de televisión o celular.

CMOS: Este es un tipo de sensor para la cámara, normalmente tienen mejor imagen, pero tienen mayor lag.

CCD: Este tipo de sensor para cámara, normalmente tiene una imagen de menor calidad pero tienen menor lag.

TVL: Dado que las cámaras son análogas, no tienen una resolución en pixeles, el equivalente son los TVL's por lo que a mayor cantidad de TVL's, mejor resolución.

WDR: Wide dynamic range es un algoritmo que ayuda a manejar los cambios de luz, de tal manera que puedes ver a detalle objetos oscuros y muy luminosos.

PAL: Es el estandar europeo de imagen análoga.

NTSC: Es el estandar americano de imagen análoga.

### Gafas
Gafas de caja: Estas gafas normalmente son las más baratas, inmersivas y grandes, si ves bien de cerca, estas no requerirán modificación para corregir la vista.

Gafas de cyclope: Otra forma de llamar a las gafas de caja.

Goggles: Estas gafas normalmente son las mas compactas, caras y populares. Si ves bien de lejos, estas no requerirán modificación para corregir la vista.

DVR: Esta función permite grabar el video que te llega a tus gafas. Sirve para tener video de lo que vuelas con baja resolución, puede ayudarte a encontrar un drone después de un choque.

Diversity: Es un sistema popular que permite conectar 2 antenas y recibir solo la señal que tenga la mejor claridad. 

18650: Este es un tipo de batería de litio que también puedes encontrar en las laptops, normalmente es la que se utiliza para dar energía a las gafas.

FOV: Revisa en cámara para mas información.

FPV: Estas son las siglas en ingles para Vista de Primera Persona, en nuestro caso usar los lentes para ver lo que ve el drone con su cámara.

Video In: Permite meter video a tus gafas de algún modulo externo o torre.

Video Out: Permite sacar la señal de video de tus gafas hacia algún otro dispositivo como un DVR o televisión.

HDMI: Permite mandar video a tu señal por medio de HDMI, esto sirve para entrenar con algún simulador.

Audio: Permite sacar el audio que te envía tu cámara hacia algún auricular. 

Antena omni direccional: Revisa en vtx para mas información.

Aantena de parche: Es una antena especial que tiene mayor amplificación de señal, entre 8db y 15 db. Lo cual te da mayor alcance y mejor claridad, pero generalmente solo funcionan en cierto ángulo.

HD: Las gafas HD normalmente tienen una resolución de 720p.

Full HD: Las gafas full HD normalmente tienen una resolucion de 1080p.

 

### Motores
Motor.jpg
1806, 2205,2206,2207,2305,2306, etc... Este es el tamaño del motor. Los primeros 2 numeros nos dicen el diámetro del motor y los ultimos 2 la altura de los imanes.

2300kv, 2400kv 2450kv, 2500kv, 2600kv,2700kv, etc... Estos nos dicen a cuantas revoluciones van a llegar nuestros motores. Generalmente se multiplica este valor por el voltaje que se tiene para obtener dicho valor.

KV: Normalmente confundido por kilo volts, este valor nos dice cuantos RPMs tenemos por cada Volt que pongamos en el motor.

Brushless / Sin escobillas: Este es el tipo de motor mas popular utilizado, ya que no sufren desgaste y tienen mayor control. Al no tener escobillas de grafito, tienen una larga vida.

Brushed / DC motor / Motor de corriente directa: Este es el tipo de motor que podemos encontrar en drones de bajo costo o de un tamaño muy pequeño. Se desgastan y tienen que ser reemplazados con regularidad. 

N48, N52, N52H, etc... Este es el tipo de imán que se esta utilizando, generalmente se pensaba un valor mas alto, significa mas potencia, pero recientemente eso ya no aplica. 

Amps: Estos nos dicen cuanta corriente consumen los motores.

Hollow Shaft / Eje hueco: Significa que el eje central esta hueco, lo cual ahorra algo de peso.

Pantless / sin pantalones: Significa que tienen una base abierta y por esa razón tienen mejor flujo de aire a través del sistema y por consiguiente regulan mejor su temperatura.

CW: Significa que giran a favor de las manecillas del reloj y por consiguiente la rosca de la tuerca esta de acuerdo a ese giro. (No significa que solo puedan girar hacia ese lado, pueden girar en ambas direcciones)

CCW: Significa que giran a en contra de las manecillas del reloj y por consiguiente la rosca de la tuerca esta de acuerdo a ese giro. (No significa que solo puedan girar hacia ese lado, pueden girar en ambas direcciones)

EZO / NSK /SKF: Son marcas de baleros disponibles en muchos motores. Todas ellas son de buena calidad.

### Hélices
Pitch: Esto muestra que tanto angulo tiene la hélice, generalmente entre mas ángulo tiene la hélice, mayor potencia genera y mas corriente consume.

Bullnose: Significa que tienen la punta chata, generalmente resisten mejor los golpes y generan más potencia, pero son mas ineficientes y pesadas.

Cyclone: Son hélices con punta fina y que tienen un perfil cambiante a través de la hélice, suelen ser las hélices mas potentes y con mayor eficiencia, pero también son algo pesadas.

PC: Cuando indica este material, están usando policarbonato, este es de los materiales mas durables que hay en las hélices.

PC+GF: Este material es policarbonato mas fibra de vidrio, suelen ser hélices durables y rígidas.

### Software
BetaFlight: El software más popular para tu controladora de vuelo, ya que es open source y contiene algunas de las funciones mas avanzadas del mercado.

RaceFlight: Uno de los mejores softwares para tu controladora de vuelo, esta es de paga y solo pocos pueden hacer hardware para dicho software. 

KISS: Un buen software para tu controladora de vuelo, es de paga y pocos pueden hacer hardware para dicho software, es el más fácil de configurar pero tienes limitaciones de compatibilidad con otros componentes.

CleanFlight: Una versión obsoleta de lo que ahora es BetaFlight.

Libre Pilot: Un software obsoleto que se llegaba a usar en CC3D y Naze32.

Open Pilot: Un software obsoleto que se llegaba a usar en CC3D y Naze32

Bootloader / Boot: Es el modo en el cual tienes que poner una controladora de vuelo para cambiar el Firmware que tiene instalado.

PID: Es un control que puede ser ajustado por medio de cambios en valor a la P(Proporcional), I (Integral) y D (Derivada), lo cual permite un mejor vuelo y menos vibración.

TPA: Es un valor que atenúa los PIDs, para que sean menos agresivos a partir de cierto valor del acelerador.

Anti-gravity: Es un valor que te permite disminuir un cambio de posicion que sucede cuando pones tu acelerador al máximo.

Anti turtle: Es un comando que requiere BLHeli y Dshot que permite voltear tu drone cuando esta de cabeza.

Notch Filter: Es un tipo de filtro que solo aplica en ciertas frecuencias específicadas por el usuario.

FIR / Low pass / Pt1 / Biquad / Pasa Bajos: Es un filtro que elimina frecuencias que se encuentren arriba del valor especificado.

Dinamic Filter: Es un filtro dinámico que funciona similar a un notch filter, pero se ajusta dependiendo de el ruido que reciba de tus motores.

Kalman: Un tipo de filtro similar a un pasa bajos, pero que puede tener funciones avanzadas como auto aprendizaje.

BlackBox: Es una caja negra y lo que permite es grabar datos de tu drone para luego ser analizados.

### Mando
Joystick / Palanca: Esta es la entrada que controla tu drone, cada joystick son 2 canales. En total usamos 4 canales para controlar Pitch, Roll, Yaw, Throttle.

FailSafe: Esta es un ajuste que permite dar instrucciones a tu drone una vez que pierde la señal. Recomiendo que al perder la señal se apaguen los motores para evitar que se vaya el drone y dañes algo.

Trim: Este permite cambiar tanto el limite superior o inferior de algun joystick y boton. De modo que en los extremos te de menos movimiento o mas, dependiendo de lo que quieras hacer.

SubTrim: Ajusta el centro de tu joystick. A veces el joystick no funciona bien o algo sucede que al poner el joystick en el centro, recibe señal como si estuviera hacia algún lado. Con esta función puedes corregir ese desajuste.

Mode / Modo: El modo se refiere a donde esta cada movimiento en el joystick, el mas popular es el modo 2, sin embargo el Mode 3 se asemeja a lo que estamos acostumbrados en los videojuegos.

Dead Band: Es una zona, que normalmente defines al centro del joystick en la que va a mandar la misma señal aun que te muevas un poco. Esto se usa normalmente cuando tu joystick ya esta algo antiguo y tiene juego.

Arm / Armado: Esta es la acción de habilitar el drone para volar. Es una medida de seguridad para evitar que el drone te pegue y haya accidentes.

Strap: Es la correa que se pone en la mayoría de los mandos para ayudar a soportar el peso con tu cuello.

Channel / Canal: Es la capacidad de mandar informacion de algun boton o joystick. Generalmente cada joystick utiliza 2 canales y cada boton utiliza 1 canal.

### Baterias
Bateria.jpg
LiPo: Es un tipo de bateria basada en litio con polimero. Es lo más utilizado en drones ya que tienen un alta capacidad de carga relativa a su peso y permiten descargas de corriente muy altas.

C: Se utiliza la C como una base para saber a que corriente puedes cargar/ descargar una bateria. O cuanta corriente te puede dar en algun punto la bateria cuando demandes energia de ella, dependiendo de la corriente de tu bateria.

Por ejemplo:

Una bateria de 4S de 1300mah, 70C que puede ser cargada a 5C y tiene una descarga pico de 140C

Cuando cargas: Maxima carga 5 C, por lo tanto 1300mah x 5C = 6500mah = 6.5A por ello puedes cargar tu bateria a 6.5 Amperes
Cuando le exiges energía: Como son 70C = 1300mah x 70C = 91,000 mah = 91A, por ello puedes consumir 91A de manera continua.
Cuando le sobre exiges energía: Como son 140C = 1300mah x 140C mah = 182,000 mah = 182 A, por ello puedes consumir 182 A durante 3 segundos sin dañar tu batería.
S: Nos dice la cantidad de celdas que tiene una batería. Normalmente una celda puede ser cargada a 4.2V, y se descarga a 3.7V. Por ello si una bateria es 1s = 3.7V, 2s = 7.4V, 3s = 11.1V y 4s = 14.8V.

LiPo Graphene: Es una variación de las baterías de LiPo normal, supuesta mente permiten mayor descarga, sin embargo parece ser mas un gimmick que algo real.

Discharge Rate / Ritmo de descarga: Nos dice que tanta corriente puede ser descargada de la batería de manera continua y sin daño.

Burst Discharge Rate /  Ritmo de descarga pico: Nos dice el pico de corriente que puede descargar la batería por menos de 3 segundos sin daño.

XT60: Es el tipo de conector estándar que tienen las baterías para ser usadas

Puerto de balanceo: Es un conector secundario que tienen las baterías para poder cargar las celdas individualmente y asegurar que no haya problemas de sobre voltaje.

Balanced Charge / Carga balanceada: Esta es la forma en que debes cargar tu batería para evitar que alguna celda sea cargada a un valor mayor de su diseño, lo cual puede resultar en fuego, humo y/o explosión.

Voltaje de almacenamiento: Es el voltaje al cual tienen que ser cargadas/descargadas las baterias para evitar daño cuando no se usan por largo tiempo. Este voltaje es igual a 3.8V o 3.85V por celda.

### Antenas
SMA Macho: Este connector trae tuerca externa y un pin en la parte interna.

SMA Hembra: Este conector trae rosca externa y socket en la parte interna.

RP-SMA Macho: Este conector trae tuerca externa y socket en la parte interna.

RP-SMA Hembra: Este conector trae rosca externa y un pin en la parte interna.

Connectores.png
### Otros términos
Cabeceoguinada.jpg
Pitch / Cabeceo: Giro hacia adelante o hacia atrás, como si dijeras SI con la cabeza.

Roll / Alabeo: Inclinación hacia la derecha o la izquierda, como si intentaras tocar tus hombros con tus orejas.

Yaw / Guiñada Giro sobre el eje, como si dijeras NO con la cabeza.

Throttle / Acelerador: Cuanta potencia tienen tus motores.

Freestyle: Es el estilo de vuelo de drones en el cual generalmente se hacen trucos.

Carreras: Funciona igual que cualquier otra carrera, generalmente se vuela a través de un circuito pre diseñado.

Telemetría: Es información que tiene tu controladora de vuelo que puede ser enviada al usuario a través de tu mando o tu OSD.

RSSI: Esta es la intensidad con la que la señal de tu mando llega a tu receptor, generalmente cuando esta en un valor de 40 ya estas próximo a perder la señal.

FrSky: Es el protocolo utilizado por FrSky o Taranis. Es de los mas confiables y populares.

2.4Ghz: Es la frecuencia a la que operan normalmente los mandos y receptores.

900Mhz: Es la frecuencia a la cual operan los mandos y receptores de larga distancia.

#### Fuentes de información 

[QuadMx Drones] http://www.quadmx.com/diccionario/   

[Airbender_FPV] https://www.instagram.com/airbender_fpv/




