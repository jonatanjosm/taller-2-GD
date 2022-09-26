
# Taller #2

Segundo taller de la materia Gestión de datos.

## Integrantes

- Marysabel Mejia
- Jonatan Murcia


## Primer punto

Descripción general de la colección de datos escogida

### Sample Supply Store Dataset

El set de datos escogido contiene información acerca de las compras realizadas en diversas sucursales de una compañía de venta de elementos de oficina. También, se puede encontrar información relevante acerca de los clientes. La base de datos contiene solo una colección (‘sales’) y cada documento contenido en la colección ‘sample_supplies.sales’ representa una única compra realizada en alguna de las tiendas de la empresa. Para cada compra, se almacena la siguiente información acerca de la compra, los artículos comprados y el comprador:
- ‘_id’: Llave única de identificación de la compra
- ‘saleDate’: fecha en la cual se realizó la compra
- ‘items’: listado de artículos comprados. Para cada artículo se almacena la siguiente información:
    - ‘name’: nombre del artículo
    - ‘tags’: categorías asociadas al artículo
    - ‘price’: precio
    - ‘quantity’: cantidad de veces que se llevó el artículo en esta compra
- ‘storeLocation’: ubicación (ciudad) de la sucursal en la cual se realizó la compra
- ‘customer’: información acerca del comprador:
    - ‘gender’: género
    - ‘age’: edad
    - ‘email’: correo electrónico
    - ‘satisfaction’: nivel de satisfacción del cliente
- ‘couponUsed’: variable booleana que indica si es usó (true) o no (false) un cupón
- ‘purchaseMethod’: método de compra

## Segundo punto
Definición de las 3 preguntas de negocio que se quieren responder.
### 1.	¿Cómo se comportan las ventas de cada categoría de productos en cada mes del año?

Las dos categorías que más se venden durante todo el año son ‘office’ y ‘school’. La época en la que más veces se compra este tipo de artículos es en los tres últimos meses del año, seguido de los meses marzo y mayo. Los meses febrero, abril y septiembre presentan caídas significativas en las ventas de estos artículos. Por otro lado, los artículos que menos veces se compran son aquellos que pertenecen a las categorías ‘electronics’ y ‘travel’.


### 2.	¿Cómo cambia la proporción de compras realizadas con cada método de pago con respecto al rango de edad de los clientes?

En todas las categorías de edad la proporción de uso de los métodos de compra es similar, siendo la compra en tienda física el método más usado en cada rango de edad. Adicionalmente, se evidenció que los clientes entre 30 y 50 años son quieres hacen más compras únicas en las tiendas de la compañía, seguidos del grupo de clientes entre 50 y 60 años. Los clientes menos frecuentes son aquellos que cuya edad está entre 10 y 20 años y entre 70 y 80 años. 

### 3.	¿Cómo cambia el nivel de satisfacción de los clientes con respecto a la tienda donde realizaron la compra?

Se evidenció que todas las sucursales tienen exactamente la misma proporción de satisfacción de los clientes. En general, el nivel de satisfacción que manifiestan los clientes es muy alto, pues más del 60% de ellos expresa que su nivel de satisfacción es 4 o 5.  Los clientes que marcaron las categorías 1 y 2, que manifiestan el mínimo nivel de satisfacción, no representan más del 20% del total de compradores en cada ciudad. Lo anterior, es un buen indicador de que la atención al cliente es satisfactoria en la mayoría de los casos. Adicionalmente, se evidenció que las ciudades con mayor cantidad de compras únicas son Denver y Seattle, mientras que la ciudad con menor cantidad de compras es San Diego. 


