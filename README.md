hello-world_Docker is Dockerfile to build hello-world container based on Ubuntu 16.04.

By default runnig this container will printout "Hello World!!!" Output. 

You can also supply any bash command for fun as shown below.

    docker run neoxsys/hello-world -c 'cat /etc/resolv.conf'
