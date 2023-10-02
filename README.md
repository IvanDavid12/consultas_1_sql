# consultas_1_sql
# introductorio a la consulta de una base de datos usando el lenguaje SQL

## base de datos: ventas 

# tabla: clientes


![tabla cliente](tabla_cliente.png "clientes")


## instruccion SELECT

- permite seleccionar datos de una tabla
- su formato es : "SELECT campos tabla FROM nombre tabla"

## consulta No . 1
1. para visualizar la informacion que contiene  la tabla cliente se puede incluir con la instruccion SELECT el caracter **\*** o cada uno de los campo de las tablas 

- ´SELECT * FROM clientes´

![consulta 1](consulta_1.png "consulta")

- ´ŚELECT identificacion, nombre, apellidos, dirreccion, telefono, ciudad nac, fecha nac FROM cliente´

![consulta 1-2](consulta_2.png "consulta")

### consulta No .2
para visualizar solamente la identificacion de cliente 

![consulta 2](consulta_3.png "consulta")
### consulta No. 3
si se desea obtener los registros cua identificacion sea mayor o igual a 150, se debe utilizar la clasula (WHERE) que especifica las condiciones que debe reunir los registros que se van seleccionando ´SELECT * FROM cliente WHERE identificacion>=150´

![consulta 3](consulta_4.png "consulta")