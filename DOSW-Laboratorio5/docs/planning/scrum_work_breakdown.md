# 📄 Planeación del Sistema

## Desglose de trabajo: Épicas, Historias de Usuario y Tareas

La implementación de los requerimientos identificados de Bankify se desglosa de la siguiente manera:

### 1. Épica:

| Campo | Descripción |
|------|-------------|
| **ID** | EP-01 |
| **Título** | Gestionar el estado de cuenta|
| **Descripción** | Porque debe tener la capacidad que el usuario o asesor modifique el estado de cuenta ya sea para crear cuentas (o no habría banco) o eliminarlas por peticion de mi cliente |
| **Stakeholder** | Pues el banco. |

### 2. Historias

| Campo | Descripción |
|------|-------------|
| **ID** | HU-01 |
| **Título** | Confirmación saldo nequi |
| **Descripción** | Como nuevo usuario de Nequi, quiero visualizar el saldo actualizado de mi cuenta tras realizar una recarga, para confirmar que los 5.000 pesos ingresaron correctamente y están disponibles para su uso.|
| **Prioridad** | *[Alta] [Media] [Baja]* |
| **Estimación** | *Puntos de historia* |


| Campo | Descripción |
|------|-------------|
| **ID** | HU-02 |
| **Título** | Historial de retiros en daviplata |
| **Descripción** | Como usuario frecuente de Daviplata, quiero filtrar y consultar mis últimos cinco retiros de efectivo, para llevar un control preciso de mis salidas de dinero recientes.|
| **Prioridad** | *[Alta] [Media] [Baja]* |
| **Estimación** | *Puntos de historia* |


| Campo | Descripción |
|------|-------------|
| **ID** | HU-03 |
| **Título** | Verificación de Obligaciones |
| **Descripción** | Como cliente de Bancolombia con un crédito externo (ICETEX), quiero consultar el estado de mis obligaciones financieras en mi banca en línea, para verificar si el préstamo aparece reflejado como deuda o si mi cuenta de ahorros permanece sin afectaciones. |
| **Prioridad** | *[Alta] [Media] [Baja]* |
| **Estimación** | *Puntos de historia* |


| Campo | Descripción |
|------|-------------|
| **ID** | HU-04 |
| **Título** | Reportes de movimientos |
| **Descripción** | Como titular de una cuenta bancaria, quiero generar una versión imprimible de mi estado de cuenta que incluya el saldo actual y los movimientos recientes, para disponer de un soporte físico o digital de mi actividad financiera. |
| **Prioridad** | *[Alta] [Media] [Baja]* |
| **Estimación** | *Puntos de historia* |

### 3. Tareas:

#### Primera historia de uso: Como nuevo usuario de Nequi, quiero visualizar el saldo actualizado de mi cuenta tras realizar una recarga, para confirmar que los 5.000 pesos ingresaron correctamente y están disponibles para su uso.

| Campo | Descripción |
|------|-------------|
| **ID** | TR-01 |
| **Título** | Altualizacion del saldo despues de la recarga |
| **ID de la Historia de Uso asociada** | HU-01 |
| **Descripción** | Desarrollar uan funcion que permita que el sistema se actualice automáticamente, haciendo que el saldo del usuario una vez se confirme la recarga de $5.000. |
| **Tareas requisito** | Ninguna|

| Campo | Descripción |
|------|-------------|
| **ID** | TR-02 |
| **Título** | visualizar el nuevo saldo en la interfaz |
| **ID de la Historia de Uso asociada** | HU-01 |
| **Descripción** | Diseñar e implementar la seccion donde el usuario pueda observar su saldo actualizado después de la recarga. |
| **Tareas requisito** | TR-01 |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-03 |
| **Título** | Confirmacion visual de la recarga |
| **ID de la Historia de Uso asociada** | HU-01 |
| **Descripción** | implementar un mensaje o comprobante tipo factura visual que confirme la recarga fue exitosa. |
| **Tareas requisito** | TR-01, TR-02 |

#### Segunda Historia: Como usuario frecuente de Daviplata, quiero filtrar y consultar mis últimos cinco retiros de efectivo, para llevar un control preciso de mis salidas de dinero recientes.

| Campo | Descripción |
|------|-------------|
| **ID** | TR-11 |
| **Título** | implementar una consulta de retiros|
| **ID de la Historia de Uso asociada** | HU-02 |
| **Descripción** | Desarrollar la lógica que permita consultar las transacciones de retiros realizados por el usuario.|
| **Tareas requisito** | Ninguna|

| Campo | Descripción |
|------|-------------|
| **ID** | TR-12 |
| **Título** | Aplicar un filtro para mostrar los ultimos cinco retiros |
| **ID de la Historia de Uso asociada** | HU-02 |
| **Descripción** | Implementar un filtro que limite la visualización a los ultimos cinco retiros. |
| **Tareas requisito** | TR-11 |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-13 |
| **Título** | Diseñar la interfaz de visualización de retiros |
| **ID de la Historia de Uso asociada** | HU-02 |
| **Descripción** | Diseñar o adaptar una pantalla donde el usuario pueda visualizar los últimos cinco retiros. |
| **Tareas requisito** | TR-11 |





