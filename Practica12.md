# Instalación de sistemas operativos como máquinas virtuales

----
Parte 1. Investigue qué es la virtualización, una máquina virtual y cómo se instala un sistema operativo en una máquina virtual.

**Virtualización** es una tecnología que permite crear entornos virtuales o máquinas virtuales (VM) en un servidor físico o una computadora personal. Estas máquinas virtuales actúan como sistemas informáticos independientes con su propio sistema operativo y aplicaciones, pero comparten los recursos físicos subyacentes. La virtualización es ampliamente utilizada en entornos empresariales y de desarrollo, así como para pruebas y desarrollo de software, ya que permite ejecutar múltiples sistemas en un solo hardware.

Una **máquina virtual (VM)** es una instancia de un sistema operativo que se ejecuta en un entorno virtualizado. Las VMs son completamente aisladas entre sí, lo que significa que pueden ejecutar sistemas operativos diferentes y tener configuraciones únicas sin afectar al sistema anfitrión o a otras VMs en el mismo servidor físico.

A continuación, se explica cómo instalar un sistema operativo en una máquina virtual:

**Paso 1:** Elije una Plataforma de Virtualización:

Debes seleccionar un software de virtualización adecuado. Algunas opciones populares incluyen VMware, VirtualBox, Hyper-V (para sistemas Windows) y KVM/QEMU (para sistemas Linux).

**Paso 2:** Descarga e Instala el Software de Virtualización:

Descarga e instala el software de virtualización en tu sistema anfitrión. Asegúrate de que tu hardware sea compatible con la virtualización.

**Paso 3:** Crea una Nueva Máquina Virtual:

Abre el software de virtualización y crea una nueva máquina virtual. Deberás especificar la cantidad de recursos (CPU, RAM, espacio en disco) que deseas asignar a la VM.

**Paso 4:** Configura las Opciones de Arranque:

En la configuración de la VM, debes seleccionar un archivo de imagen ISO del sistema operativo que deseas instalar. Este archivo ISO contiene los archivos de instalación del sistema operativo.

**Paso 5:** Inicia la Máquina Virtual:

Inicia la VM y sigue las instrucciones del asistente de instalación del sistema operativo seleccionado. Este proceso será similar a la instalación en una computadora física.

**Paso 6:** Completa la Instalación:

Durante la instalación, debes seleccionar las opciones de configuración, como el idioma, la zona horaria, el nombre de usuario y la contraseña.

**Paso 7:** Instala Herramientas Adicionales (Opcional):

Algunos hipervisores ofrecen "Herramientas de Invitado" o "Herramientas de VM" que mejoran la interacción entre el sistema anfitrión y la VM. Pueden incluir controladores, integración de pantalla completa, copiar y pegar entre sistemas, etc.

**Paso 8:** Finaliza la Configuración:

Una vez completada la instalación, tendrás un sistema operativo completamente funcional en tu máquina virtual. Puedes iniciar y apagar la VM según sea necesario.

----
