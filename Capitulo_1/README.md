# Nombre de la demostración: 1. Comunicación rápida en Teams: 

## Objetivo de la práctica:

![Instrucciones](/images/Laboratorio-01-00.jpg)

Al finalizar la práctica, el participante dominará la gestión de comunicaciones en escenarios corporativos complejos dentro de Microsoft Teams, siendo capaz de:

- Configurar chats grupales ad-hoc con asignación de nombres temáticos y control de miembros.

- Redactar comunicaciones estructuradas utilizando bloques de formato enriquecido, niveles de prioridad e inserción de código fuente con sintaxis adecuada.

- Implementar menciones contextuales directas y grupales (@mención) para trazabilidad de tareas.
- Compartir archivos con control granular de permisos de acceso desde OneDrive/SharePoint dentro de la conversación.

- Gestionar acciones sobre mensajes: reacciones, guardado para seguimiento y anclaje de información crítica.

## Duración aproximada:
- 10 minutos.

## Instrucciones 

### Tarea 1. Iniciar un chat.

Paso 1. En la aplicación de Microsoft Teams o desde el portal web de Teams, ir al panel de la izquierda y buscar el icono de mensajes.

Paso 2. Una vez localizado el icono de mensajes, dar clic en el y buscar el botón de *nuevos elementos* y selecciona nuevo mensaje. 

> Como alternativa puedes presionar el atajo Ctrl + N / Cmd + N).

Paso 3. En el extremo derecho del campo Para:, haz clic en la flecha desplegable para habilitar el campo Nombre de grupo. Asigna el nombre: Incidente Crítico - Despliegue DB.

Paso 4. Ingresa el nombre algunos contactos de tu organización (por lo menos 3) para enviar el mensaje.

Paso 5. Envía un mensaje genérico de prueba para crear el chat grupal.

### Tarea 2. Dar formato a un mensaje.

> En el ejercicio anterior se envío un mensaje genérico, ahora enviaremos un segundo mensaje, preferentemente el mensaje debe contener un pequeño fragmento de código para poder editarlo

Paso 1. En el cuadro de redacción del grupo creado, haz clic en *opciones de formato* (representado por el ícono Formato, un icono con la forma de la letra A con un lápiz) para expandir el editor de texto enriquecido.

Paso 2. Agrega una línea de asunto que describa el evento: URGENTE: Error en script de migración SQL.

Paso 3. Configura la prioridad del mensaje: haz clic en el menú contextual de opciones de entrega (!) y selecciona Importante.

Paso 4. En el cuerpo del mensaje, redacta una breve descripción técnica estructurada con una lista numerada que contenga los pasos a seguir, has uso de las diversas funciones que ofrece para poner el texto en negritas, subrayado, resaltado, tamaño de fuente entre otras.

Paso 5. Inserta un bloque de código. Haciendo clic en el icono Fragmento de código (</>) indica en que lenguaje es el que vas a enviar el fragmento de código

Paso 6. Pega el siguiente código:

> BEGIN TRANSACTION; 
> ALTER TABLE Clientes ADD EstadoCuenta VARCHAR(20) DEFAULT 'Activo';
> ROLLBACK TRANSACTION;



### Tarea 3. Mencionar a una persona.

Paso 1. En la misma conversación grupal, redacta una respuesta dirigida:
Escribe el símbolo @ seguido del nombre de uno de los integrantes para asignarle una tarea puntual.

Paso 2. Presiona la tecla Retroceso (Backspace) una vez inmediatamente después de completar el nombre para mostrar únicamente el primer nombre de la persona (mención limpia).

Paso 3. Agrega una mención general a todos los miembros presentes escribiendo @todos para validar el impacto de la notificación global.

### Tarea 4. Reaccionar a un mensaje.

Paso 1. Selecciona un mensaje dentro de la conversación y reacciona sobre el mismo con una reacción rápida.

Paso 2. Selecciona el mismo mensaje y ve al apartado de **Más opciones (...)** y realiza las siguientes acciones:
    1. Selecciona Anclar para fijar el mensaje en el panel de información superior del chat.
    2. Selecciona Guardar este mensaje para añadirlo a tu lista de marcadores personales de seguimiento.

### Tarea 5. Buscar una conversación

Paso 1. Usando la barra de búsqueda, busca alguna conversación con algún contacto con el que hayas mantenido una conversación reciente.

> También puedes usar el atajo **(Ctrl + E / Cmd + E)**

Paso 2. Una vez ingresado a ese chat, utiliza la opción de buscar mensaje para poder explorar las opciones de búsqueda internas dentro de las conversaciones.

> Puedes hacerlo mediante el atajo **Ctrl + F / Cmd + F)**

Paso 3. Busca el contenido que deseas encontrar.

### Tarea 6. Compartir un archivo.

Paso 1. Seleccionando cualquier chat, haz clic en el botón de adjuntar archivos (representado con un icono de un Clip de papel)

Paso 2. Selecciona **Cargar desde este equipo o OneDrive** y carga cualquier documento para que quede resguardado dentro del chat.

Paso 3. Repite el paso anterior, pero ahora haz clic en el **Selector de permisos** adjunto al nombre del archivo y cambia los permisos a unos valores distintos.

### Resultado esperado

El entorno de Teams debe reflejar:

Un chat grupal configurado con título personalizado persistente y miembros específicos.

Un mensaje marcado como "Importante" con un fragmento de código formateado y etiquetas de texto enriquecido.

Un hilo con mensajes anclados y guardados en marcadores.

Un registro de menciones directas ejecutadas con formato corto.

Un documento compartido en el chat con permisos restringidos de solo lectura, visible tanto en el historial como en la pestaña de archivos del grupo.