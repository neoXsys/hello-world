hello-world is DOckercontainer based on Ubuntu 16.04. By default it will execute hello-world.sh bash shell script.

By default runnig this container will printout "Hello World!!!" Output. 

You can also supply any bash command for fun as shown below.

    docker run neoxsys/hello-world -c 'cat /etc/resolv.conf'
