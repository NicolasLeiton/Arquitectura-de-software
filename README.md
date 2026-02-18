# Proyecto: AgendaSalud

## 1. El Problema (Discovery)
### Problemas más comunes según la encuesta:
![Distribución de las áreas del problema](imagenes/area_problema.png)
### ¿Qué duele?

1. Hace un mes tuve que sacar una cita para mi abuelo, el cual es un adulto mayor. Por lo que tuve que hacer una fila para recibir un turno y, al momento del llamado del respectivo turno, me dijeron que estas citas aún no estaban habilitadas, perdiendo tiempo desde las 5:00 a.m. hasta las 8:00 a.m.
2. Agendas de citas médicas hasta dentro de varios meses o que no haya agenda. Entrega de medicamentos con filas de hasta horas.

### Frecuencia

Es un problema recurrente: 3.82

![Frecuencia del problema](imagenes/frecuencia_problema.png)

### La Solución Soñada

1. Una aplicación web en la que por lo menos se pueda ver la disponibilidad de las citas antes de asistir presencialmente.
2.	Una plataforma que puede conectarse con las eps o con servicios particulares donde se pueda agendar cita fácilmente, esta se registre en un calendario con alertas o que la plataforma pueda mandar alertas o programar citas automáticamente cada que haya agenda (con la posterior aprobación del usuario) y que además pueda funcionar como app de delivery para pedir y programar entregas rápidas, sin que sea complicada de usar.
## Definición Funcional

### Historia de usuario principal
Como paciente quiero consultar la disponibilidad de las citas para ahorrar tiempo en filas y desplazamientos al ir presencialmente.

### Criterios de aceptación
- El tiempo de carga debe ser menor a 2 segundos.
- Debe contar con una base de datos que se actualice constantemente.
- La información mostrada debe ser consistente con la base de datos.
- La aplicación debe ser responsive (usable en dispositivos móviles).
- Debe contar con una interfaz intuitiva.

### Requisitos funcionales
- **RF-01:**  El sistema debe permitir autenticación mediante login seguro.
- **RF-02:**  El sistema debe conectarse a una base de datos centralizada para consultar y actualizar información.
- **RF-03:** El sistema debe permitir consultar disponibilidad de citas por fecha.
- **RF-05:** El sistema debe permitir visualizar el estado de una cita (ej: disponible, asignada, no disponible, no autorizada).
- **RF-06:** El sistema debe permitir a un administrador gestionar la disponibilidad de citas.