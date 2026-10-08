# Datos crudos de tesis: fallas de motor por OBD-II

Lecturas OBD-II en crudo de vehículos ligeros de gasolina en Arequipa, con fallas de motor inducidas de forma controlada y el estado sin falla de cada vehículo como referencia. **En recolección**: corte al 8 de octubre de 2026.

| | |
|---|---|
| Vehículos | 9 |
| Atenciones | 37 (28 válidas) |
| Filas de lectura | 5 990 |
| Clases | C0 sin falla, C1 encendido, C2 mezcla aire y combustible, C3 admisión de aire |

`crudo/lecturas_crudas_etiquetadas.csv` tiene cada lectura con su vehículo, régimen y clase; `crudo/atenciones.csv`, una fila por atención con su etiqueta y validez; `crudo/modo06_etiquetado.csv`, los contadores de fallo de encendido. Sin placa, VIN ni datos del propietario.

Luis Enrique Torres Quispe, UCSM.
