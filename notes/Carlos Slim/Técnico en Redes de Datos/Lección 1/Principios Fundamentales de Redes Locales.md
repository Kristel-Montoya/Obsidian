---
tags:
  - Redes
---
### LAN (Local Área Network)

Redes en áreas locales y bajo una misma administración. Esta red existe cuando dos o más dispositivos pueden enviarse información entre sí en una área pequeña. La información se envía dividida en paquetes de datos, que se re ensamblan en el destino. 

Debe tener:

- **Transmisor**
- **Medio** (cable trenzado, fibra óptica u ondas de radio)
- **Receptor**

Puntos Importantes:

- **Switch**: conecta varios dispositivos dentro de la LAN. Capa 2
- **Router**: conecta la LAN con otras redes (por ejemplo, Internet).
- **Dirección IP**: identifica de forma única a cada dispositivo dentro de la red.

Cuando la red es cableada, los transmisores y receptores se encuentran en la tarjeta de red 
(NIC), la cual permite la conexión mediante un **puerto Ethernet**.

### Modelo OSI (Open Systems Interconnection)

Es una arquitectura que divide la comunicación en 7 capas.

- **Capa 1 - Física:** Capa inferior, se encarga de la **transmisión y recepción de bits (0 y 1)** a través de un medio físico.
    - Cables (UTP, fibra óptica)
    - Conectores (RJ45)
    - Tarjeta de red (parte física)
    - Señales eléctricas, ópticas o de radio
    
- **Capa 2 – Enlace de Datos:** Usa direcciones físicas (MAC), que viene grabada en la tarjeta de red, se encarga de:
    - Encapsular los datos en **tramas**
    - Identificar dispositivos dentro de la **misma red local**
    - Controlar errores básicos
    - Gestionar el acceso al medio
      
- **Capa 3 – Red:**  La **capa de red** se encarga de **llevar los datos entre redes diferentes**. Aquí aparece:
    - **Dirección IP**
    - **Enrutamiento**
    - **Routers**
      
- **Capa 4 – Transporte:** Se asegura de que los datos lleguen **completos y en orden**.
    - TCP: confiable (web, correo)
    - UDP: rápido, sin confirmación (video, juegos)
      
- **Capa 5 - Sesión:**  Gestiona cuando inicia y termina la comunicación (mientras esté conectado)
  
- **Capa 6 - Presentación:**  Se encarga del formato de los datos:
    - Compresión
    - Cifrado
    - Codificación
      
- **Capa 7 - Aplicación:** Es la capa es más cercana al usuario, incluye
    - Navegador web
    - Correo electrónico
    - FTP, HTTP, DNS


> [!NOTE]
> El modelo OSI no describe una red real, sino una forma ordenada de entender cómo se comunican los datos.
> 
> - Capa 2 → **MAC, tramas, switch**
> - Capa 3 → **IP, paquetes, router**
> - Capa 1 → **señales y cables**
> - **MAC** → quién eres físicamente
> - **IP** → dónde estás en la red
> 

### TCP Orientado a Conexión

Protocolo usado para la conexión efectiva entre equipos. Antes de enviar datos, ambos dispositivos establecen una conexión formal. 
Trabaja en la capa 4 para:

- Controlar la entrega de los datos
- Dividirlos en segmentos
- Reordenarlos al llegar

- Detectar errores
- Solicitar retransmisión si algo se pierde

### Direccionamiento IP

Al conectar una computadora a la red, la dirección IP es asignada de forma estática o dinámica, según sea el diseño de la red, para identificar de forma lógica a cada dispositivo dentro de la red.

- Dinámica: Asignada de forma automática por un protocolo DHCP (Dynamic Host Configuration Protocol).
- Estática: Asignada de forma manual.

En redes medianas y grandes se utiliza un servidor DNS para asociar nombres (alias) a direcciones IP, permitiendo acceder a equipos y servidores mediante nombres fáciles de recordar en lugar de su dirección IP.

- **DHCP** → asigna IP
- **DNS** → traduce nombres
- **IP** → identifica al equipo
- 
### Red LAN de 2 Computadoras

Cuando dos dispositivos de red iguales se usa un cable CrossOver, donde se cruzan los **pares de transmisión y recepción** (TX ↔ RX) para establecer la conexión. Debe asignarse una dirección IP a cada nick. 

El cable crossover cruza los pares de transmisión y recepción para que:

- El transmisor de una computadora llegue al receptor de la otra.
- Y viceversa.

Hoy en día, **la mayoría de las tarjetas de red modernas** soportan una tecnología llamada **Auto-MDI/MDI-X**, que detecta automáticamente si deben cruzarse los pares.

**Configuración de IP**

1. Conexiones de red
2. Propiedades 
3. Funciones de red / protocolos de internet 4 / propiedades
4. Utilizar la siguiente dirección / IP / Máscara de subred (debe ser la misma)
5. Compartir archivos / configuración adicional