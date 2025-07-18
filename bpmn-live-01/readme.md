Gestión de Reclamos

Cada año, la agencia de viajes XY tiene que procesar un lote de reclamos (cerca de 1000). Hay un departamento especial para el proceso de reclamos (Departamento C), además, hay un departamento interno llamado logística (Departamento L) el cual se encarga de registrar los reclamos que llegan y archivar los reclamos procesados. El siguiente proceso es utilizado para manejar los reclamos:
Primero, un empleado del departamento de Logística registra cada reclamo que se presente.
Después del registro, un empleado del departamento de reclamos envía un formulario al cliente con preguntas acerca de la naturaleza del reclamo. Hay dos posibilidades: que el cliente devuelva el formulario dentro de las dos semanas siguientes o que no lo haga. Si el formulario es devuelto, este es procesado automáticamente, resultando en un reporte que puede ser usado por el proceso actual de reclamos. Si el formulario no es devuelto a tiempo, un time-out ocurre, resultando en un reporte vacío. Tenga en cuenta que no recibir el formulario no implica la terminación del proceso ni que el reclamo sea descartado. Después del registro, es decir, en paralelo con el envío y recepción del formulario, comienza la preparación del proceso.
Primero, el reclamo es evaluado por el director de reclamos del departamento C. La evaluación indicará si es requerido un procesamiento adicional. Si no se requiere procesamiento adicional y ya se procesó el formulario, el reclamo es archivado. Si un procesamiento adicional es requerido, un empleado del departamento de reclamos ejecuta la tarea “Procesar Reclamo” (en esta actividad se proponen acciones necesarias para dar solución al reclamo). Para procesar el reclamo, el reporte resultante del formulario es utilizado.
Tenga en cuenta que el reporte puede estar vacío. El resultado de la tarea “Procesar Reclamo” es analizado por el director de reclamos. Si el resultado no es OK, la tarea “Procesar Reclamo” es ejecutada nuevamente. Esto es repetido tantas veces hasta que el resultado es aceptado. Si el resultado es aceptado, un empleado del departamento C ejecuta las acciones propuestas. Después de esto, el reclamo es archivado por un empleado del departamento L.

Requerimientos

1. Se requiere diseñar un modelo BPMN que responda al contexto, teniendo en cuenta la legibilidad y consistencia.
2. Validar el modelo a través de simulación por token.

