---- ##### Requisitos para el Funcionamiento ##### ----

Para asegurar que el gestor de pedidos funcione sin problemas, por favor, ten en cuenta los siguientes requisitos antes de empezar:

Microsoft Excel: Este archivo ha sido desarrollado y optimizado para Microsoft Excel 365 y es compatible con versiones recientes como Excel 2016, 2019 y 2021 en sistemas operativos Windows. Es importante tener en cuenta que el funcionamiento en Excel para Mac puede variar.

Habilitación de Macros: El archivo utiliza macros (VBA) para automatizar la gestión de pedidos. Para que la herramienta funcione correctamente, es indispensable que habilites las macros al abrir el archivo. Si necesitas ayuda, consulta la guía de cómo habilitar macros.

Permisos de Archivo: Asegúrate de que el archivo no está en una carpeta de solo lectura. Se necesitan permisos para guardar los cambios y las actualizaciones de la base de datos de pedidos.



### Manual de Usuario - Sistema de Gestión de Equipo alquilado
El presente manual ha sido diseñado como una guía práctica y de referencia para todos los usuarios involucrados en el proceso de manejo de equipos usados en actividades
El objetivo principal es asegurar la correcta y eficiente utilización del archivo de Microsoft Excel denominado "Equipos", una herramienta desarrollada internamente para automatizar y optimizar este flujo de trabajo en los procesos administrativos llevados en el manejo y control del equipo
Este documento te guiará paso a paso a través de las funcionalidades clave del archivo, desde la creación de un insumo, contrato, entrada, devolución y edición de registros hasta la visualización de los reportes de control. Al familiarizarte con las macros y funciones integradas, podrás maximizar el rendimiento de la herramienta, reducir los errores manuales y agilizar los tiempos de respuesta del proceso administrativo de los equipos



---- ##### Descripción General del Proceso de equipo alquilado ##### ----


Este sistema facilita la administración de los equipos alquilados usados en actividades. El proceso comienza cuando se presenta la necesidad en realizar una actividad que necesita de primera mano o como apoyo el uso de equipos. Una de las herramientas propuestas, es la elaboración de contrato para controlar el valor y la fecha de salida del equipo en requerimiento; luego al llegar el equipo, se dará entrada del mismo mediante formulario de ingreso, al momento de realizar la devolución del equipo, se realiza mediante formulario de devolución de equipo. Es posible mediante la herramienta visualizar el detalle del equipo en un periodo, como también será posible visualizar el valor del arrendamiento del periodo seleccionado.



---- ##### Instrucciones: Cómo Habilitar Macros y Empezar a Usar la Herramienta ##### ----

Por motivos de seguridad, Microsoft Excel deshabilita las macros de los archivos que se descargan de internet. Para que tu gestor de pedidos funcione correctamente, debes habilitarlas. El proceso es muy sencillo y solo lo tendrás que hacer una vez por archivo.

Paso 1: Habilitar las Macros (Opción 1 - La más común)
Abre el archivo Tu_Archivo.xlsm que has descargado.

Verás una barra de seguridad amarilla en la parte superior de la hoja de cálculo, justo debajo de la barra de herramientas. El mensaje dirá: "ADVERTENCIA DE SEGURIDAD Las macros se han deshabilitado."

Haz clic en el botón que dice "Habilitar contenido" o "Enable Content".

Una vez que hagas clic, las macros se activarán y la barra de seguridad desaparecerá. Ahora ya puedes utilizar todas las funciones automáticas del archivo.

Paso 2: Empezar a Usar el Gestor de Pedidos
Una vez que las macros están habilitadas, la herramienta está lista para ser usada.


---- ##### Creación Insumo ##### ----

Las celdas destinadas para el ingreso de la información se identifican fácilmente por su sombreado de color gris, lo que las distingue de las celdas protegidas o de solo lectura.
Descripcion_Insumo: campo para ingresar el nombre insumo
Unidad: corresponde a la unidad del insumo
Cod_Insumo: corresponde al código del insumo (este archivo contiene plantilla de migración de actas generales del sistema SINCO. Por lo que se recomienda usar el código del aplicativo SINCO)
El usuario puede usar el campo de descripción como buscador de insumos



---- ##### Registrar contrato ##### ----
En esta sección, será posible registrar el contrato perteneciente al proveedor quien suministra el equipo, si tiene contratos almacenados se verán en esta sección de manera informativa


---- ##### Adicionar insumo al contrato ##### ----
Luego de realizar el registro del contrato, se prosigue con adicionar insumos al contrato. En el formulario se deberá seleccionar el nombre del proveedor y el contrato ingresado. Luego de diligenciar los campos solicitados, procedemos al ingreso de los insumos al contrato. Seleccionando de la lista desplegable de la celda en color gris, seleccionar el insumo y a continuación indicar los campos habilitados como Valor Unit_(Incluido IVA), Item y	 Fecha Salida, si es necesario ingresar otro insumo se habilitará otra celda para seguir con el registro


---- ##### Registrar ingreso equipo ##### ----

Sección para registrar el ingreso del equipo. El usuario deberá seleccionar el proveedor y el número de contrato. Luego deberá ingresar la información del documento de ingreso de equipo” remisión”. Los campos acá solicitados deberán estar diligenciados en su totalidad para luego ingresar las cantidades del equipo relacionado en el documento

---- ##### Registrar devolución equipo ##### ----
Similar al formulario de ingreso, se diferencia por tener condiciones al momento de digitar las cantidades, esta tiene condición la cual no puede superar las cantidades del inventario existente del proveedor

---- ##### Corte y detalle periodo ##### ----
Ingresando a esta sección el usuario puede seleccionar el proveedor, contrato, fechas de periodo de corte (no superar los 62 dias), código del proyecto (usar código de proyecto SINCO), el usuario puede visualizar el valor del corte y el detalle del periodo
En la sección de detalle periodo se puede apreciar la información detallada en el periodo seleccionado en la sección corte periodo. El detalle mostrado cuenta con los colores azul para indicar devoluciones y color verde para ingresos

---- ##### Corte y detalle periodo ##### ----
Complementando la herramienta, en la sección de corte, se encuentra la plantilla de actas generales como migración en SINCO

---- ##### Licencia ##### ----

Este proyecto está distribuido bajo la Licencia MIT.
Esto significa que eres libre de usar, copiar, modificar, fusionar, publicar y distribuir este software para cualquier propósito, incluso para uso comercial, siempre que se conserve la nota de copyright original.

Contrasegna:

### File ### = RetoR@-8958
### Book ### = RetoR25$$5241
### Sheth ### = RetoR%&968725

### VBasic ### = Minirex$&8716&

