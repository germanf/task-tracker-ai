# Task Tracker

## 1. Interacción Humano-IA en la Creación de Código

La creación de esta aplicación web es un reflejo de la evolución en la colaboración entre humanos y sistemas de inteligencia artificial. A lo largo del desarrollo, se han implementado mejoras iterativas a partir de sugerencias detalladas, optimizando tanto la funcionalidad como la experiencia de usuario. Este tipo de sinergia permite no solo acelerar el desarrollo, sino también mejorar la calidad del producto final mediante una retroalimentación constante y precisa.

## 2. Descripción del Proyecto

Task Tracker es una aplicación web de gestión de tareas desarrollada con HTML, CSS (Bootstrap), y JavaScript puro. Su objetivo es ofrecer una interfaz sencilla pero potente para la administración de tareas, con funcionalidades como:
- Creación, edición y eliminación de tareas.
- Control de estado de tareas con marcado de "Done".
- Temporizador con cuenta regresiva y notificación al finalizar.
- Modo oscuro/claro con persistencia de selección.
- Soporte multilenguaje con selección de idioma.
- Respaldo en LocalStorage para persistencia de datos.
- Notificaciones del sistema y alertas de tiempo excedido.

## 3. Prompt para Generar la Misma Funcionalidad

Asegúrate de copiar y pegar este prompt en un modelo de IA avanzado para obtener exactamente la misma funcionalidad:

```
Quiero una aplicación web de gestión de tareas usando HTML, CSS (Bootstrap) y JavaScript puro con las siguientes características y funcionalidades:

1. **Lista de tareas**:
   - Cada tarea debe mostrar su título y tener un tooltip con su descripción. Si la descripción está vacía, el tooltip debe mostrar el título.
   - Checkbox "Done" para marcar si la tarea está completada. Al marcarlo:
     - La fila se debe tachar y deshabilitar.
     - Se debe ocultar el botón de "Iniciar/Pausar".
     - La tarea no puede ser editada hasta que se desmarque "Done".
   - Un clic en la celda del "Título" abre un modal para editar la tarea.
   - Botón "Eliminar" con tooltip, que elimina la tarea y la elimina de LocalStorage.
   - Botón "Iniciar/Pausar" con tooltip, para iniciar o pausar un temporizador de cuenta regresiva basado en el tiempo estimado.

2. **Modal de Agregar/Editar Tarea**:
   - Si se abre desde "Agregar Tarea", el modal debe titularse "Agregar Tarea".
   - Si se abre desde la edición, el modal debe titularse "Editar Tarea" y cargar la información existente.
   - El botón "Guardar" debe deshabilitarse si los campos "Título" o "Tiempo estimado" están vacíos.
   - Si el tiempo total de tareas sin completar supera los 20 minutos, el botón de "Agregar Tarea" debe deshabilitarse y debe mostrarse una alerta indicando "El tiempo de la tarea no puede superar {##}" siendo {##} el tiempo restante disponible.

3. **Cuenta regresiva**:
   - Al hacer clic en "Iniciar", comienza la cuenta regresiva en formato mm:ss.
   - Si se hace clic en "Pausar", la cuenta se detiene.
   - Si llega a 0, la tarea se marca como "Done", se muestra una notificación y se reproduce un sonido de campanilla.

4. **Modo Oscuro/Claro**:
   - Un botón con icono de sol/luna cambia entre los modos.
   - El modo se aplica a toda la página y sus componentes.
   - Los botones deben cambiar de tono al pasar el mouse (hover).

5. **Multilenguaje**:
   - Selector de idioma con banderas y nombres (Español, Inglés, Portugués, Italiano, Chino y Ruso).
   - Todos los textos deben cambiar dinámicamente según el idioma seleccionado.

6. **Persistencia y Notificaciones**:
   - Todas las tareas deben guardarse y recuperarse desde LocalStorage.
   - Pedir permisos para mostrar notificaciones.
   - Mostrar notificación al completar una tarea.
   - Corregir cualquier error de tooltips que queden colgados después de interactuar.
```

## 4. Perspectivas sobre el Futuro

La evolución de la colaboración entre humanos e inteligencias artificiales está redefiniendo la manera en que desarrollamos software. En el futuro, veremos modelos de IA cada vez más autónomos, capaces de generar código optimizado y adaptarse a estilos específicos de programación. Sin embargo, la creatividad y el juicio humano seguirán siendo fundamentales para orientar estos sistemas.

Además, la integración de IA en el desarrollo de software permitirá:
- **Automatización inteligente** de pruebas y depuración en tiempo real.
- **Optimización automática** del código para mejorar rendimiento y seguridad.
- **Mayor inclusión**, permitiendo que personas sin experiencia en programación puedan desarrollar soluciones a partir de descripciones en lenguaje natural.

## 5. Notas Finales

Todo el código fué integramente generado por la IA. La única intervención humana fué a través de IA prompting.
Este proyecto es un reflejo de la constante mejora y adaptabilidad que la tecnología nos ofrece. La capacidad de interactuar con un sistema de IA y refinar una idea hasta lograr un producto final funcional y bien estructurado demuestra el potencial de estas herramientas para potenciar la productividad y la creatividad humana. 🚀

