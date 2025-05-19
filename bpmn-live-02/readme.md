Solicitud de Crédito

Suponemos una organización que recibe solicitudes (a través de formularios) de clientes para otorgamiento de crédito, La empresa realiza una evaluación, y en función de eso comunican el rechazo o aprobación de la solicitud de crédito. Ahora asumamos que queremos representar el hecho de que un cliente contacta la empresa para pedir un formulario de solicitud, la empresa se lo envía y activa un temporizador para enviarle un recordatorio al cliente si no recibe la solicitud en un periodo de tiempo de siete días. Para que la empresa no se encuentre con iteraciones infinitas, puesto que un formulario de solicitud podría no llegar nunca, decide establecer un contador de iteraciones en la espera del formulario para que si se ha avisado al cliente ya tres veces se archiven los detalles del pedido de solicitud y no se espere más el formulario. Se decide contemplar la situación de que el cliente informe que no está interesado en realizar la solicitud de evaluación una vez que recibe el formulario. En ese caso, al igual que cuando se le envía recordatorio 3 veces se archivan los detalles del pedido de solicitud.

Requerimientos

1. Se requiere diseñar un modelo BPMN que responda al contexto, teniendo en cuenta la legibilidad y consistencia.
2. Validar el modelo a través de simulación por token.
