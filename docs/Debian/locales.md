---
layout: default
title: Generar locales Debian
parent: Debian
nav_order: 3
---
## Instalación nuevos locales en Debian
Revisamos los locales que tenemos generados en el sistema:
``` bash
locale -a
```
Podemos generar más editando /etc/locale.gen y descomentando la línea que nos interesa:
``` bash
es_ES.UTF-8 UTF-8
```

Generamos nuevamente los locales con:
``` bash
locale-gen
```
Hacemos el cambio en "Region & Language"

![Screenshot from 2022-12-28 17-42-40.png](/pictures/1.png)


![Screenshot from 2022-12-31 12-34-31.png](/pictures/2.png)
