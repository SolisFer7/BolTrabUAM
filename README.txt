1. Instalar base de datos con el respaldo 
2. establecer la cadena de conexion correspondiente en el archivo de configuración del sitio web.
3. ingresar

CONSULTA PARA LOS USUARIOS (Guardados en la base de datos):

select b.UserName,a.Password  from dbo.aspnet_Membership as a inner join aspnet_Users as b
on a.UserId = b.UserId 

