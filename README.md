# Fetch Docker

### Prerequisites

* Install Docker - https://docs.docker.com/engine/install/ubuntu/
* Optional: Install Nvidia Docker to access gpu inside docker - https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/install-guide.html#docker 

### Installation
1. Pull image from Dockerhub
   ```sh
   sudo docker pull nahsen/ros-melodic-fetch
   ```
   
2. Clone this repo
   ```sh
   git clone https://github.com/Nick-AhSen/fetch_docker.git
   cd fetch_docker
   ```
   
### Setting up a catkin workspace
1. create your catkin folder
   ```sh
   mkdir catkin_ws/src
   cd catkin_ws/src
   ```
2. clone fetch_ws repo
   ```sh
   git clone https://github.com/Nick-AhSen/fetch_ws.git
   ```

### Running the docker
  start.sh script contains the command to run the docker. First cd to the fetch_docker directory and run:
   ```sh
      sudo ./start.sh
   ```

