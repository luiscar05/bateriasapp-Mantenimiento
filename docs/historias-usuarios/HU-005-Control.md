## Epica 2 - Productos e inventario

### HU-005: Control automático de Inventario
**Como** Propietario
**Quiero** que el inventario baje al facturar un pedido
**Para** saber lo que realmente tengo.

**Cristerios de aceptacion:**
- [] Dado un pedido facturado con N unidades, cuando se confirma, entonces la cantidad disponible disminuye en N..

- [] Dado un pedido con más unidades de las disponibles, cuando intento facturarlo, entonces el sistema lo advierte y no permite continuar sin corregir.

- [] Dado un pedido cancelado antes de entregar, cuando se cancela, entonces las unidades regresan al inventario.


