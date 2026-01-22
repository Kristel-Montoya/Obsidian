### Instalaciones de Entrada
Para comunicar 2 o más edificios de la misma empresa usando cables de fibra óptica, se requiere canalización subterránea o tendido aéreo por postes o muros. Una instalación de entrada es el lugar en el que entran los servicios de telecomunicaciones al edificio. En la norma ANSI TIA EIA 569 se recomiendan las instalaciones subterráneas y aéreas para las instalaciones de entrada. 

Una canalización subterránea consiste en un sistema de ductos y cámaras de inspección para la inmersión de los cables de fibra óptica. Cuando no se cuenta con la estructura para esto, se realiza la instalación aérea soportada en postes o muros. Los cables empleados para las acometidas tienen una capacidad de 6 o 12 fibras ópticas. 

### Inmersión subterránea
Se necesitan las siguientes herramientas
- Guía o cobra para cableado subterráneo
- Guía de acero
- Rafia 
- Eslabón
- Des-torcedor
- Lubricante 
- Hidrogel 

Para la instalación se debe:
- Ubicar la bobina de fibra óptica en el trayecto asignado 
- Alambrar la vía mediante la inmersión de la cobra por los pozos proyectados
- Amarrar una soga o rafia a la punta de la cobra 
- Jalar la rafia con la cobra para dejarla inmersa en todos los pozos
- Amarrar la rafia al cable
- Ubicar un técnico en cada pozo para jalar el cable una vez este esté lubricado
- Jalar el cable hasta dejar suficiente en cada extremo, hacer un rollo de cable en cada extremo 
- Fijar e identificar el cable en los pozos. 

### Tendido del cable de cometida en el interior del edificio 
Cuando se tiene el rollo de cable, la siguiente misión es tender el cable en las canalizaciones hasta los bastidores, para esto se debe:
1. Distribuir técnicos a lo largo de la trayectoria de la fibra óptica dentro del edificio.
2. Guiar el cable hasta el bastidor de remate de la F.O
3. Tender el cable en las canalizaciones exclusivas para la F.O
4. Asegurar que el radio de curvatura sea mayor de 35 mm cuando haya un giro en la trayectoria, para evitar micro dobleses y atenuación excesiva 
5. Verificar que en trayectos muy largos hayan puntos de retoma de fibra óptica, registros de jalado, para disminuir la fuerza de tracción sobre el cable
6. Tender el cable hasta los puntos de remate de los bastidores de telecomunicaciones
7. Fijar el cable en tendidos verticales a cada 40 cm y en las rutas horizontales cada 7 m
8. Dejar cable suficiente en el punto de remate para la terminación del cable de F.O en las repisas de distribución

### Cableado Vertical
Se utilizan dentro del edificio para interconectar los bastidores de telecomunicaciones y los cuartos de equipo. Los ductos y canalizaciones para este deben protegerse adecuadamente ya que se puede dañar 

El procedimiento para su tendido es el siguiente:
1. Distribuir técnicos a lo largo de la trayectoria de la F.O, dentro del edificio
2. Guiar el cable de un punto de remate a otro
3. Tender el cable en las canalizaciones exclusivas para la F.O
4. Asegurar un radio de curvatura mayor de 35 mm cuando haya un giro en su trayectoria
5. Verificar que en distancias largas, existan puntos de retoma de fibra óptica
6. Tender el cable hasta los puntos de remate
7. Fijar el cable en tendidos verticales a cada 40 cm y en las rutas horizontales cada 7 m
8. Dejar cable suficiente en el punto de remate para la terminación del cable de F.O en las repisas de distribución


### <mark style="background: #D2B3FFA6;">Normativa TIA/EIA-568B</mark>

Se encarga de regular:
- EL orden de los colores dentro del cable
- Uso de pares trenzados 
- Compatibilidad entre dispositivos 

#### Normas básicas
- El cable no se estira con fuerza, ni se hacen dobleces bruscos
- No se debe aplastar cables con otros cables o estructuras
- Los ductos no deben llenarse al 100%
- Los cables se aseguran con bridas, pero no excesivamente apretados. 
- Cables de electricidad y datos no deben ir juntos
- Si deben cruzarse, que sea en ángulo de 90°

#### Orden de colores estándar 568B 
**El cable Ethernet**  tiene 8 hilos, organizado en 4 pares trenzados
Un conector RJ-45 debe llevar el siguiente orden en sus pares internos: 

![[Pasted image 20260121190605.png]]


**Que pasa si no se sigue el estándar?** 
- La red no conecta o lo hace a menor velocidad 
- Fallos difíciles de notar

#### Tipos de cables usados 
**De par trenzado:**
- UTP (Unshield twisted pair): No tiene blindaje, se usa en casa, aulas y oficinas
- FTP/STP (cable blindado): Tiene una malla metálica para reducir interferencia eléctrica, se usa en industrias y lugares con mucho ruido eléctrico.
**Por categoría** 
- Cat 5e: Hasta 1 Gbps 
- Cat 6/6A: más velocidad y menos inferencia

#### Tipos de canalización 
- En casas u oficinas: Ductos de pvc 
- En edificios grandes: Charolas metálicas en el techo 

#### Agrupación y etiquetas en las puntas de conexión 
Se agrupan por su función o área y terminan en Patch Panel o Jack RJ-45. Además, cada cable debe estar etiquetado e identificado en cada extremo 

#### Conexión a la tierra física
La tierra física no se conecta al cable UTP, se conecta a Racks, charolas metálicas, gabinetes, equipos activos... EL objetivo es descargar la electricidad estática, proteger equipos y evitar descargas eléctricas. El cable de red no va a la tierra, pero la estructura que lo sostiene sí 

