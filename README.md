![image](https://github.com/swapnalidharme/Docker/assets/73031765/0e35020f-4fd3-441a-baf4-d87eff3e65ba)# Docker
Docker is a platform for developers and sysadmins to develop, deploy, and run applications with containers. This is often described as containerization. 
Putting applications into containers leads to several advantages:
  1. Docker containers are always portable. This means that you can build containers locally and deploy containers to any docker environment (other computers, servers, cloud, etc …)
  2. Containers are lightweight because containers are sharing the host kernel (the host operating system) but can also handle the most complex applications.
  3. Containers are stackable, services can be stacked vertically and on-the-fly.

##Containers vs. Virtual Machines
When talking about containerization it is very often compared to virtual machines. 
Let’s take a look at the following image to see the main difference:

![image](https://github.com/swapnalidharme/Docker/assets/73031765/8e9378fe-b975-42a1-9a47-d84c84171c37)

- The Docker container platform is always running on top of the host operating system. 
- Containers are containing the binaries, libraries, and the application itself. 
- Containers do not contain a guest operating system which ensures that containers are lightweight.

- In contrast virtual machines are running on a hypervisor (responsible for running virtual machines) and include it’s own guest operating system.
- This increased the size of the virtual machines significantly, makes setting up virtual machines more complex and requires more resources to run each virtual machine.

Here are some key concepts and terms related to Docker:
###Images: 
A Docker image is containing everything needed to run an application as a container. This includes code, runtime, libraries, environment variables, configuration files.
The image can then be deployed to any Docker environment and executable as a container.

Containers
A Docker container is a runtime instance of an image. From one image you can create multiple containers (all running the sample application) on multiple Docker platform.

A container runs as a discrete process on the host machine. Because the container runs without the need to boot up a guest operating system it is lightweight and limits the resources (e.g. memory) which are needed to let it run.
