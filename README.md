# SQLITE - COMANDOS 
## BASE DE DATOS
### **Tablas creadas y insercion de datos**
![image](https://github.com/juanpisjaja/Sqlitre3/blob/main/IMG/tablas.png)
![image](https://github.com/juanpisjaja/Sqlitre3/blob/main/IMG/insertar.png)
## UPDATE :
>La sentencia UPDATE se utiliza para actualizar 
![image](https://github.com/juanpisjaja/Sqlitre3/blob/main/IMG/update.png)
***
## ESTRUCTURA DE LA BASE DE DATOS .SCHEMA :
>Basciamente es pare ver las tablas con sus colomnas 

![image](https://github.com/juanpisjaja/Sqlitre3/blob/main/IMG/schema.png)
***
## DATE AND TIME :
**TEXTO** como cadenas ISO 8601 ("YYYY-MM-DD HH:MM:SS.SSS").

**REAL** como números de días julianos, el número de días desde el mediodía en Greenwich el 24 de noviembre de 4714 aC según el calendario gregoriano proléptico. 

**INTEGER** como Unix Time, el número de segundos desde 1970-01-01 00:00:00 UTC.
### SQLite admite seis funciones de fecha y hora de la siguiente manera:
1.	fecha ( valor de tiempo, modificador, modificador, ... )
2.	tiempo ( valor de tiempo, modificador, modificador, ... )
3.	fecha y hora ( valor-hora, modificador, modificador, ... )
4.	julianday( tiempo-valor, modificador, modificador, ... )
5.	unixepoch( valor-tiempo, modificador, modificador, ... )
6.	strftime( formato, valor de tiempo, modificador, modificador, ... )

![image](https://github.com/juanpisjaja/Sqlitre3/blob/main/IMG/date%20and%20time.png)
***
## PRIMARY KEY CONSTRAINT :
La llave primaria hace referencia a la clave principal de la tabla, esta es la que hace unica la tabla la que la diferencia de las demas 

![image](https://github.com/juanpisjaja/Sqlitre3/blob/main/IMG/tablas.png)
***
## NOT NULL CONSTRAINT :}
>La restricción NOT NULL impone una columna para NO aceptar valores NULL.

*  Esto obliga a que un campo siempre contenga un valor, lo que significa que no puede insertar un nuevo registro o actualizar un registro sin agregar un valor a este campo.

![image](https://github.com/juanpisjaja/Sqlitre3/blob/main/IMG/not%20null.png)
***
## UNIQUE CONSTRAINT :
>La restricción UNIQUE asegura que todos los valores en una columna son diferentes.

* Las restricciones UNIQUE y PRIMARY KEY proporcionan una garantía de exclusividad para una columna o conjunto de columnas.

![image](https://github.com/juanpisjaja/Sqlitre3/blob/main/IMG/unique.png)
***
## DEFAULT CONSTRAINT :
>La restricción DEFAULT se usa para proporcionar un valor predeterminado para una columna.

* El valor predeterminado se agregará a todos los registros nuevos SI no se especifica ningún otro valor.
* **CREATE TABLE Orders (**
    **ID int NOT NULL,**
    **NumeroPedido int NOT NULL,**
    **FechaPedido date DEFAULT GETDATE()**
);

![image](https://github.com/juanpisjaja/Sqlitre3/blob/main/IMG/default.png)
***
## ALTER TABLE :
>ALTER TABLE es una sentencia que se usa para añadir, modificar o borrar columnas en una tabla que ya existe en tu bbdd. También se puede usar para añadir y eliminar algunas restricciones en una tabla.

![image](https://github.com/juanpisjaja/Sqlitre3/blob/main/IMG/alter1.png)

![image](https://github.com/juanpisjaja/Sqlitre3/blob/main/IMG/alter2.png)
***
## DROP :
>La sentencia DROP TABLE se utiliza para eliminar una base de datos SQL existente.

![image](https://github.com/juanpisjaja/Sqlitre3/blob/main/IMG/drop.png)
***
## DELETE :
>La declaración DELETE se utiliza para eliminar registros existentes en una tabla de SQL.

![image](https://github.com/juanpisjaja/Sqlitre3/blob/main/IMG/delete.png)
***
## CHECK CONSTRAIN :
>La restricción CHECK en SQL se usa para limitar el rango de valores que se puede colocar en una columna, por ejemplo, Si define una restricción CHECK en una sola columna, solo se permiten ciertos valores para esta columna. De esta manera se pueden evitar errores al no introducir valores erróneos.

![image](https://github.com/juanpisjaja/Sqlitre3/blob/main/IMG/check.png)
***
## BACKUP-RESTORE :
>La sentencia BACKUP DATABASE se usa en SQL Server para crear una copia de seguridad completa de una base de datos SQL existente.

* Es muy útil ya que podemos borrar una tabla importante de una bbdd
sin querer hacerlo mientras trabajamos, por ello, en ocasiones necesitamos o deberíamos realizar un BACKUP DATABASE o backup de la base de datos para ser cautelosos y tener una copia de seguridad de la base de datos en SQL para cuando la necesitemos.

![image](https://github.com/juanpisjaja/Sqlitre3/blob/main/IMG/BAKCUP.png)
***

























