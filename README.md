# **TRABAJO PRACTICO N° 1**

## Alummos: Pinto Marisol, Donaire Marisol
## Profe: Rosales Rene

## **Fundamento y Ecosistemas del Desarrollo Móvil** <br><br>

### Android y Apple

![Android y Apple](C:/Users/edwin/Documents/Año 2026/POO/Android y Apple.png)


1. ¿Cuáles son los principales sistemas operativos para dispositivos móviles en la actualidad? <br><br>
 Los principales sistemas operativos móviles actuales son :
 * **Android** destacado por su por su código abierto y diversidad de fabricantes como por ejemplo Samsung, Xiaomi. Es utilizado por la mayoría de las marcas de teléfonos inteligentes y tabletas.<br><br>
 * **IOS** Sistema exclusivo de Apple. Conocido por su ecosistema cerrado, alto rendimiento, seguridad y actualizaciones rápidas. <br><br>
   
2. ¿Cuáles son las principales diferencias técnicas entre el desarrollo  nativo para iOS y para Android en la actualidad?
<br><br>
## Diferencia entre Andrpid y IOS es: <br><br>
 
 | CARACTERISTICA | IOS | ANDROID     
 ---------------- |:----- |:----------| 
 |**Lenguaje**| Swift (o objetive-C)|kotlin (java)|
 |**Entorno (IDE)**| Xcode| Android studio|
 |**Sistema Operativo**|unicamente macOS|Windows, macOS O Linux|
 |**Distribucion**| Apple App Store| Google Play Store
---------------------------------------

3. ¿A qué nos referimos cuando hablamos de desarrollo nativo en programación de APP móviles? ¿Qué ventajas ofrece sobre el desarrollo multiplataforma?<br><br>
 **El Desarrollo Nativo** consiste en crear una aplicacion especifica para un sistema operativo utilizando los lenguajes y herramientas oficiales del fabricante (como Swift para IOS O Kotlin para android)<br>
<br>
*Ventajas del desarrollo nativo sobre el multiplataforma*<br>
+ **Rendimiento superior**: al no tener capas intermedias, la ejecucion es mas fluida y rapida<br>
+ **Acceso total al hardware** : Permite aprovechar al maximo snesores, camara, GPS y las ultimas funciones del sistema de forma inmediata<br>
+ **Mejor Experiencia de Usuario(UX)** : Las inerfaces se sienten naturales y coherentes con el resto del sistema operativo.
+ **Seguridad** : Suelen ser mas robustas al seguir los estandares directos del fabricantes. <br><br>
4. ¿Qué ventaja principal ofrece Framework Multiplataforma (como Flutter o React Native) frente  al desarrollo nativo?<br><br>
   ### **Multiplataforma vs Nativo** 
   |**Importancia** | **Frameworks multiplataforma (Flutter/RN)** |	**Desarrollo Nativo (Swift/Kotlin)** 
   --------------------| :-------------------| :-------------|
   |**Código Base**| Único para iOS y Android|Separado (uno por plataforma)|
   |**Tiempo de Desarrollo**| XcodeRápido (recarga rápida)| Más lento(dos equipos)|
   |**Costo**|Menor (menos recursos)|Alto (mantenimiento doble)|
   |**Rendimiento**| Muy alto (casi nativo)|  Máximo nivel posible	 
   |**Interfaz (UI)** |	Consistente/Idéntica |	Nativa por plataforma
   |**Acceso a API Nativa** |	Bueno, pero requiere puentes | Acceso directo e inmediato
--------------------------------------------
5. En el contexto arquitectura movil ¿Cual es la funcion de una API REST importa el sistema operativo desde el cual se consma la API o es indistinto?
#### Una API REST <br><br>
Una API REST es una interfaz de programación de aplicaciones ( API ) que se ajusta a los principios de diseño del estilo arquitectónico de transferencia de estado representacional ( REST ), un estilo utilizado para conectar sistemas hipermedia distribuidos.
##### Funciona de la siguiente manera (componentes)
* Arquitectura Cliente-Servidor: Separa el front-end (cliente) del back-end (servidor), lo que permite escalabilidad.
* Protocolo HTTP: Utiliza los verbos estándar de la web para interactuar con los recursos:
* GET: Recupera información.
* POST: Crea un nuevo recurso.
* PUT/PATCH: Actualiza un recurso existente.
* DELETE: Eliminar un recurso <br><br>
_A una API REST no le importa qué sistema operativo utiliza (Windows, Linux, macOS, Android, iOS), siempre y cuando el cliente pueda enviar una solicitud HTTP_