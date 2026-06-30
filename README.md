# WES-Production-Engine

Guía de Configuración: WES Content & Production Engine
Esta guía detalla el proceso para configurar el sistema integral de producción de WES, garantizando que el agente opere bajo los parámetros de diseño, marca y automatización técnica requeridos.

1. Acceso al Creador de Agentes
Inicia sesión en tu cuenta de ChatGPT.

En el menú lateral, selecciona "Explorar GPTs" y haz clic en el botón "+ Crear" en la esquina superior derecha.

En la ventana de configuración, selecciona la pestaña "Configurar" (Configure) para editar los detalles manualmente.

2. Configuración General
Completa los campos en el siguiente orden:

Nombre: WES Content & Production Engine

Descripción: Sistema automatizado de estrategia, copy y producción de activos visuales para WES.

Instrucciones (Instructions): Copia y pega el contenido completo del archivo Instrucciones.txt 

Capacidades (Capabilities): Asegúrate de habilitar "Code Interpreter" (para la generación de archivos .docx y .pptx). Desactiva el resto si no son necesarias.

3. Carga de Base de Conocimiento (Knowledge)
Para que el agente pueda aplicar los colores y el estilo correctamente, es vital cargar la fuente de verdad:

En la sección "Conocimiento" (Knowledge), haz clic en "Subir archivos".

Sube el documento Manual de Marca.docx proporcionado en el archivo Manual de Marca. Esto permitirá que el agente consulte los valores HEX y las directrices visuales antes de cada ejecución.

4. Carga de Habilidades (Skills)
5. 
Descarga en tu computadora las 3 habilidades (WES Content Strategist), (WES Social Copywriter), (WES PowerPoint Automation) que te han sido proporcionadas en el archivo Skills_wes.

En la configuración del agente, haz clic en "Añadir habilidad" (o "Add skill").

Se abrirá una ventana emergente: en la barra lateral, selecciona la opción "Cargar skill" y sube los archivos .zip correspondiente.

Asegúrate de cargar las 3 habilidades una por una según lo requerido para que el agente cuente con la base técnica completa.

Las habilidades modularizan la lógica técnica (como la automatización de PowerPoint).

6. Guardado y Publicación
En la esquina superior derecha, haz clic en "Actualizar" o "Publicar".

Selecciona "Solo yo" (privado) o "Cualquier persona con el enlace" para compartirlo con tu equipo de trabajo.

6. Flujo de Operación (Uso diario)
Cada vez que necesites generar un carrusel:

Abre tu agente WES Content & Production Engine desde el menú lateral.

Escribe tu instrucción siguiendo el formato:

"Genera un carrusel sobre [TEMA] de [X] diapositivas. Sigue estrictamente el manual de marca y el protocolo de producción establecido."

El agente ejecutará el proceso de tres etapas (Estrategia > Copywriting > Producción) y te entregará:

Los enlaces de descarga directa para el .docx y .pptx.

La guía de exportación a PNG.

El resumen técnico de QA.

Notas importantes para el mantenimiento:
Ortografía: Este sistema ha sido configurado para preservar los caracteres especiales (tildes y "ñ"). Si detectas cualquier omisión, puedes corregir al agente recordando que su "Instrucción de codificación" prohíbe la normalización de texto.

Actualización de Marca: Si el Manual de Marca.docx cambia, simplemente reemplaza el archivo en la sección Conocimiento del agente. No es necesario reconfigurar las instrucciones si estas hacen referencia al archivo por su nombre.
