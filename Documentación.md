# TelloDrone_ROS2
# Controla un Tello Drone con ROS2


## #1 Instalación de Linux Ubuntu 20.04.6 LTS (Focal Fossa)
### Página donde puedes descargar la imagen ISO https://releases.ubuntu.com/focal/

## #2 Instalación de ROS 2 Foxy Fitzroy 
### En la siguiente página puedes encontrar los pasos para la instalación de Foxy https://docs.ros.org/en/foxy/Installation/Ubuntu-Install-Debians.html
### Asegurate de instalar la versión Desktop y las Development tools

## #3 Sigue las instrucciones del siguiente repositorio 
### Repositorio: https://github.com/clydemcqueen/tello_ros/tree/master

## #4 Antes de volar el Drone
### Una vez llegada a esta parte asegurate de configurar tu máquina virtual para que se conecte mediante WiFi y NO via Ethernet para que no obtengas errores de conexión y puedas conectarte al WiFi del Drone
![image](https://github.com/Emiomar/TelloDrone_ROS2/assets/62313075/ff16cfcc-768b-4020-b00c-c5485eec632b)


## #5 Volando el Drone
### Durante el vuelo del drone podras visualizar la cámara del drone en tu computadora y controlarlo con ayuda del Joystick

https://github.com/Emiomar/TelloDrone_ROS2/assets/62313075/dbd4dd0f-9490-4025-b7ca-76c57321dd07

# Simula un Tello Drone con ROS 2
## #1 Sigue las instrucciones del siguiente repositorio
### Repositorio: https://github.com/clydemcqueen/tello_ros/tree/master/tello_gazebo
### Asegurate de instalar transformations.py Puedes instalarlo con los siguientes comandos
```
sudo apt update
sudo apt install python3-pip
pip3 install transformations
```
## #2 Una vez iniciado la simulación podras controlar el drone con ayuda del Joystick

https://github.com/Emiomar/TelloDrone_ROS2/assets/62313075/899d0820-ddc7-4df5-a149-886c21660fa9

## #3 Visualización de topicos
### Abre otra terminal mientras corre la simulación y ejecuta el siguiente comando para visualizar los topicos 
```
ros2 topic list
```
![image](https://github.com/Emiomar/TelloDrone_ROS2/assets/62313075/aeafc0d2-bc0d-475d-83f9-d0f3d0cb9dd4)

### Ejecuta Rvizz2
```
rviz2
```
### Dentro de rviz2 podras seleccionar los topicos que quieras visualizar, a continuación un ejemplo
### -ODOMETRÍA
### -CAMERA

https://github.com/Emiomar/TelloDrone_ROS2/assets/62313075/58eb63f8-62a9-461a-b6cd-f07bdd1cd590
