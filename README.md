# HomeLab Cloud

## De que va este proyecto?
Es un servidor que comienza desde Linux WSL2 hasta AWS.

## Porque tiene esta estructura?
Cuenta con el principio de menor privilegio: cada uno de los usuarios solo tendra acceso a lo que necesiten.

## Estructura del proyecto
- /proyectos: trabajo activo (775 – solo equipo y lectura invitado)
- /backups: respaldos criticos (700 – solo admin)
- /logs: registros del sistema (750 – lectura equipo)
- /scripts: automatizacion (755 – ejecutable por todos)
