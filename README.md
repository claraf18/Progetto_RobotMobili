# Progetto_RobotMobili

# Implementazione di ORB-SLAM in RoboMaster S1

Per prima cosa è necessario collegare RoboMaster S1 e il pc alla stessa rete LAN "ROBOMASTER".

Una volta stabilita la connessione è sufficiente lanciare il file publisher.launch che fa partire:
 - master node
 - robomaster_cam_talker.py
 - path_publisher.py
 - orb_slam2_d435_mono.launch
 - rviz

Infine, per muovere RoboMaster all'interno dell'ambiente, in modo che possa ricostruire la mappa e localizzarsi, è necessario pilotarlo tramite l'app dedicata "RoboMaster"
