# practica4-tpi

Nombres de los integrantes

Vladimir Enrique Martínez Flores 	MF18030
Edwin Arnoldo Argueta Lara 		AL15022
Christian Eduardo Meda Margueiz		MM17017

Para esto necesita descargar minikube y kubectl
una vez instalados debe iniciar minikube con el comando:
minikube start
luego debe usar el comando:
eval $(minikube docker-env)
que permitira que dentro de minikube usted pueda crear la imagen docker en la carpeta src/
luego utilice los respectivos comandos para crear una imagen con: docker build -t tpi-hello src/.
luego una vez creada la imagen ejecute:
kubectl apply -f k8s/
