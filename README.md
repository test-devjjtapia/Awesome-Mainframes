# Awesome Mainframes [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) <!-- omit in toc -->
![system 360](media/320px-IBM_System360_Mainframe.jpg)

Lista Awesome de recursos y proyectos relacionados con mainframes.  

El público objetivo de esta lista son las personas interesadas en aprender sobre mainframes, con énfasis en el System/360 y sus descendientes.

Si te gustaría contribuir a esta lista, por favor envía un pull request. Si no estás familiarizado con los pull requests de git y solo quieres enviar una corrección menor o un enlace nuevo, simplemente abre un "issue" en GitHub. Esto garantizará que las contribuciones no se pasen por alto.

Esta lista está bajo licencia [CC0](https://creativecommons.org/publicdomain/zero/1.0/).

# Contenido <!-- omit in toc -->
- [Mainframes IBM System/360, System/370, System/390, z](#mainframes-ibm-system360-system370-system390-z)
  - [Primeros pasos](#primeros-pasos)
  - [General](#general)
  - [Emuladores](#emuladores)
  - [Front-ends GUI para Hercules](#front-ends-gui-para-hercules)
  - [Emuladores de terminal TN3270](#emuladores-de-terminal-tn3270)
    - [Información técnica de TN3270/3270](#información-técnica-de-tn32703270)
  - [Sistemas operativos](#sistemas-operativos)
    - [MVS](#mvs)
      - [Información de MVS](#información-de-mvs)
      - [Videos de MVS](#videos-de-mvs)
    - [VM/370](#vm370)
      - [Videos de VM/370](#videos-de-vm370)
    - [MUSIC/SP](#musicsp)
    - [Michigan Terminal System](#michigan-terminal-system)
    - [Linux](#linux)
    - [DOS/360](#dos360)
    - [DOS/VS](#dosvs)
    - [OS/360 MFT](#os360-mft)
    - [OS/360 MVT](#os360-mvt)
    - [TSS/370](#tss370)
  - [CICS](#cics)
  - [Lenguajes de programación](#lenguajes-de-programación)
    - [APL](#apl)
    - [Assembler](#assembler)
      - [Tutoriales / Cursos de Assembler](#tutoriales--cursos-de-assembler)
    - [BASIC](#basic)
    - [C](#c)
    - [CLIST](#clist)
    - [COBOL](#cobol)
      - [Tutoriales / Cursos de COBOL](#tutoriales--cursos-de-cobol)
      - [Videos de COBOL](#videos-de-cobol)
    - [JCL](#jcl)
    - [REXX](#rexx)
      - [Tutoriales / Cursos de REXX](#tutoriales--cursos-de-rexx)
  - [Canales de YouTube relacionados con mainframes](#canales-de-youtube-relacionados-con-mainframes)
  - [HNET / BITNET](#hnet--bitnet)
    - [Videos de HNET / BITNET](#videos-de-hnet--bitnet)
  - [Blogs de mainframes](#blogs-de-mainframes)
  - [Cursos](#cursos)
  - [Software gratuito u opensource para correr en tu mainframe](#software-gratuito-u-opensource-para-correr-en-tu-mainframe)
  - [Otras listas de enlaces](#otras-listas-de-enlaces)
  - [Comunidades / Foros / Listas de correo](#comunidades--foros--listas-de-correo)
    - [groups.io](#groupsio)
  - [Otros / Pendiente de categorizar](#otros--pendiente-de-categorizar)
- [Otros mainframes IBM (IBM 1401, 1620, 7090/7094, System 3)](#otros-mainframes-ibm-ibm-1401-1620-70907094-system-3)
  - [Emuladores](#emuladores-1)
  - [Software](#software)

# Mainframes IBM System/360, System/370, System/390, z

## Primeros pasos

## General
* [Línea de tiempo de sistemas operativos](https://webfiles.uci.edu/scosel/_$OSTL37.5.pdf) - "IBM Mainframe Operating Systems: Timeline and Brief Explanation For the IBM System/360 and Beyond" por Dave Morton. Enlace alterno: https://groups.io/g/hercules-os380/files/_$OSTL37.5.pdf ***NOTA:** Necesitarás unirte al grupo [hercules-os380](https://groups.io/g/hercules-os380/) antes de poder acceder a este documento desde el enlace alterno.*
* [Anuncio original del mainframe System/360](http://www.ljw.me.uk/ibm360/nix/360a.html) Históricamente significativo, ya que es el anuncio de marketing original del primer mainframe System/360.
* [The Open Mainframe Project](https://www.openmainframeproject.org/) - *"The Open Mainframe Project is intended to serve as a focal point for deployment and use of Linux and Open Source in a mainframe computing environment. The Project intends to increase collaboration across the mainframe community and to develop shared tool sets and resources. Furthermore, the Project seeks to involve the participation of academic institutions to assist in teaching and educating the mainframe engineers and developers of tomorrow."*
* [Colección de referencias rápidas de programación de mainframe IBM](http://ibmmainframes.com/references/)

## Emuladores
* [Hercules Spinhawk](https://github.com/rbowler/spinhawk) - Hercules 3.x - spinhawk es el repositorio de la versión de calidad de producción (release 3.xx) de la plataforma de virtualización de mainframes Hercules
* [Hercules Hyperion](https://github.com/hercules-390/hyperion) - La versión Hyperion de Hercules es la versión oficial de desarrollo del emulador Hercules y contiene los cambios más recientes (bleeding edge) hechos por los desarrolladores de Hercules para corregir varios bugs que puedan existir en la versión de producción.
* [SDL Hercules Hyperion](http://www.softdevlabs.com/hyperion.html) - [(github)](https://github.com/SDL-Hercules-390/hyperion) Versión de SoftDevLabs (SDL) de Hercules 4.x 
  * [Instalar SDL Hyperion](https://geronimo370.nl/s370/hercules-installing/installing-sdl-hyperion/) - Tutorial de Gerrard Wassink para compilar e instalar SDL Hercules Hyperion en varias arquitecturas.
  * [Compila la versión más reciente de Hercules desde el código fuente - M82](https://www.youtube.com/watch?v=ZJI5v3-zEww&feature=youtu.be) (YOUTUBE) - Video de [Moshix](https://github.com/moshix) demostrando cómo compilar la versión más reciente de Hercules desde el código fuente.

## Front-ends GUI para Hercules
* [HercGUI](http://softdevlabs.com/hercgui.html) - *"HercGUI La interfaz gráfica de usuario de Hercules para Windows es un programa estándar de Windows que hace que usar el emulador Hercules sea mucho más fácil y agradable. Mantiene automáticamente tu configuración de Hercules y los archivos de log mediante diálogos estándar de Windows y proporciona retroalimentación realista en tiempo real sobre la actividad de tu mainframe virtual."*  De Software Development Laboratories.
* [HercStudio](http://hercstudio.sourceforge.net) - Hercules Studio es un front-end GUI para el emulador Hercules en Mac y Linux.  Escrito por Jacob Dekel.
* [Jason](http://ollydbg.de/Jason/index.htm) - *"Jason 1.00 es un front-end gráfico integrado para el emulador Hercules S/370, ESA/390 y z/Architecture. ¿Qué, no habías escuchado de Hercules antes? Es una obra maestra que emula mainframes IBM, desde el buen viejo IBM System/360 y hasta la moderna serie z."*
  * [MockbaTheBorg/TK4_Jason](https://github.com/MockbaTheBorg/TK4_Jason) - Información sobre cómo hacer que Jason y TK4- trabajen bien juntos.
* [MVS Ops](https://mvs.gadsby.me.uk) - Una aplicación web que simplifica la administración de MVS ejecutándose en Hercules.

## Emuladores de terminal TN3270
* [Vista TN3270](https://www.tombrennansoftware.com/index.html) - Emulador TN3270 con muchas funciones de Tom Brennan para Microsoft Windows; corre en Linux y Mac con WINE. *"Vista tn3270 es un programa para Windows diseñado para emular terminales IBM 3270 conectadas a un host mediante un enlace IP. Actualmente está disponible como prueba gratis por 30 días y cuesta solo $30. Si buscas un emulador creado pensando en programadores de mainframe, entonces pruébalo. Puede que encuentres funciones únicas que no están disponibles incluso en los emuladores comerciales más caros."*
* [x3270](http://x3270.bgp.nu) - x3270 es un emulador de terminal IBM 3270 para el X Window System y Windows. Corre en la mayoría de los sistemas operativos tipo Unix -- por ejemplo, Linux, Mac OS X, Solaris y Cygwin. Para correr de manera nativa en Windows, descarga e instala wc3270. 
* [tn3270 para Macintosh](https://www.brown.edu/cis/tn3270/) - Emulador TN3270 gratuito para versiones de macOS X anteriores a 10.15 (Catalina) ya que requiere soporte para aplicaciones de 32 bits.
* [PW3270](https://softwarepublico.gov.br/social/pw3270) ([github](https://github.com/PerryWerneck/pw3270)) - Emulador TN3270 opensource (GPL2)
* [ZOC: Cliente SSH y emulador de terminal para Windows y macOS](https://www.emtec.com/zoc/) - ZOC es un emulador de terminal comercial y multiplataforma con soporte para emulación TN3270.
### Información técnica de TN3270/3270
* [Programación de flujos de datos 3270](https://www.tommysprinkle.com/mvs/P3270/start.htm) - Referencia de Tommy Sprinkle sobre flujos de datos 3270.  

## Sistemas operativos
### MVS
* [Tur(n)key MVS 3.8j TK4-](http://wotho.ethz.ch/tk4-/) - La forma más fácil de empezar con MVS. TK4- es una distribución preconstruida de MVS con muchas mejoras, que incluye lenguajes de programación y herramientas adicionales. Está lista para ejecutarse en Linux, MacOS X, Windows e incluso una Raspberry Pi (en las versiones más recientes).
* [Tur(n)key MVS 3.8j TK3](http://www.bsp-gmbh.com/turnkey/) - Distribución Tur(n)key MVS 3.8 TK3 de Volker Bandke.
* [Instalar y ejecutar MVS 3.8j](http://www.jaymoseley.com/hercules/) - Enfoque práctico para generar un sistema MVS 3.8j funcional a partir del sistema inicial IBM MVS 3.7. 
* [MVS/380](http://mvs380.sourceforge.net/) - MVS/380 es una versión parchada de MVS 3.8 y Hercules que permite acceso al espacio de direcciones de 31 bits. 
#### Información de MVS
* [MIB Mainframe Useful Commands - Basic V1.10](https://www.yumpu.com/it/document/read/7780434/mib-mainframe-useful-commands-basic-v110) - Hoja de trucos (cheatsheet) de comandos útiles de zOS / MVS de ibmmainframe.cn 
* [Tutorial de TSO](http://www.jaymoseley.com/hercules/tso_tutor/tsotutor.htm) - Tutorial de TSO de Jay Moseley, basado en MVS 3.8.
* [El recetario para nuevos usuarios de MVS Tur(n)key](http://www.bsp-gmbh.com/turnkey/cookbook/index.html) - Un gran recurso para usuarios nuevos de Volker Bandke, creador de TK3.
* [FAQ de MVS](http://www.jaymoseley.com/hercules/faq/mvsfaq.htm) - Preguntas frecuentes relacionadas con MVS respondidas por Jay Mosley.
#### Videos de MVS
* [Agregar un dispositivo de disco a tu sistema MVS o z/OS - M14](https://www.youtube.com/watch?v=UXCaXF0n0F4) video de Moshix

### VM/370
* [Descargas de VM/370 - múltiples versiones](http://www.smrcc.org.uk/members/g4ugm/VM370.htm) - Este sitio incluye la versión Six Pack 1.2 de Robert O'Hara, el sistema 5-Pack de Paul Gorinskey, el sistema 4-Pack de Andy Norrie y el sistema 3-Pack original de Bob Abele.
* [Six Pack, versión 1.3 Beta](http://www.smrcc.org.uk/members/g4ugm/SixPack-1.3.Beta.htm)
* [Six Pack Extended (6PExt)](https://geronimo370.nl/vm6pext/vm-370/) - Actualización no oficial de René Farland a la distribución original Six Pack 1.2. 6PExt incluye el núcleo RSCS reciente de Peter Coghlan para soporte NJE.
#### Videos de VM/370
* [Meter datos dentro y fuera de VM/370 y z/VM - M101](https://www.youtube.com/watch?v=U-kFCsiqB0c&list=PLmD2RvHHbEaDX9PK0nxBlGbZpKJKU26WX&index=8&t=0s) video de [Moshix](https://github.com/moshix)
* [Operaciones de cinta en VM/370 - M96](https://www.youtube.com/watch?v=HfSPt66v7Hk&list=PLmD2RvHHbEaDX9PK0nxBlGbZpKJKU26WX&index=6&t=0s) video de [Moshix](https://github.com/moshix)
* [VSAM en IBM VM/370 - M93](https://www.youtube.com/watch?v=YDX-gn1WmNU&list=PLmD2RvHHbEaDX9PK0nxBlGbZpKJKU26WX&index=5&t=0s) video de [Moshix](https://github.com/moshix)
* [Mantener el directorio de usuarios en VM/370 o z/VM - M90](https://www.youtube.com/watch?v=auRtWgQSSfc&list=PLmD2RvHHbEaDX9PK0nxBlGbZpKJKU26WX&index=3&t=0s) video de [Moshix](https://github.com/moshix)
* [Proteger nuestros mainframes alojados MVS 3.8 y VM/370 con iptables - M147](https://www.youtube.com/watch?v=yuS9Hih1vxA&list=PLmD2RvHHbEaDX9PK0nxBlGbZpKJKU26WX&index=18&t=0s) video de [Moshix](https://github.com/moshix) explicando cómo asegurar un mainframe emulado con iptables.
* [Hacer que MVS y VM/370 coexistan en paz - M153](https://www.youtube.com/watch?v=73cPmEe-Qm4&list=PLmD2RvHHbEaDX9PK0nxBlGbZpKJKU26WX&index=22&t=0s) video de [Moshix](https://github.com/moshix)

### MUSIC/SP
MUSIC/SP (Multi-User System for Interactive Computing/System Product; originalmente "McGill University System for Interactive Computing") fue desarrollado en la Universidad McGill en los años 70 a partir de un sistema temprano de tiempo compartido de IBM llamado RAX (Remote Access Computing System). 
* [MUSIC/SP](http://www.canpub.com/teammpg/de/mcgweb/msi/musicsp.htm) - MUSIC/SP significa Multi-User System for Interactive Computing / System Product. Es un sistema operativo, similar en algunos aspectos a Unix. Es un sistema verdaderamente multi-tarea y multiusuario. 

### Michigan Terminal System
El Michigan Terminal System (MTS) es uno de los primeros sistemas operativos de tiempo compartido. Fue desarrollado en 1967 en la Universidad de Michigan para usarse en IBM S/360-67, S/370 y mainframes compatibles.
* [Archivo del Michigan Terminal System](http://archive.michigan-terminal-system.org)

### Linux
* [Linux/390 en la Universidad de Princeton](http://linuxvm.org/penguinvm/)
* [Gentoo Linux/390 en Hercules](https://wiki.gentoo.org/wiki/S390/Hercules) - Esta guía es sobre instalar Gentoo en una máquina S390 emulada usando Hercules.
* [Cómo instalar Ubuntu 18.04 en el mainframe Hercules - M87](https://www.youtube.com/watch?v=QTBNt32ERWE) video de [Moshix](https://github.com/moshix)
### DOS/360
Hay al menos cuatro procedimientos de instalación disponibles. Los primeros tres están en el grupo [H390-DOS/VS groups.io](https://groups.io/g/H390-DOSVS) (se requiere registro gratuito) y el cuarto es un sitio web independiente.
* [DOS360-2314.zip de Bill Carlborg](https://groups.io/g/H390-DOSVS/files/Yahoo-Archive/files.zip) - Ver el archivo zip dentro del archivo files.zip: dos360-2314.zip.
* [DYI-DOS360.zip de Ben Huntsman](https://groups.io/g/H390-DOSVS/files/Yahoo-Archive/files.zip) - Ver el archivo zip dentro del archivo files.zip: DIY-DOS360.zip.
* [DOS-360 26.2 de Kevin Leonard](https://groups.io/g/H390-DOSVS/files/Yahoo-Archive/files.zip) - Ver la carpeta dentro del archivo files.zip: DOS-360 26.2.
* [Archivo de software de dominio público IBM de J. Maynard](http://www.ibiblio.org/jmaynard/) - Incluye varias versiones de OS/360; Turnkey MVT de Kevin Leonard; DOS/360 y TOS/360; 4-pack VM/370 de Andy Norrie; Tu(r)nkey TK3 MVS de Volker Bandke; y TSS/370.
* [Instalar DOS/360 en Hercules 390](https://sites.google.com/site/dos360install/) - Este sitio está modelado de forma general a partir del sitio de Jay Moseley sobre MVS 3.8j mencionado arriba, en la sección de MVS. 
### DOS/VS
* [2314DOS.zip del usuario de Yahoo! ceo1944](https://groups.io/g/H390-DOSVS/files/Yahoo-Archive/files.zip) - Ver el archivo zip dentro del archivo files.zip: 2314dos.zip. Este enlace descarga un archivo zip de JCL e instrucciones desde el grupo H390-DOS/VS en groups.io; se requiere registro gratuito.
* [DOSVSE](https://github.com/moshix/DOSVSE) - JCL, scripts, jobs y software relacionados con DOS/VS, DOS/VSE, VSE/ESA, z/VSE de [Moshix](https://github.com/moshix)
### OS/360 MFT
### OS/360 MVT
IBM OS/360 MVT es un sistema operativo sin almacenamiento virtual.
* [Introducción a generar y ejecutar OS/360 en Hercules](http://www.conmicro.com/hercos360/) - Jay Maynard, "The Tron Guy", proporciona un buen procedimiento de instalación.
* [Archivo de software de dominio público IBM de J. Maynard](http://www.ibiblio.org/jmaynard/) - Incluye varias versiones de OS/360; Turnkey MVT de Kevin Leonard; DOS/360 y TOS/360; 4-pack VM/370 de Andy Norrie; Tu(r)nkey TK3 MVS de Volker Bandke; y TSS/370.
### TSS/370
* [Archivo de software de dominio público IBM de J. Maynard](http://www.ibiblio.org/jmaynard/) - Incluye varias versiones de OS/360; Turnkey MVT de Kevin Leonard; DOS/360 y TOS/360; 4-pack VM/370 de Andy Norrie; Tu(r)nkey TK3 MVS de Volker Bandke; y TSS/370.
## CICS
* [KICKS para TSO](http://kicksfortso.com) - Un reemplazo gratuito de CICS que corre en los entornos TSO o CMS
  * [KICKS (CICS) para IBM MVS 3.8 - Procesamiento de transacciones - M24](https://www.youtube.com/watch?v=u_ZSH9OagTM) - Video de [Moshix](https://github.com/moshix) sobre instalar KICKS para TSO
  * [An idiot at a mainframe](https://idiotmainframe.blogspot.com) - Blog de Johan. Aunque está listado en la categoría de blogs, publica mucha información sobre el uso de KICKS, así que amerita incluirse aquí también.
* [Mainframe CICS World](https://sites.google.com/site/mainframecicsworld/) - Mucha información sobre CICS

## Lenguajes de programación
### APL
* [MVT para APL versión 2.00](http://wotho.ethz.ch/mvt4apl-2.00/) - OS/360-MVT 21.8F personalizado para usarse con APL\360 versión 1 Modification Level 1 por Jürgen Winkelmann - también se necesita el [código fuente de IBM APL\360](http://www.computerhistory.org/atchm/the-apl-programming-language-source-code/). Descarga el código fuente aceptando el [Acuerdo de licencia](https://computerhistory.org/blogs/apl360-software-license-agreement/).
### Assembler
* [IBM Mainframe Assembler - Consejos y trucos](http://www.les-smith.com/software/assembler/assembler-hints-and-tips.htm)
* [Recursos de Assembler de David Woolbright](http://csc.columbusstate.edu/woolbright/WOOLBRIG.htm)
#### Tutoriales / Cursos de Assembler
* [Programar en lenguaje ensamblador en los mainframes IBM: una introducción](http://www.edwardbosworth.com/My3121Textbook/MyText3121_AFrontMatter_V03.htm) por Edward L. Bosworth, Ph.D.
* [Programación de Assembler para mainframes por Bill Qualls](http://billqualls.com/assembler/)
### BASIC
* [Intérprete Batch Basic para MVS 3.8 en IBM S/370](https://github.com/moshix/BASIC360)
### C
### CLIST
* [Tutorial de TSO de Jay Moseley](http://www.jaymoseley.com/hercules/tso_tutor/tsotutor.htm) - Aunque está pensado como tutorial de TSO, las partes posteriores del tutorial se enfocan en Command Lists (CLIST).
### COBOL
#### Tutoriales / Cursos de COBOL
* [COBOL Programming de OpenMainframe Project](https://github.com/openmainframeproject/cobol-programming-course) - Curso de programación COBOL opensource creado durante la pandemia de COVID-19.
* [Universidad de Limerick - Departamento de CSIS](http://www.csis.ul.ie/cobol/) - Programación COBOL - tutoriales, lecturas, ejercicios, ejemplos
#### Videos de COBOL
* [Cobol y el desastre del Departamento de Salud de Nueva Jersey - M169](https://www.youtube.com/watch?v=3KEQT7IPRgg) - Video de [Moshix](https://github.com/moshix) discutiendo la situación actual con COBOL y el Departamento de Salud de NJ, y una breve descripción general de COBOL
* [Programa Hello world en Cobol de mainframe - M124](https://www.youtube.com/watch?v=exAp0Ddbi-c) - [Moshix](https://github.com/moshix) escribe un programa Hello Word en COBOL de mainframe
* [IBM MVS - Editar, compilar y ejecutar un programa Cobol - M2](https://www.youtube.com/watch?v=YA3FQOzr0ag) video de [Moshix](https://github.com/moshix)
* [Compilador IBM OS/VS Cobol vs compilador moderno IBM Enterprise Cobol - M47](https://www.youtube.com/watch?v=sP2umvFZ3Xk) video de [Moshix](https://github.com/moshix)
* [Programación de sistemas con IBM Cobol - M72](https://www.youtube.com/watch?v=030TuJZ9wIo) video de [Moshix](https://github.com/moshix)

### JCL
* [Tutorial introductorio de utilidades JCL](http://www.bsp-gmbh.com/turnkey/cookbook/utilmvs.html)
### REXX
* [BREXX/370](https://github.com/mgrossmann/brexx370) - BREXX/370 es un port solo para MVS (y que se mantiene activamente) de la implementación rexx de Vasilis Vlachoudis. [Mike Grossmann](https://github.com/mgrossmann) y [Peter-Jacob](https://github.com/Peter-Jacob) han corregido bugs y agregado muchas funciones, incluyendo soporte para VSAM y paneles interactivos a pantalla completa (FSS).
#### Tutoriales / Cursos de REXX
* [Tutorial de REXX de Jim Barry](http://www.kyla.co.uk/other/rexx1.htm#introduction)
* [Instalar y ejecutar el recién lanzado intérprete Rexx para MVS 3.8j - M113](https://www.youtube.com/watch?v=3Sg0mYdeIsE) video de [Moshix](https://github.com/moshix)
## Canales de YouTube relacionados con mainframes
La lista de abajo son canales de YouTube que presentan videos relacionados con mainframes.
* [Moshix Mainframe Channel](https://www.youtube.com/user/moshe5760) - [Moshix](https://github.com/moshix) es un veterano de mainframes con una gran cantidad de seguidores de casi 4,000 suscriptores. Frecuentemente publica videos nuevos que cubren todo lo relacionado con mainframes.
* [Mainframes & More with Matthew](https://www.youtube.com/channel/UCFvM_17zCxRhXHIhOyg-N3Q) - Videos sobre mainframes IBM y mini-computadoras. Tiene una serie de videos que detallan cómo hacer un sysgen (instalación) de MVS 3.8 desde cero.

## HNET / BITNET
BITNET fue una red cooperativa de computadoras de universidades en EE. UU. fundada en 1981 por Ira Fuchs en la City University of New York (CUNY) y Greydon Freeman en Yale University. Los protocolos de red NJE (Network Job Entry) de BITNET, llamados RSCS, se usaban para la enorme red interna de IBM conocida como VNET. Los protocolos de BITNET eventualmente se portaron a sistemas operativos de mainframe no IBM y se volvieron ampliamente implementados bajo VAX/VMS, además de DECnet.

HNET es la red de mainframes compatible con BITNET de [Moshix](https://github.com/moshix) (tanto big iron como emulados), así como sistemas Linux y VAX, construida sobre NJE sobre TCP/IP. 
* [NJE Subsystems for MVS 3.8J](https://github.com/moshix/nje38mvs) - Este es el ingenial subsistema NJE de Bob Polmanter para MVS 3.8. Funciona perfecto con TK4- MVS 3.8 (update 8).
* [NetNJE](https://github.com/friedkiwi/netnje) - Servidor y cliente NJE (Network Job Entry) de [Yvan Janssens](https://github.com/friedkiwi) implementado en C#
* [LinuxNJE](https://github.com/moshix/linuxNJE) - NJE para Linux. LinuxNJE es la tercera encarnación del protocolo NJE de la Hebrew University of Jerusalem para UNIX y VMS. Esta versión fue actualizada por Moshix para que compile correctamente con compiladores gcc modernos y corra en distribuciones Linux modernas.
* [HUJInje](https://github.com/moshix/HUJInje) - El software NJE original de la Hebrew University of Jerusalem.
### Videos de HNET / BITNET
* [Conectar MVS 3.8 a HNET/BITNET con NJE38 - M168](https://www.youtube.com/watch?v=8_esBksImCg&list=PLmD2RvHHbEaBJyWYyuBL4-kWr6vNEkR5B&index=2&t=0s) video de [Moshix](https://github.com/moshix)
* [NJE, TCPIP, DECNET - openVMS habla mainframe - M167](https://www.youtube.com/watch?v=3UZLYJktm_M&list=PLmD2RvHHbEaBJyWYyuBL4-kWr6vNEkR5B&index=3&t=0s) video de [Moshix](https://github.com/moshix)
* [Usa tu caja Linux para conectarte a la red HNET bitnet - M163](https://www.youtube.com/watch?v=1iHrNNH7plY&list=PLmD2RvHHbEaBJyWYyuBL4-kWr6vNEkR5B&index=4&t=0s) video de [Moshix](https://github.com/moshix)
* [Grupos de discusión de mainframes con HNET (BITNET) CONFERENCES - M162](https://www.youtube.com/watch?v=gsY_m8ufcs4&list=PLmD2RvHHbEaBJyWYyuBL4-kWr6vNEkR5B&index=5&t=0s) video de [Moshix](https://github.com/moshix)
* [Un servidor de chat para HNET (BITNET) - M158](https://www.youtube.com/watch?v=VwbPgY-yQ7Q&list=PLmD2RvHHbEaBJyWYyuBL4-kWr6vNEkR5B&index=6&t=0s) video de [Moshix](https://github.com/moshix)
* [Desarrollar apps de red ágiles para mainframes con NJE - M157](https://www.youtube.com/watch?v=QZZJhTnbYUM&list=PLmD2RvHHbEaBJyWYyuBL4-kWr6vNEkR5B&index=7&t=0s) video de [Moshix](https://github.com/moshix)
* [BITNET - El despertar - M155](https://www.youtube.com/watch?v=SpUgWt9OWB0&list=PLmD2RvHHbEaBJyWYyuBL4-kWr6vNEkR5B&index=8&t=0s) video de [Moshix](https://github.com/moshix)

## Blogs de mainframes
* [Geronimo/370](https://geronimo370.nl) - Blog de Gerrard Wassink
* [An idiot at a mainframe](https://idiotmainframe.blogspot.com) - Blog de Johan. Mucha información sobre el uso de KICKS.
* [mainframe.dev](https://blog.mainframe.dev) - Blog de Christian Svensson  
  
## Cursos
* [The Complete Mainframe Professional Course : TSO/ISPF](https://www.udemy.com/course/the-complete-mainframe-professional-course-tso-ispf/) (UDEMY) por Abhishek Rathi. *"El primer paso para aprender sobre mainframes. 4 cursos en 1. Cubre TSO, ISPF, JCL, VSAM, COBOL y CICS."*
* [Mainframe: The Complete TSO/ISPF from Beginner to Expert](https://www.udemy.com/course/master-tso-ispf-on-mainframe-from-scratch-to-advanced-level/) (UDEMY) por Sandeep Kumar. *"El mejor curso de TSO e ISPF. Los comandos de TSO e ISPF se explican a detalle. COBOL simplificado se cubre como bonus junto con JCL."*
* [Mainframe: The Complete JCL Course from Beginner to Expert](https://www.udemy.com/course/the-complete-jcl-course-from-beginner-to-expert-on-mainframe/) (UDEMY) por Sandeep Kumar. *"Conviértete en un experto en JCL. Los JCL se usan para programas COBOL. Se cubren procedures, utilities, GDG y lo básico de TSO/ISPF."*
* [IBM z/OS Mainframe Practitioner Professional Certificate](https://www.coursera.org/professional-certificates/ibm-z-mainframe#courses) (COURSEA) - En realidad es una colección de 3 cursos de Jeff Bisti:
  * [Introducción a Enterprise Computing](https://www.coursera.org/learn/introduction-enterprise-computing)
  * [Primeros pasos en mainframe con comandos y paneles de z/OS](https://www.coursera.org/learn/z-commands-and-panels)
  * [Programación básica de sistemas en IBM Z](https://www.coursera.org/learn/system-programming)
* [COBOL Programming de OpenMainframe Project](https://github.com/openmainframeproject/cobol-programming-course) - Curso de programación COBOL opensource creado durante la pandemia de COVID-19.

## Software gratuito u opensource para correr en tu mainframe
* [CBT Tape](http://www.cbttape.org) - El CBT tape es una colección de freeware (casi todo open source) para el mainframe IBM en el entorno de los sistemas operativos MVS y OS/390.
* [Pycroft Six](http://www.prycroft6.com.au/software.html) - User Mods y software gratuito de MVS de Pycroft Six, incluyendo REVIEW, un navegador y editor TSO a pantalla completa.

## Otras listas de enlaces
* [Lista de enlaces de Scott C sobre Hercules](https://curlie.org/Computers/Emulators/IBM_Mainframe/Hercules/) - Otra lista de enlaces, similar a la lista Awesome Mainframes.
* [Bookmarks de DeepBlue2](https://curlie.org/Bookmarks/D/deepblue2/) - Otra lista larga de enlaces con recursos de mainframe. Lamentablemente, algunos enlaces apuntan a sitios que ya no existen.
* [Tur(n)key #3, Hercules, MVS/380, VM/370, VM/380, DocLinks](https://webfiles.uci.edu/scosel/_TK3herc_links.html)  

## Comunidades / Foros / Listas de correo
### groups.io
Muchos de estos grupos se originaron como un Yahoo! Group, pero después de cambios en Yahoo!, la mayoría de los miembros migraron sus discusiones a groups.io. El acceso a mensajes, archivos y enlaces del grupo solo está disponible después de unirte a cada grupo (membresía gratuita).
* [cbt-tape](https://groups.io/g/cbt-tape) - Discusión sobre el [CBT Tape](http://www.cbttape.org/) software de mainframe de dominio público.
* [H390-DOSVS](https://groups.io/g/H390-DOSVS) - Discusión sobre el uso de los sistemas operativos DOS/VS y DOS/VSE bajo el emulador de mainframe Hercules.
* [H390-MTS](https://groups.io/g/H390-MTS) - Discusión sobre el uso del [sistema operativo MTS](https://try-mts.com/why-try-mts/) bajo el emulador de mainframe Hercules.
* [H390-MUSIC](https://groups.io/g/H390-MUSIC) - Discusión sobre el uso del sistema operativo [Music/SP](http://www.canpub.com/teammpg/de/mcgweb/msi/musicsp.htm) bajo el emulador de mainframe Hercules.
* [H390-MVS](https://groups.io/g/H390-MVS) - Discusión sobre el uso del sistema operativo [MVS](http://wotho.ethz.ch/tk4-/) bajo el emulador de mainframe Hercules.
* [H390-OSVS1](https://groups.io/g/H390-OSVS1) - Discusión sobre el uso del sistema operativo OS/VS1 de IBM bajo el emulador de mainframe Hercules.
* [h390-vm](https://groups.io/g/h390-vm) - Discusión sobre el uso del sistema operativo [VM/370](http://www.smrcc.org.uk/members/g4ugm/VM370.htm) bajo el emulador de mainframe Hercules.
* [hercules-390](https://hercules-390.groups.io/g/group) - Discusión sobre instalar y/o usar el [emulador de hardware Hercules](http://www.hercules-390.eu/) en sí. Las discusiones sobre instalar y/o usar software de sistemas operativos específicos deberían hacerse en uno de los otros grupos listados.
* [hercules-os380](https://groups.io/g/hercules-os380) - Discusión sobre el uso del sistema operativo [Hercules-os380](https://sourceforge.net/projects/mvs380/files/mvs380/) de 31 bits y sus partes, corriendo en el sistema operativo MVS 3.8j de dominio público bajo el emulador de mainframe Hercules.
* [hercules-s370asm](https://groups.io/g/hercules-s370asm) - Discusión sobre usar ensamblador [S/370](http://www.jaymoseley.com/hercules/compiling/how_to.htm#topic16) bajo el emulador de mainframe Hercules.
* [KICKSforTSO](https://groups.io/g/KICKSforTSO) - Discusión sobre usar [KICKS para TSO](http://www.kicksfortso.com/) (sustituto gratuito de CICS) en [MVS TK4-](http://wotho.ethz.ch/tk4-/) bajo el emulador de mainframe Hercules.
* [turnkey-mvs](https://groups.io/g/turnkey-mvs) - Discusión sobre usar el sistema operativo [Turnkey 4- MVS 3.8j](http://wotho.ethz.ch/tk4-/) bajo el emulador de mainframe Hercules.

## Otros / Pendiente de categorizar
  
---
# Otros mainframes IBM (IBM 1401, 1620, 7090/7094, System 3)
Aunque la intención original de esta lista era enfocarse en el IBM System/360 y sus descendientes, [RattyDAVE](https://github.com/RattyDAVE) me recordó SimH, que emula algunos de los otros mainframes de IBM, así que incluyo una sección para esas máquinas en esta lista también.
## Emuladores
* [SimH](http://simh.trailing-edge.com/) ([github](https://github.com/simh/simh)) SimH (History Simulator) es una colección de simuladores para hardware y software históricamente significativos o simplemente interesantes del pasado. Emula IBM 1401, 1620, 7090/7094, System 3, así como muchas otras computadoras históricas.
* [IBM 1401 EMULATOR IN BAL 360 ASSEMBLY](https://github.com/moshix/IBM1401) - Un emulador para la computadora IBM 1401, escrito en BAL360, pensado para funcionar en MVS 3.8
## Software
* [Kits de software de SimH](http://simh.trailing-edge.com/software.html) - Varios sistemas operativos históricos y software para correr en tus sistemas emulados con SimH.