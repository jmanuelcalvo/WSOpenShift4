# Workshop OpenShift Conceptos Generales

## Arquitectura de referencia


![Ref](Base%20OpenShift%20Diagram%20-%20Arch%20Pods.png)


## Antes de iniciar
Antes de iniciar, tenga en cuenta que a este workshop ingresaran varias personas, por lo que previo a esto es necesario que cada uno seleccione un numero de usuario y con este trabajara durante todos los talleres
Ejemplo:

* user01 - Jose Manuel Calvo
* user02 - Diego Saenz
* user03 - Tatiana Gomez
* user04 - Luisa Mendez

y asi sucesivamente, una vez tenga **su usuario**, durante los talleres reemplaze **userXX** por **user04** (o su usuario asignado)

Las contraseñas de los usuarios tanto por SSH como por consola seran redhat01

## Por Navegador
```
https://loadbalancer.0f40.example.opentlc.com/
```

## Acceso por SSH a la maquina Bastion
```
ssh user0X@bastion.0f40.example.opentlc.com
oc login https://loadbalancer.$GUID.internal:443 -u user0X -p redhat01
```


## Facilitador / Consultor Red Hat
Jose Manuel Calvo I


# Laboratorios
[Taller 1](talleres/taller1.md) - Iniciando con OpenShift - Explorando OpenShift (proyectos, apps, svc, routes)

[Taller 2](talleres/taller2.md) - Volumenes Persistentes, ConfigMap y Secrets

[Taller 3](talleres/taller3.md) - Aplicaciones complejas (FrontEnd + BD + Datos Persistentes)

[Taller 4](talleres/taller4.md) - Trabajo con contenedores Docker

[Taller 5](talleres/taller5.md) - Backup de OpenShift

[Taller 6](talleres/taller6.md) - Tareas automatizadas con Ansible, Primeros pasos

[Taller 7](talleres/taller7.md) - Tareas de Operacion de OpenShift



------------

# Workshop Despliegue de aplicaciones en OpenShift

## Imagen de referencia


![Ref](deploy.png)




# Laboratorios

[Taller 1](talleresd/taller1.md) - Despliegue de aplicaciones desde Docker y s2i

[Taller 2](talleresd/taller2.md) - Uso de repositorios GIT

[Taller 3](talleresd/taller3.md) - Configuracion de limites y quotas en los pods

[Taller 4](talleresd/taller4.md) - Configuracion de Rutas - Estrategias de despliegues avanzadas

[Taller 5](talleresd/taller5.md) - Monitoreo y Logs

[Taller 6](https://github.com/dudash/openshiftexamples-autoscaling) - Autoescalamiento



------------
# Varios  




# Backup OpenShift
### Ver taller 5

