#### [0.1.45] - 2023-12-19 6:30 GMT

Nuevo botón [Web3Modal](https://web3modal.com/) para autenticación y desaprobación temporal del Web3Button en favor del modal para interactuar con contratos inteligentes.
![Web3Modal](https://i.ibb.co/Zx07dCW/web3modal.png)
##### Agregado
- Nuevo botón de conexión de billetera
- Nueva documentación (WIP) disponible para cada componente y accesible a través del modal del editor de componentes (icono de información)

##### Cambió
- Webstudio SDK ahora usa ethers 6.9.0 y web3modal 3.4.0
- El formulario Web3 ahora permite cargar ABI y seleccionar el método para interactuar mediante el menú desplegable, en lugar de copiar y pegar el abi json y el nombre del método.

##### Corregido
- Iniciar sesión con Wallet Connect

##### Eliminado
- Web3Button eliminado temporalmente. Nos centraremos en componentes más específicos como las galerías y tiendas NFT.

#### [0.1.41] - 2023-11-28 12:21 GMT

¡Ahora puedes copiar y pegar páginas de tu proyecto con la funcionalidad del portapapeles! ¡Deje que desee clonar una página existente o duplicar un encabezado o una sección en varias páginas! 1. Seleccione su componente, 2. Copie al portapapeles, 3. Seleccione un componente de destino y péguelo desde el portapapeles.
![Portapapeles](https://i.ibb.co/yh522Wv/Clipboard.png, "Portapapeles") 
##### Adiciones
- [Portapapeles](https://twitter.com/webstudioso/status/1729472757581185305). Ahora puedes copiar y pegar entre páginas de tu proyecto con la función del portapapeles. Simplemente seleccione su elemento (podría ser una página completa), cópielo al portapapeles, seleccione un componente de destino y haga clic en pegar desde el portapapeles.
- Nueva plantilla "Wellness"
##### Cambios
- Iconografía de la barra de herramientas

#### [0.1.38] - 2023-11-24 15:20 GMT

El administrador de estilos se ha ampliado a todos los componentes y también hemos agregado un nuevo "Modo de diseñador" que le permite alternar entre una construcción fácil que responde a dispositivos móviles de forma predeterminada o un posicionamiento personalizado de los componentes configurados manualmente para todos los dispositivos para una mayor personalización.
![Administrador de Estilos](https://i.ibb.co/3kyytDG/StyleM.png, "Administrador de Estilos") 
##### Adiciones
- [Administrador de Estilos](https://twitter.com/webstudioso/status/1728094961868976334). Edite los atributos visuales de todos sus componentes de una manera sencilla y tenga la flexibilidad de especificar clases tailwindcss y animatecss individualmente.
- [Modo Diseñador](https://twitter.com/webstudioso/status/1728100810104664494). La nueva opción del Modo Diseñador le permite crear sitios adaptables para dispositivos móviles de forma predeterminada en función de la cuadrícula de la plantilla. ¡También puede cambiar al modo Manual para mover componentes libremente a cualquier lugar de la pantalla para cualquier resolución de dispositivo!
- Nueva plantilla "ETHDublin"
- El administrador de estilos ahora admite sombras, imágenes de fondo, formas de bordes, colores y relleno.
##### Cambios
- Imágenes en miniatura fijas para los tipos de contrato de botones Web3 disponibles

#### [0.1.35] - 2023-10-23 14:00 GMT

Nuevo editor de bordes que permite de manera visual seleccionar los tipos de bordes para componentes de texto, pronto disponible en otros tipos de componentes.
!["Editor de bordes](https://i.ibb.co/Sy7MXF1/Border-Radius.gif, "Editor de bordes") 
#### [0.1.32] - 2023-09-04 09:20 GMT

🚀 Ahora mover items en el canvas es mas facil que nunca. Anteriormente posicionar elementos en el canvas debia respetar la grilla de los componentes padres. Ahora cada elemento puede ser movido a cualquier lugar.
!["Drag and Drop and Style Manager](https://i.ibb.co/fpgs17S/Anim.png, "Drag and Drop and Style Manager") 
##### Adiciones
- ["Drag and Drop and Style Manager](https://twitter.com/webstudioso/status/1698613369098354921). Poder posicionar elementos en cualquier lugar del canvas otorga la libertad de generar cualquier estilo visual.
- Manejador de estilos (Componente de texto). Al hacer click derecho sobre un componente de texto se abrira el manejador de estilo que permite cambiar la fuente, tamano, agregar links y animaciones, entre otras cosas a cualquier componente de texto.
- Funcionalidad para "traer al frente" o "moveral fondo" componentes que se sobrelapen
- Animate CSS nuevas animaciones
- Nueva forma para agregar links a texto
##### Removido
- Las plantillas Prima Persona y Streamer fueron eliminadas debido a problemas con licencia.
##### Cambios
- Cualquier elemento puede ser movido a cualquier parte del canvas

#### [0.1.31] - 2023-07-19 15:30 GMT

🚀 Disponible hoy, Studio AI manejador de plantillas. Construye sitios web simplemente describiendolos, sin necesidad de codigo. 
![Studio AI Preview](https://i.ibb.co/kmhkHVB/Screenshot-2023-07-28-162617.png, "Studio AI Preview") 
##### Added
- [Studio AI Preview](https://twitter.com/webstudioso/status/1684894684819107840). Observa el demo de como funciona Studio AI para crear sitios web usando ChatGPT. 
 
##### Changed
- Studio AI esta disponible en el plan gratuito
- Todos los modulos de Web3 estan disponible en el plan gratuito


[Title](CHANGELOG_en.md) [Title](CHANGELOG_es.md)
#### [0.1.29] - 2023-07-14 9:55 GMT

Cambia las imagenes de fondo de cualquier componente.

![Fondo](https://i.ibb.co/6bZtkXd/Untitled.png, "Fondo") 
##### Added
- [Imagen de Fondo](https://github.com/orgs/webstudioso/projects/1/views/1?pane=issue&itemId=33281542) Para cambiar la imagen de fondo de cualquier componente en tu proyecto, selecciona el componente y abre la seccion de media para seleccionar una image. Al seleccionarla, reemplazara la imagen de fondo de tu componente seleccionado. Para ajustar la configuracion haz click en el boton de editar para el componente, y baja a la seccion de Decoration > background. [Aqui tienes un tutorial paso a paso](https://twitter.com/webstudioso/status/1679784701832118273)
 

#### [0.1.28] - 2023-07-03 14:45 GMT

Presentando la "Bitacora". Un nuevo feature de Webstudio que despliega una ventana emergente con informacion relevante para los usuarios con respecto a nuevos features lanzados, correccion de errores y traza de eventos en la plataforma.  
![Changelog](https://i.ibb.co/jzRsz2T/Screenshot-2023-07-03-at-14-22-59.png, "Changelog") 
##### Nuevo
- [Ventana de Bitacora](https://github.com/orgs/webstudioso/projects/1?pane=issue&itemId=30367337) Obten notificaciones de nuevos lanzamientos y cambios en Webstudio, justo cuando los realizamos.  
 
##### Cambios
- Incrementamos parcialmente las pruebas unitarias automaticas

