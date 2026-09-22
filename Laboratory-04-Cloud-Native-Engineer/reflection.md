# How does the boot time and setup process of a Docker container compare to installing an operating system on a Virtual Machine?

-In this laboratory, I learned how Docker containers can make application deployment faster and easier compared to using a virtual machine. A Docker container can start within seconds because it does not need to boot a complete operating system. In contrast, setting up a virtual machine requires installing and starting a separate operating system before the application can be used. This makes containers more convenient when deploying applications quickly.

# Why is port mapping (-p 8080:80) necessary when running a web server inside a container?

-The port mapping -p 8080:80 is necessary because the Nginx web server is running inside the container on port 80, while port 8080 on the host is used to access it from outside the container. The mapping connects the host’s port 8080 to the container’s port 80. This allowed me to use curl http://localhost:8080 and successfully view the Nginx welcome page.

# What happens to the data inside a container when you use the docker rm command?

-When the docker rm command is used, the specified stopped container is removed completely. Any data stored only inside the container that was not saved using a volume or another external storage method can be lost. This shows why persistent data should be stored separately when necessary.

# How do you think containerization changes the way software developers and IT operations teams work together (DevOps)?

-Containerization can change how software developers and IT operations teams work together. Developers can package an application and its dependencies into a container, while operations teams can run the same container in different environments. This can reduce problems caused by differences between development and production environments and support a more consistent DevOps workflow.

# How is your GitHub portfolio evolving?

-My GitHub portfolio is evolving as I add more laboratory activities, documentation, screenshots, and reflections. This laboratory helped me improve my understanding of Docker and gave me practical experience with deploying and managing containers. It also helped me practice organizing my technical work in a GitHub repository.
