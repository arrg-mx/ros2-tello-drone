# ARRG: Curso ROS2 Humble, 2024-I - Tello Drone

## Contenido

- [Desarrollo](#desarrollo)
- [Equipo](#equipo)
- [Referencias](#referencias)

## Desarrollo

**Nota:** En este proyecto **sólo se bastará con la simulación del drone**; sin embargo, se les invita a desarrollar el proyecto con el drone real.

- [ ] Documentación y justificación de la configuración del robot.
- [ ] Planteamiento de la simulación
	- [ ] Evaluación del material disponible,
 	- [ ] Implementación del modelo del robot seleccionado.
  	- [ ] Esquema de paquetes/metapaquete a implementar
  	- [ ] Diagrama de nodos y tópicos
  	- [ ] Servicios a implementar
  	- [ ] Controles a implentales
  	- [ ] Acciones a implentar
  	- [ ] Desarrollo de nodos, tópicos, servicios, controles y acciones en Python/C++
- [ ] Simulación
	- [ ] Construcción de la simulación en Gazebo, escena y modelos 3D a implemenatr.
	- [ ] Implemenatción del modelo tridimencional del robot en la simulación
 	- [ ] Interación de rutinas y acciones en el entorno simulado
- [ ] Reporte de resultados finales.

## Equipo

**Integrantes del proyecto:**

| Nombre | Observaciones |
| :----------| :----------- |
| Cruz Baños Omar Emiliano | **responsable** | 

## Referencias

### ¿Dónde empezar?

**Academics**

1. **Ryze Tello drone tracking** [Bachelor Project](https://dspace.cvut.cz/bitstream/handle/10467/101276/F3-BP-2022-Masharipov-Bekhzod-RyzeTelloDroneTracking.pdf)
	- *Tracking real Tello drone using an ArUco Marker* [YT video](https://www.youtube.com/watch?v=V-9W5hL1Efo)
 	- *Tracking a Tello drone using an ArUco marker* [YT video](https://www.youtube.com/watch?v=n8WVKc7n2FE)
1. **A simple vision-based navigation and control strategy for autonomous drone racing** [arxiv.org article](https://arxiv.org/abs/2104.09815)
	> A. Cyba, H. Szolc, and T. Kryjak, A simple vision-based navigation and control strategy for autonomous drone racing. 2021.
 	>
 	> doi: 10.48550/arXiv.2104.09815
 1. **Autonomous navigation of a drone in indoor environments** [master thesis](https://matheo.uliege.be/bitstream/2268.2/11543/1/master_thesis_meurisse_report.pdf)
 	- *Autonomous navigation of a drone in indoor environments* [Github repository](https://github.com/meurissemax/autonomous-drone)
  	- **Autonomous drone** [YT playlist](https://www.youtube.com/playlist?list=PLJEcTQrQgiVdacuc2HymqLV9RqjaRMNYt)

**Legacy/Open Source Code**

1. **dji_sdk** [ROS.org package](http://wiki.ros.org/dji_sdk)
1. **DJI Onboard SDK ROS 4.1.0** [Github repository](https://github.com/dji-sdk/Onboard-SDK-ROS)
1. **tello_ros** [Girhub repository](https://github.com/clydemcqueen/tello_ros) is a ROS2 driver for Tello and Tello EDU drones.
1. **Tello Dji** [Gitbook page](https://alfredo-reyes-montero.gitbook.io/tello-dji/frameworks/ros). ROS driver wrapper for DJI/Ryze Tello drone
1. **Running a Tello simulation in Gazebo** [Github repository](https://github.com/TIERS/tello-ros2-gazebo)
1. **TelloPy** [Github repository](https://github.com/hanyazou/TelloPy). DJI Tello drone controller python package
   
**Media**

From ***tello drone ros*** [YT search results](https://www.youtube.com/results?search_query=tello+drone+ros)

1. **Drone Programming With Python - Setup Tello Python Package** [YT video](https://www.youtube.com/watch?v=-Mb_FKhRn00)
2. *Streaming Video from Tello and Tello EDU Drones with Python* [YT video](https://www.youtube.com/watch?v=kcXN7CYgQ0g)
1. **Gazebo implementation of a Tello drone (with RGB camera) using RotorS and ROS** [YT video](https://www.youtube.com/watch?v=yDGRqMpgBy8)
1. **[Tello] Indoor Autonomous Drone Navigation using monocamera and openVSLAM in a known map (ROS)** [YT video](https://www.youtube.com/watch?v=cx2MV2OOG7U)
	- *2D Autonomous Drone Navigation:* [presentation](https://docs.google.com/presentation/d/1NWfk5wRGWgtlASOhHfgQv3R09tHSWqZZJjLYRBnueoM/edit#slide=id.p)
	- *Localization: openVSLAM (localization mode with pre-built map) + EKF (robot_localization package)* [Github repository](https://github.com/surfii3z/openvslam/tree/aigc_ekf). OpenVSLAM: A Versatile Visual SLAM Framework
	- *robot_localization* [Github repository](https://github.com/surfii3z/robot_localization). is a package of nonlinear state estimation nodes. The package was developed by Charles River Analytics, Inc. [Documentation ](http://docs.ros.org/melodic/api/robot_localization/html/index.html)
	- ***See more references in video's description:***
1. **Autonomous Drone Scanning and Mapping | DJI Tello | ORB_SLAM2** [YT video](https://www.youtube.com/watch?v=lqBRYkWSmjI)
	- *Autonomous Drone Scanning and Mapping* [Github repository](https://github.com/waseemtannous/Autonomous-Drone-Scanning-and-Mapping)
1. **Drone Programming With Python Course | 3 Hours | Including x4 Projects | Computer Vision** [YT video](https://www.youtube.com/watch?v=LmEcyQnfpDA)
1. **Easy Programming of Tello Drone | Python OpenCV Object Tracking** [YT video](https://www.youtube.com/watch?v=vDOkUHNdmKs) 

---

**Nota:** Usar la siguiente [plantilla](https://github.com/arrg-mx/fmtos-docs/blob/main/fmto-reporte-curso.md) para su reporte así como la [plantilla del repositorio](https://github.com/mrg-mex/mrg-plantilla-repositorio) como una guía para organizar sus archivos y referencia del formato Markdown para diferentes elementos que necesiten integrar en su reporte.
