# Docker-en-Alpine
Instalación de docker en Alpine

Lo primero que debemos hacer es instalar la versión de alpine que más de adecue a nuestro caso
(En mi caso he descargado la Standard X86)
![1](https://user-images.githubusercontent.com/91874499/172212866-33d8920e-1ae7-4391-87e1-9c6e450599e5.PNG)

Seguidamente abriremos VirtualBox y creamos una nueva máquina virtual con el nombre de Alpine y le indicamos la ruta donde se guardará esta.
![2](https://user-images.githubusercontent.com/91874499/172213092-69ed7171-5c7a-4536-8c8a-59776374f10f.PNG)
También configuraremos a nuestro gusta el consumo que queremos que tenga de Memoria, Ram etc
![3](https://user-images.githubusercontent.com/91874499/172213222-9cc29f9a-932f-4e18-85df-2658a91dc46c.PNG)

Ahora añadiremos la versión que hemos instalado de alpine en nuestra máquina virtual de la seguiente manera:
Cofiguración,Almacenamiento,en el disco presionamos doble click y seleccionamos el disco que nos habíamos descargado
![4](https://user-images.githubusercontent.com/91874499/172213508-da0c906d-39a7-4e99-bcca-d1c11590fd25.PNG)

Ahora arrancaremos la máquina virtual e iremos siguiendo las diferentes indicaciones del video para ir configurando la maquina virtual.
![5](https://user-images.githubusercontent.com/91874499/172213756-c7dc356d-209f-410a-a034-d68fb10a8914.PNG)
![6](https://user-images.githubusercontent.com/91874499/172213760-8efeb7b8-0099-43a4-b383-c0058c0f79b9.PNG)
![7](https://user-images.githubusercontent.com/91874499/172213762-e030bb2f-0378-4d62-ad6a-901bab00c38e.PNG)
![8](https://user-images.githubusercontent.com/91874499/172213766-cafaa3d5-cc43-4b5f-ab9d-6f38bbbe9785.PNG)
![9](https://user-images.githubusercontent.com/91874499/172213767-cc10f655-514e-4f8a-93c1-fa986a2852d5.PNG)


Al finalizar las diferentes configuraciones que nos indica el video saldremos de la maquina virtual y accederemos a las configuraciones de la maquina virtual,en el apartado de Red y habilitaremos el 'Adaptador puente'.
![10](https://user-images.githubusercontent.com/91874499/172214204-b61cdfde-e858-4e94-b1e4-ab036202e745.PNG)

Despúes accederemos al apartado de Sistema y desactivaremos las opciones de Disquete y Óptica que aparecen en pantalla 
![11](https://user-images.githubusercontent.com/91874499/172214392-73b36c12-e7fb-4cc0-b874-389f3f65a9e6.PNG)

Y para finalizar volvermos a arrancar la maquina virtual para acceder a la dirección IP con la que deberemos conectar con docker.
![12](https://user-images.githubusercontent.com/91874499/172214601-2acef753-afeb-4614-8755-c89e0c5b6c27.PNG)
