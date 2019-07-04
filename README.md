# F1/10 racecar simulator docker image
Based on:  <https://hub.docker.com/r/dorowu/ubuntu-desktop-lxde-vnc/> and <https://github.com/madhurbehl/f1tenth_docker>

## Quick start
```
docker run -it --rm -p 6080:80 billyz/f110
```
Then open your browser and go to http://127.0.0.1:6080/.
After you've connected to the Ubuntu in Docker, click the button at the bottom left of the screen, go to System Tools --> LXTerminal.
In the terminal, run
```
roslaunch racecar_simulator simulate.launch
```
