# Configuración del sitio web iRunner

## Realizar copias de seguridad

Ejecutar:

`drush sql-dump --gzip --structure-tables-list=cache,cache_*,watchdog > ../backups/bd_irunner.sql.gz`

Realizamos una copia excluyendo todas las base de datos: 
- cache
