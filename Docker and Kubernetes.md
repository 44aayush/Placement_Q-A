<h2 style="color:yellow">WHY DEVOPS?</h2>
<br>

----------------------------------------------------------------------------------------------------------------------------------------

<h1 align="center">DOCKER</h1>
<br>

1. <h3 style="color:yellow">DOCKER</h3>
    Docker is a containerization platform i.e., used for building, deploying and running applications<br>
    Can be run on any infrastructure<br>
    Conatiner/Docker Hub for sharing containers of the application<br>
<br>

2. <h3 style="color:yellow">CONTAINER</h3>
    A Container is a standard unit of software that holds the code and all it's dependencies, in order to make the application run smoothly, quickly and reliably between different computing platforms <br>
    Main aim is to get rid of infrastructure dependency while deployment and running of application<br>
    Technically, it is runnable instance of docker image<br>
<br>    

3. <h3 style="color:yellow">DOCKER IMAGES</h3>
    * Executable packages (code and dependencies, software packages etc...)
    * Can be deployed to any docker environment and the container can be spun to run the application
<br>

4. <h3 style="color:yellow">DOCKERFILE</h3>
    * Text file that has all the commands which need to be run for building a given image
<br>

5. <h3 style="color:yellow">HYPERVISOR</h3>
    * Virtual Machine Monitor
    * Software that makes the virtualization happen by allocating resources of host system to each of environment installed
    * * Native - Bare-Metal Hypervisor, runs directly on host system
    * * Hosted - Use the lying host system for resources
<br>

6. <h3 style="color:yellow">DOCKER COMPOSE</h3>
    * YAML (JSON) file consisting of all the details regarding various service, networks and volumes to set up Docker-based application
    * Used for creating multiple containers, host them and establish communication between them
<br>

7. <h3 style="color:yellow">NAMESPACE</h3>
    * Namespace is linux feature that ensures OS resource partition in a mutual exclusive manner
    * In Docker, it ensure containers are portable and don't affect underlying host
    * PID, Mount, User, Network, IPC
<br>

8. <h3 style="color:yellow">COMPONENTS</h3>
    * **Host** - Holds the Docker Daemon(link with registry), Images(metadata), and Containers(application)
    * **Clinet** - Runs operations to set up communication with the Docker Host
    * **Registry** - Used to store Docker images
<br>

9. <h3 style="color:yellow">DOCKER SWARM</h3>
    * Native tool used for clustering and scheduling of Docker containers
<br>

10. <h3 style="color:yellow">COMMANDS</h3>
    * **build** : to build an image file for docker
    * **create** : for creation of new container
    * **kill** : to kill a conatiner
    * **dockerd** : for launching docker daemon
    * **commit** : for creating new image from the container changes
    * **push** : pushes repository or image to a registry
    * **run** : runs a command in a new container
    * **pull** : pulls repository or image from a registry
    * **start** : starts one or more containers
    * **stop** : stops running containers
    * **search** : searches for an image in a docker hub
<br>

11. <h3 style="color:yellow">WORKFLOW</h3>
    * Since the Dockerfile is the source code of the image, everything starts with it
    * Once it is created, the Dockerfile is used to build compiled version of the image of the container
    * This image is then redistributed using the registry, which is like a repository of images.
    * Further, the image can be used to run containers. A container, while it is running, is very similar to a VM without the hypervisor.
<br>

12. <h3 style="color:yellow">VIEW LOGS OF DOCKER</h3>
    * **journalctl -u docker;**
<br>

13. <h3 style="color:yellow">WHY STATELESS APPLICATION?</h3>
    * We can create one container from our application and take out the app's configurable state parameters
    * Once it is one, we can run the same container with different production parameters and other environments
    * We can reuse the same image in distinct scenarios and also easy to Scale 
<br>

----------------------------------------------------------------------------------------------------------------------------------------

<h1 align="center">KUBERNETES</h1>
<br>

1. <h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>

<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

<br>
<h3 style="color:yellow"></h3>

