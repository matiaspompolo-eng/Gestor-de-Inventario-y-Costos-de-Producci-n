Gestor de Inventario y Costos de Producción

Aplicación de escritorio desarrollada para la gestión de componentes, materiales y costos de producción de tres equipos electrónicos específicos: efeSIM, efeTEST y efeMora.
La aplicación permite centralizar la información necesaria para conocer tanto la composición de cada equipo como su costo real de producción por unidad, teniendo en cuenta materiales, mano de obra, logística, shipping y gastos de aduana.

Objetivo
El objetivo de la aplicación es simplificar y centralizar el cálculo de costos de producción de equipos electrónicos, evitando realizar manualmente los cálculos de materiales, mano de obra y logística.
De esta forma, permite tener una referencia rápida y actualizada del costo necesario para fabricar cada unidad y facilita la gestión de los componentes necesarios para su producción.

Gestión de componentes y materiales
La aplicación cuenta con una base de datos local SQLite3 para almacenar y administrar la información de los componentes utilizados en cada equipo.
Para cada componente es posible registrar información como:
  ->Equipo al que pertenece.
  ->PCB.
  ->Componente.
  ->Footprint.
  ->Valor.
  ->Cantidad utilizada.
  ->Proveedor.
  ->Cantidad mínima de compra.
  ->Precio unitario.
  ->Precio total.
  ->Método de colocación.
  ->Link de compra.
Los registros pueden ser agregados, modificados y eliminados desde la interfaz de la aplicación.

Acceso directo a proveedores
Cada componente puede tener asociado un enlace de compra.
Al realizar doble clic sobre el enlace, la aplicación abre automáticamente el navegador y redirige al sitio correspondiente del proveedor, facilitando la consulta y adquisición de los materiales.

Gestión de proveedores y logística
La aplicación identifica automáticamente los diferentes proveedores utilizados por cada equipo.
Esto permite ingresar los costos asociados a:
  ->Shipping.
  ->Aduana.
De esta manera, los gastos logísticos pueden incorporarse al cálculo final del costo de producción.

Cálculo del costo de producción
El sistema permite calcular el costo de fabricación de cada equipo considerando diferentes etapas del proceso productivo:
  ->Fabricación.
  ->Ensamblado.
  ->Envío.
  ->Packaging.
Para cada etapa se pueden establecer las horas de trabajo y el costo por hora, permitiendo obtener el costo correspondiente a la mano de obra.

Generación de informes

Una de las funcionalidades principales es la generación de un informe detallado de costos de producción.
El reporte incluye:
  ->Desglose de materiales.
  ->Subtotal de componentes electrónicos.
  ->Costo de PCBs.
  ->Mano de obra y tiempos de producción.
  ->Costos de shipping.
  ->Gastos de aduana.
  ->Total de gastos logísticos.
  ->Costo total de producción por unidad.
Esto permite obtener una visión completa de cuánto cuesta producir cada unidad del equipo.
