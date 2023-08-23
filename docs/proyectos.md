---
layout: default
title: Proyectos
nav_order: 3
---

# Proyectos
{: .no_toc }

## Vista general de la sección 
![](../../assets/images/clientesvg.png)  
En esta sección, los usuarios podrán acceder a una tabla detallada de los proyectos actuales que han sido cargados en la aplicación. Cada proyecto se presenta con información relevante y completa, que incluye el **nombre del proyecto**, el **cliente asociado**, las **fechas de inicio** y **finalización**, el **estado** actual del proyecto y la **fase** en la que se encuentra hasta el momento.  
<br>
Esta vista proporciona una visión general completa y actualizada de todos los proyectos en curso, lo que permite a los usuarios mantenerse al tanto del estado de proyecto y tomar decisiones informadas en función del progreso y las fechas límite. Además, la disponibilidad de información detallada sobre el cliente asociado en cada proyecto facilita la identificación rápida y precisa de los proyectos relacionados con cada cliente específico, optimizando así la eficiencia y organización en la gestión de múltiples proyectos y clientes.


---
## Filtrando proyectos y clientes

![](../../assets/images/buscador.png)  
Para facilitar la búsqueda y organización de proyectos, el usuario podrá utilizar la función de filtrado. 

1. Localizar el buscador ubicado en la parte superior izquierda de la vista general con la palabra "Buscar proyecto"
2. Ingresar el nombre del proyecto que quiere buscar.
3. A medida que se escribe el nombre del proyecto o nombre del cliente, la tabla comenzará a mostrar automáticamente los resultados coincidentes en tiempo real.

--- 

## ¿Cómo agregamos un proyecto?

Los usuarios tendrán la capacidad de crear nuevos proyectos directamente desde esta sección. A continuación, se detallará como agregar un nuevo proyecto.

1. Localizamos el botón de "Nuevo proyecto" en la parte superior derecha de la vista general.

   ![](../../assets/images/NuevoProyecto.png)

2. Hacer clic en el botón. Se nos abrirá un modal con el formulario de alta de un proyecto donde vamos a rellenar todos los campos.

   ![](../../assets/images/Creando Proyecto.png)

3. Ingresamos el nombre del proyecto, este nombre debe ser único y no coincidir con algún proyecto existente en la plataforma. 

   ![](../../assets/images/NombredelProyecto.png)

4. Seleccionamos el cliente que pertenece el proyecto en la lista despegable.
   
    ![](../../assets/images/buscarCliente.png)

5. Ingresamos la cantidad de horas totales de desarrollo del proyecto.
   
   ![](../../assets/images/horasproyecto.png)

6. Ingresamos la cantidad de horas totales vendidas.
   
   ![](../../assets/images/cantidadHorasVendidas.png)

7. Ingresamos fecha de Inicio del proyecto y la fecha de finalización del proyecto.
   ![](../../assets/images/fechainicio.png)

8. Seleccionamos de la lista despegable el estado en el que se encuentra el proyecto, estos pueden ser: En Curso, Cancelado, Terminado, En análisis, En espera cliente, En espera interno.
   ![](../../assets/images/selectEstado.png)

9.  Seleccionamos de la lista despegable la fase en el que se encuentra el proyecto, estos pueden ser (En curso, En construcción, En preparación, En producción, Desarrollo, Requerimientos, Cancelado).
   ![](../../assets/images/selectEstadoProyecto.png)

10. indicamos el porcentaje del avance en cual se encuentra el proyecto indicando del 0 al 100%.
   ![](../../assets/images/proyecto.png)

Finalmente, una vez rellenado todos los campos existentes para crear un proyecto finalizamos el proceso haciendo clic en "Crear proyecto" y esperamos la confirmación de la creación del proyecto.
   ![](../../assets/images/btnCrearProyecto.png)

--- 


## ¿Cómo editamos un proyecto?
Esta sección también permitirá a los usuarios editar los proyectos existentes en caso de que se necesite. Para editar un proyecto deben seguir los siguientes pasos.

1. Localizamos en la tabla de proyectos la columna de **ACCIONES** .
2. Identificamos el icono designado para la edición (icono de lápiz).
   
   ![](../../assets/images/botonEditarProyecto.png)
   
3. Hacemos clic en el icono de edición.
4. Se volverá a abrir el mismo modal con el formulario esta vez con los datos del proyecto seleccionado.
5. Modificamos el cambio que se necesite.
6. Hacemos clic en "Guardar cambios" para que impacten en la aplicación.  
   ![](../../assets/images/btnGuardarCambios.png)

--- 

## ¿Cómo eliminamos un proyecto?
En caso de que un proyecto haya sido concluido o desestimado, los usuarios podrán eliminarlo de la lista. La opción de "Eliminar proyecto" permitirá retirar de manera definitiva el proyecto seleccionado, asegurando que la lista de proyectos refleje siempre el estado actual de las tareas en curso, **los proyectos solo se podrán eliminar si no tienen clientes y consultores asignados al proyecto**.

![](../../assets/images/proyectos/botonEliminar.png)

1. Localizamos en la tabla proyectos la columna **ACCIONES**
2. Identificamos el icono designado para la eliminación de proyectos (icono con signo menos).
3. Hacemos clic en el icono de 'Eliminar'.
4. A continuación, recibiremos una advertencia de que la acción no se puede deshacer.  
   ![](../../assets/images/proyectos/eliminarProyecto.png)

5. Para que los cambios impacten en el sistema hacemos clic en el botón "Eliminar proyecto" para confirmar la acción.


## Errores que nos podemos encontrar en la sección    <br>

  <br><br>
   ![Error al guardar Cambios](../../assets/images/proyectos/errorProyecto1.png)  

1. Esta notificación de error alerta que se está queriendo eliminar un proyecto que tiene consultores asignados, verifique que el proyecto no tenga consultores asignados antes de eliminarlos. <br>
  
   ![Error al guardar Cambios](../../assets/images/proyectos/errorProyecto2.png) 

2. Esta notificación alerta que cuando se intentó crear el proyecto hubo un fallo y no se pudo crear, puede llegar a deberse por problemas de conexión o tal vez de servidor, cerrar y volver a intentarlo.<br>

   ![Error proyectos cargados](../../assets/images/proyectos/errorProyecto3.png)  

3. Esta notificación advierte que no se pudieron obtener los datos de la sección, puede deberse a problemas de conexión