# Particiones y sistemas de archivos

----
Parte 1. Investigue los conceptos involucrados: partición (física y lógica, primaria, partición de arranque) (guía), GPT y MBR (guía), 
formatear un dispositivo de almacenamiento (guía), sistema de archivos (guía), archivo (guía), tipos de archivo (binario, texto, programa)(guía),
cómo se guarda un archivo (guía) y las operaciones de manejo de archivos (guía).

**Partición Física:** Es una división real en un dispositivo de almacenamiento, como un disco duro.
Cada partición física es independiente y puede contener un sistema de archivos o datos.
**Partición Lógica:** Se crea dentro de una partición primaria y se utiliza para organizar datos en más de cuatro divisiones en discos MBR.
Las particiones lógicas no pueden albergar sistemas operativos directamente.
**Partición Primaria:** Las particiones primarias son las divisiones principales en un disco duro y pueden contener sistemas operativos.
Un disco MBR puede tener hasta cuatro particiones primarias.
**Partición de Arranque:** También llamada "partición activa", es la partición desde la cual se inicia el sistema operativo en un disco MBR.
En sistemas GPT, esta función se maneja de manera diferente.

**GPT y MBR:**
**GPT (Tabla de Partición GUID):** Un estándar moderno de partición utilizado en discos grandes (>2TB) y sistemas UEFI.
Admite más particiones y proporciona mayor resistencia a errores.
**MBR (Registro Maestro de Arranque):** Un estándar más antiguo de partición utilizado en discos más pequeños y sistemas BIOS.
Limitado en tamaño y número de particiones (4 primarias o 3 primarias y 1 extendida).

**Formatear un Dispositivo de Almacenamiento:**
**Formateo:** Es el proceso de preparar un dispositivo de almacenamiento para su uso.
Borra todos los datos existentes y crea una nueva estructura de sistema de archivos.

**Sistema de Archivos:** Es la estructura utilizada para organizar y almacenar archivos en un dispositivo de almacenamiento.
Ejemplos incluyen NTFS, FAT32, EXT4 y HFS+.

**Archivo:** Es una unidad de información que se almacena en un dispositivo de almacenamiento.
Puede ser un documento, una imagen, un video, un programa, etc.

**Tipos de Archivo (Binario, Texto, Programa):**
**Archivo Binario:** Contiene datos en formato no legible por humanos.
Ejemplos incluyen archivos de imágenes, ejecutables de programas, etc.
**Archivo de Texto:** Contiene texto legible por humanos.
Ejemplos incluyen documentos de texto, archivos de código fuente, etc.
**Archivo de Programa:** Contiene instrucciones ejecutables por una computadora.
Ejemplos incluyen aplicaciones, software de sistema, scripts, etc.

**Cómo se Guarda un Archivo:**
**Guardar un Archivo:** Implica escribir datos en un archivo y almacenarlo en un dispositivo de almacenamiento.
Se realiza a través de aplicaciones que ofrecen opciones de "Guardar" o "Guardar como..." para elegir una ubicación y un nombre de archivo.

**Operaciones de Manejo de Archivos:** Incluyen acciones como crear, leer, escribir, copiar, mover, renombrar y eliminar archivos.
Se realizan mediante el sistema operativo o aplicaciones específicas de gestión de archivos.

----
