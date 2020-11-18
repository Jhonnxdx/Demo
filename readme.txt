--DESPLIEGUE BACK JAVA_SPRINTBOOT---

1: descargar el proyecto desde https://github.com/Jhonnxdx/Demo.git, con un git clone
2: el proyecto se debe ubicar en una ruta local desde una PC que tenga instalado el Java version 8 y el maven.
3: Ubicarse en la raiz de la carpeta en el explorador de windows  y en la barra de navegacion escribir CMD para que lo abra desde la raiz del proyecto.
	ejemplo de raiz: "C:\Users\Usuario\Documents\workspace-sts-3.9.5.RELEASE\demoProyect"

6:Una vez en la consola, ejecutar el comando: mvn install
7:Luego ejecutar el comando: java -jar + la ruta donde se encuentra generado el JAR del proyecto; se debe encontrar en la carpeta /target del proyecto.
	ejemplo: java -jar C:\Users\Usuario\Documents\workspace-sts-3.9.5.RELEASE\demoProyect\target\demoProject-0.0.1-SNAPSHOT.jar

