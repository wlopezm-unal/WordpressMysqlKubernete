# WordpressMysqlKubernete
Implementación de MySQL y WordPress en Kubernetes: Descubre cómo desplegar y gestionar eficientemente tu base de datos y tu sitio web en esta plataforma de orquestación de contenedores
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Para poder ejecutar el archivo:
1. Descarga los archivos de Github
2. Inicia minikube usando el comando --> minikube start
3. Crea los pods, volumen y los deployment usando el comando --> kubectl apply -f .
4. Verifica si se crearon los pods --> kubectl get pods
5. Verifica si se crearon los deployment --> kubeckt get deployment
6. Ejecutar los servicios creados --> minikube service --all
7. Nombre usuario: wordpress_user
   Password: asdf1234
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
![image](https://github.com/wlopezm-unal/WordpressMysqlKubernete/assets/68913739/167b40a3-353b-4b51-b301-892bc6acb851)
