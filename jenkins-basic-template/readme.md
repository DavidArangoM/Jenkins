# Jenkins Basic Template

**[ENGLISH VERSION]**

This template shows a basic configuration for a Jenkinsfile with only a two example stages


## Key concepts

 - **Agent:** Compute resource where the stages will be executed, e.g.:
	 - The same machine where Jenkins is installed.
	 - An external machine on-premise or in the cloud.
	 - A docker container.
	 
 - **Stage:** Business-related steps that show an ordered sequence, e.g.:
	 - Build
	 - Test
	 - Deploy
	 
 - **Step:** Bunch of necessary commands to achieve the business stages, e.g.:
	 - Step to achieve the build stage:
		 - Get date and time
		 - Get environment variables
		 - Inject those environment variables into te source code
		 - Execute the build command


## Use cases
This Jenkinsfile is the most basic example for setup a new Pipeline, the use cases can be:

 - Test if the Jenkinsfile is being called correctly from the Jenkins pipeline configuration.
 - Test any command on the agent.
 - General study projects


# 

**[SPANISH VERSION]**

Esta plantilla muestra la configuración básica para un Jenkinsfile con solo dos stages de ejemplo


## Conceptos clave

 - **Agent:** Recurso de computo donde los stage serán ejecutados, ejemplo:
	 - La misma maquina donde Jenkins esta instalado.
	 - Una maquina local o una maquina virtual en la nube.
	 - Un contenedor de Docker.
	 
 - **Stage:** Pasos relacionados al negocio que muestran una secuencia ordenada, ejemplo:
	 - Compilar
	 - Probar
	 - Desplegar
	 
 - **Step:** Conjunto de comandos necesarios para lograr los pasos relacionados al negocio, ejemplo:
	 - Paso para lograr la compilación:
		 - Obtener la fecha y hora
		 - Obtener las variables de entorno
		 - Injectar las variables de enterno dentro del código fuente
		 - Ejecutar el comando de compilación


## Casos de uso
Este Jenkinsfile es el más básico ejemplo para configurar un nuevo piepline, los casos de uso pueden ser:

 - Probar si el Jenkinsfile esta siendo llamado correctamente desde la configuración del pipeline.
 - Probar cualquier comando sobre el agente.
 - Para proyectos generales de estudio