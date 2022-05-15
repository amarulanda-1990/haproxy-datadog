#Proyecto Telematia UAO
#Estudiantes:    Adrian Varela Rendon, Andres Felipe Marulanda
                
#Descripción: Este proyecto consiste en la implementación de un servidor HaProxy con la función de balanceador de carga, se utilizará el DataDog como herramienta de monitoreo y análisis de métricas, para el entorno de prueba se desarrolla dos servidores web utilizando NGix. Se utiliza un ambiente de trabajo en Vagrant todo bajo Centos 8.


#Entorno: 
3 maquinas virtuales Centos 8 administradas desde Vagrant como entorno de trabajo
VM1 ip: 192.168.50.5 (HaProxy, DataDog)
VM2 ip: 192.168.50.6 (Ngix Servidor web 1)
VM3 ip: 192.168.50.7 (Ngix Servidor web 2)
