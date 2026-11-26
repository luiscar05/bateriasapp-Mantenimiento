## Epica 1 - Clientes

### HU-001: Registrar Usuarios
**Como** Personal de Atencion
**Quiero** registrar los datos de contacto y facturación de un cliente
**Para** no volver a pedirlos por WhatsApp en cada pedido.

**Cristerios de aceptacion:**
- [] Dado el formulario de cliente, cuando ingreso nombre, teléfono y datos de facturación válidos, entonces el cliente queda guardado y aparece en el listado.

- [] Dado que dejo vacío nombre o teléfono, cuando intento guardar, entonces el sistema indica el campo faltante y no guarda.

- [] Dado un teléfono ya registrado, cuando intento crear otro cliente con el mismo, entonces el sistema avisa del duplicado y ofrece abrir el existente.


