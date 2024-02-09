# BBDD-AdvancedQueries-Views-SQL
Diseño y Programación de una BBDD (MySQL)

ACTIVIDAD:

Resolver con Combinaciones Externas
Mostrar aquellos socios que no se han inscrito en ninguna actividad.
El listado deberá mostrar los siguientes campos: idSocio, Nombre, Apellido1, Fecha de Alta.

Mostrar aquellos monitores sin horas asignadas.
El listado deberá mostrar los siguientes campos: id, nombre, apellidos, titulación(es), teléfono fijo, teléfono móvil.

Mostrar una lista con todos los monitores tengan o no horas asignadas
Mostrar una lista de socios que han sido recomendados el id, nombre y apellido de quien lo ha recomendado.

Resolver con Subconsultas
Mostrar el idSocio, nombre, apellido1, apellido2 y la fecha de alta del socio corporativo más antiguo del gimnasio.

Indicar la sala (instalación) con el horario más reciente ocupado

Indicar cuál es la sala con el aforo más pequeño

Resolver con Consultas de UNION

Crear una consulta de UNION producto de la combinación de las siguientes cuatro consultas: 
Altas del mes: idSocio, Concepto="Matrícula", Mes, Año, Matrícula

Para aquellos socios que se han dado de alta en el mes y año especificado
Cuotas: idSocio, Concepto="Cuota Mensual", Mes, Año, CuotaMensual
Descuento: idSocio, Concepto="Descuento", MesDcto, AñoDcto, Importe

De la tabla Decuento
Actividades Extra: idSocio, Concepto="Extra", Mes, Año, precioSesión

De la tabla Actividades
Crear una consulta de UNION producto de la combinación de las siguientes dos consultas: NIF, NombreEmpresa, Teléfono, EMail, DNI, Nombre+Apellidos Socio, Teléfono, EMail. Sólo socios principales

Resolver con Vistas
Utilizando la consulta de UNION del punto anterior más la tabla de Socios, crear una vista que agregue los campos idSocio, nombre Completo, Plan y NIF (en caso de ser un socio corporativo). Grabar la vista con el nombre Facturación

Crear una vista a partir de la tabla HORARIOS que muestre el día de la semana (Lunes-Domingo), fecha, hora y nombre de la actividad
