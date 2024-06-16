# Analisis de ventas de un supermercado

**Bibliotecas usadas**
- import pandas as pd
- import matplotlib.pyplot as plt
- import seaborn as sns
- import numpy as np

**Direccion de dataset**
- url = 'https://raw.githubusercontent.com/AaronE08/datasets/main/supermarkets/supermarket.csv'

**Datos del dataset**

- ID de factura: Un identificador único para cada transacción.
- Sucursal: La tienda o local donde se realizó la transacción.
- Ciudad: La ciudad donde se encuentra la sucursal.
- Tipo de cliente: La clasificación del cliente (por ejemplo, miembro, no miembro).
- Género: El género del cliente.
- Línea de productos: La categoría del artículo comprado.
- Precio unitario: El costo por artículo individual.
- Cantidad: El número de artículos comprados.
- Impuesto 5%: La cantidad de impuesto aplicado a la compra (5% del costo total).
- Total: La cantidad final pagada, incluyendo impuestos.
- Fecha: La fecha en que ocurrió la transacción.
- Hora: La hora en que ocurrió la transacción.
- Pago: El método de pago utilizado (por ejemplo, efectivo, tarjeta de crédito).
- cogs (costo de bienes vendidos): Los costos directos atribuibles a la producción de los bienes vendidos.
- porcentaje de margen bruto: La diferencia porcentual entre el costo de bienes vendidos y los ingresos por ventas.
- ingreso bruto: La ganancia obtenida de la transacción antes de deducir cualquier gasto.
- Calificación: La valoración del cliente sobre su experiencia de compra.

**Cuenta con 1000 lineas y 11 columnas**

**Hallazgos General y separados por ciudad**

**General**

- Comportamiento de compra por género: Las mujeres parecen ser las principales consumidoras en este contexto, lo que podría indicar que los productos o la experiencia de compra atraen más a las mujeres.
- Método de pago preferido: El efectivo es el método de pago más utilizado. Esto podría sugerir que los clientes prefieren pagar en efectivo o que hay una oportunidad para aumentar las ventas promoviendo más los pagos digitales.
- Tipo de cliente: Los miembros son más frecuentes que los clientes normales, lo que podría indicar que el programa de membresía es atractivo para los clientes y podría ser una buena área para seguir invirtiendo.
- Ventas por ciudad: Naypyitaw es la ciudad con más ventas, lo que podría sugerir que esta ciudad tiene una gran demanda de los productos o que las estrategias de marketing están funcionando bien allí.
- Línea de producto más vendida: Los alimentos y bebidas son los productos más vendidos. Esto podría indicar que estos productos son muy populares entre los clientes y podrían ser el foco principal para futuras estrategias de marketing y ventas.
Las mujeres se unen mas a la membresia que los hombres

**Por ciudad**

- En Mandalay los hombres compran mas que las mujeres,el tipo de cliente es mas frecuente el cliente noirmal que miembros.El pago mas usado es Ewallet y su producto mas vendido es sport and travel.
- En Naypytaw las mujeres compran mas, el cliente mas frecuente son los miembros, el metodo de pago mas usado es cash y el producto mas vendido es "Food and beverages"
- Yangon los hombres compran mas, los clientes mas frecuentes son los normales, el metodo de pago mas usado es Ewallet y el producto mas vendido es "Home and lifestyle"
