# Proyecto: AgendaSalud

## 1. El Problema (Discovery)

### ¿Qué duele?

Hace un mes tuve que sacar una cita para mi abuelo, el cual es un adulto mayor. Por lo que tuve que hacer una fila para recibir un turno y, al momento del llamado del respectivo turno, me dijeron que estas citas aún no estaban habilitadas, perdiendo tiempo desde las 5:00 a.m. hasta las 8:00 a.m.

### Frecuencia

Es un problema recurrente: 3.82

### La Solución Soñada

Una aplicación web en la que por lo menos se pueda ver la disponibilidad de las citas antes de asistir presencialmente.

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