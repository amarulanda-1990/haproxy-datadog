#Proyecto Telematia UAO
#Estudiantes:    Adrian Varela Rendon, Andres Felipe Marulanda
                
#Descripción: Este proyecto consiste en la implementación de un Cluste de servidores que contiene HaProxy con la función de balanceador de carga, se utilizará el DataDog como herramienta de monitoreo y análisis de métricas, para el entorno de prueba se desarrolla dos servidores web utilizando NGix. Se utiliza un ambiente de trabajo en Vagrant todo bajo Centos 8.


#Entorno: 
3 maquinas virtuales Centos 8 administradas desde Vagrant como entorno de trabajo
VM1 ip: 192.168.50.5 (HaProxy, DataDog)
VM2 ip: 192.168.50.6 (Ngix Servidor web 1)
VM3 ip: 192.168.50.7 (Ngix Servidor web 2)

Ejecutamos en el siguiente orden(tomamos el Vagrantfile):

1.  Instalamos el HaProxy Instructivo: VM1-haproxy
2.  Instalamos el Nginx Instructivo: VM2-ngix
3.  Instalamos el Nginx Instructivo: VM3-ngix
4.  Creamos la cuenta en DataDog ejecutamos el proceso segun el instructivo: VM1-agentedatadog y procedemos con la integración
5.  Finalmente probamos en los navegadores del anfitrión 
