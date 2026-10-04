# robotics-turtlebot3
Syarat: Docker Engine >= 24 dan Docker Compose >= v2.20. ROS tidak perlu dipasang di host.

```bash
git clone https://github.com/Shidqirasyad17/CPS_robotics-turtlebot3.git
cd robotics-turtlebot3/docker
docker compose build
docker compose up
```

Hasil: node talker dan listener berjalan otomatis dan saling bertukar pesan.
