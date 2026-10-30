```mermaid
graph TD
    A[Desencadenador: Nuevo Correo o Llamada] --> B[Acción: Obtener Caso relacionado]
    B --> C{Condición: ¿Primera respuesta enviada = No?}
    C -- Sí --> D[Acción: Actualizar Caso a Sí]
    C -- No --> E[Fin: No se requiere acción]