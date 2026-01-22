---
tags:
  - Redes
  - Cableado
  - UTP
  - FO
---

Para seleccionar el cable de par trenzado y de fibra óptica, debe considerarse el cableado horizontal que va de los sitios de trabajo hasta el patch pannel en el bastidor de telecomunicaciones y el cableado vertical de fibra óptica que interconecta los distribuidores en los diferentes pisos.  

- El cableado horizontal **normalmente es cobre (UTP/STP)**
- El cableado vertical **normalmente es fibra óptica**, por distancia y capacidad

### Cable de par trenzado

Los pares se **trenzan para cancelar interferencias electromagnéticas (EMI)** y reducir el ruido entre pares (crosstalk).

 Se usan cables de 4 pares:

- **UTP:** Sin blindaje, es común por su bajo costo y fácil instalación. A altas velocidades puede resultar vulnerable a interferencias del medio ambiente, para su terminación se usan conectores RJ-45
- **FTP:** Sus pares no están apantallados, pero contiene una pantalla metálica que envuelve los 4 pares para mejorar su protección a  interferencias externas. Posee propiedades de transmisión parecidas a las del UTP y usa los mismos conectores RJ-45
- **STP(par trenzado con blindaje):** Cada par tiene una cubierta de malla protectora para evitar interferencias externas, es más seguro pero el cable se vuelve más robusto y difícil de instalar. Debe conectarse a tierra física y conectores RJ-49, usado cerca de fuertes interferencias externas como tendidos eléctricos.

### Selección de cable UTP

Se consideran las categorías existentes, que se diferencias según la cantidad de torción que se tenga en el trenzado y la velocidad de transferencia. Categorías y uso:

- CAT 03: Datos hasta 10Mbps, muy usado. **No se usa actualmente**
- CAT 05: Datos hasta 100Mbps, usado en redes LAN de edificios corporativos. **No se usa actualmente**
- CAT 05e: Datos hasta 1000Mbps
- CAT 06: Hasta 1Gbps
- CAT 06a: 10Gbps

### Tipos de fibras

El uso de fibra óptica resuelve problemas ligados al medio ambiente pues es inmune a las perturbaciones electromagnéticas, además de su baja atenuación y a su ancho de banda. Permite transmitir información con seguridad, sus tipos son:

- Fibra Multimodo: Tiene un núcleo de mayor diámetro por donde pueden viajar más rayos de luz, tiene más atenuación por kilómetro.
- Fibra Monomodo: Núcleo menor, donde solo puede viajar un rayo de luz, pero tiene menor atenuación ya que usa un láser muy estable.

En distancias menores a 2 mil metros se usa fibra multimodo ya que los componentes necesarios son más económicos. El tipo de fibra óptica más utilizado es el de 65.5 125 micrómetros en núcleo y revestimiento.

El cable para instalaciones verticales debe ser cubierta de pvc, color gris antiflama para utilización en interiores y con fibras multimodo de índice gradual de 62.5 125 para longitudes de onda de 850 nanómetros y 1310 nanómetros. 

![image.png](a6393bfb-a7cb-4618-81a1-896907b094b0.png)

Cable interior-exterior, se usa en enlaces entre edificios de una empresa cuando se encuentran a menos de 2mil metros, se usa el cable antiflamas con fibra multimodo, se puede tender hasta los distribuidores de fibra óptica. En caso de usar cable para uso exterior en los enlaces en los edificios, se debe realizar el cambio de cable. 

![image.png](2d2fa411-0ee8-404f-b1ad-b198fabcf7f1.png)

Para enlaces mayores a 2miol metros, se debe usar el cable de fibras monomodo de dispersión normal, el cual proporciona mejor alcance.

### Jumper Óptico o cordón de Parcheo de Fibra óptica

Se usan para la interconexión entre los distribuidores de fibra óptica y los equipos de telecomunicaciones. El cordón de parcheo debe ser del mismo tipo de fibra utilizado en el cableado vertical. 

![[a6393bfb-a7cb-4618-81a1-896907b094b0.png]]

