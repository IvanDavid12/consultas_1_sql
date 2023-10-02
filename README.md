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

![consulta 2](consulta_2.png "consulta")

### consulta No .2
para visualizar solamente la identificacion de cliente 

![consulta 3](consulta_3.png "consulta")