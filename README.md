# Fetch Docker

### Prerequisites

* Install Docker - https://docs.docker.com/engine/install/ubuntu/
* Optional: Install Nvidia Docker to access gpu inside docker - https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/install-guide.html#docker 

### Installation
1. Clone this repo
   ```sh
   git clone https://github.com/Nick-AhSen/fetch_docker.git
   cd fetch_docker
   ```
2. Pull image from Dockerhub
   ```sh
   sudo docker pull nahsen/ros-melodic-fetch
   ```
3. Run the docker
    ```sh
    sudo ./start.sh
    ```
