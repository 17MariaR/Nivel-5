### CREACION DE GRUPO DE RECURSOS

Permite que haya comunicacion entre recursos creados (como maquinas virtuales, aplicaciones web y bases de datos)

## Es de utilidad cuando:

- Se crean y configuran redes virtuales desde el portal de Azure, Azure powershell, Azure CLI, Azure Cloud o plantillas ARM
- Comunicacion entre usuarios de internet, recursos de Azure y recursos locales
- Hay conexion de Redes virtuales
- Filtrar el trafico de redes

## Costos

El costo es variable segun lo que se utilice y por cuanto tiempo esta activo el recurso
Consultar la [calculadora de costos](https://azure.microsoft.com/es-mx/pricing/calculator/)

## Procedimientos

Ingresar a [Portal de Azure](https://portal.azure.com/#home) e iniciar sesion

**Crear un grupo de recursos**

![image text](I1S5.png)

**Crear redes virtuales**

![image text](I2s5.png)

**Crear subred**

![image text](I3s5.png)

Crear una segunda subred 

![image text](I4s5.png)

**Creacion de dos maquinas virtuales**

![image text](I5s5.png)
![image text](I6s5.png)

Conectarlas

![image text](I7s5.png)

Emparejamiento de VN (redes)

![image text](I8s5.png)

Probar el funcionamiento de emparejamiento de las vn a traves de Azure Powershell

![image text](I9s5.png)
