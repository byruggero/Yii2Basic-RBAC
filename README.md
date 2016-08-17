1.-Crear una base de Datos vacia en MYSQL.

2.-Primer lugar es ejecutar migraciones Yii que crearan nuestra base de datos vacía.En la consola y ejecutar las migraciones Yii:
	accedemos a la carpeta de nuestro proyecto, se configura la conexion a la base de datos anteriormente creada:
	$	cd /proyecto
	ejecutamos el codigo de la migracion de Yii2:	
	$	./yii migrate
	ejecutamos el comanto que invocara la creacion de las acciones de RBAC dentro de la base de datos y los controladores
	$	./yii rbac/init







