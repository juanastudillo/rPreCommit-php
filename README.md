Para PHP que utiliza las siguientes herramientas:

1-PHP-CS-Fixer: Para corregir y formatear el código según un estándar.

2-PHPStan: Para realizar un análisis estático y encontrar posibles errores.


Cada repositorio de Git tiene un directorio de hooks (.git/hooks). Git almacena una serie de scripts de ejemplo con la extensión .sample en este directorio. Para empezar, navega a la raíz de tu proyecto y luego a este directorio:

cd .git/hooks


Aca ya puedes crear tu archivo pre-commit

touch pre-commit


Asegúrate de que el script tenga permisos para ejecutarse:

chmod +x pre-commit
