# Requerimientos no funcionales

| # | Atributo | Métrica | Umbral | Condición de carga | Verificación | Consecuencia si no se cumple |
|---|---|---|---|---|---|---|
| 1 | Rendimiento | Tiempo de respuesta | Menor a 3 segundos | 50 usuarios concurrentes | Prueba de carga | Mala experiencia del usuario |
| 2 | Disponibilidad | Tiempo activo | 99% mensual | Horario normal de operación | Monitoreo del sistema | Pérdida de citas |
| 3 | Seguridad | Accesos no autorizados | 0 incidentes críticos | Operación normal | Auditoría y pruebas | Exposición de datos de clientes |

## Escenario 1

- Fuente: Cliente
- Estímulo: Solicita una reserva de cita.
- Artefacto: Aplicación web TurnoFácil.
- Entorno: Operación normal.
- Respuesta: El sistema registra la cita correctamente.
- Medida: La operación debe completarse en menos de 3 segundos.