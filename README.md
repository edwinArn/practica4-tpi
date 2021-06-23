# practica4-tpi

<b>Nombres de los integrantes

<br>Vladimir Enrique Martínez Flores 	MF18030
<br>Edwin Arnoldo Argueta Lara 		AL15022
<br>Christian Eduardo Meda Margueiz		MM17017</b>
<br>
<br>Para esto necesita descargar minikube y kubectl
<br>una vez instalados debe iniciar minikube con el comando:
<i><b>minikube start</b></i>
<br>luego debe usar el comando:
<i><b>eval $(minikube docker-env)</b></i>
<br>que permitira que dentro de minikube usted pueda crear la imagen docker en la carpeta src/
<br>luego utilice los respectivos comandos para crear una imagen con:
<i><b>docker build -t tpi-hello src/</b></i>
<br>luego una vez creada la imagen ejecute:
<i><b>kubectl apply -f k8s/</b></i>
