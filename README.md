# docker-compose-nginx-postgres-alpine

Nginx is an open source reverse proxy server for HTTP, HTTPS, SMTP, POP3, and IMAP protocols, as well as a load balancer, HTTP cache, and a web server (origin server).

For Redhat(Linux) and Centos(Linux) host system, configuration as follows:

To run this docker-compose.yml file, docker and docker-compose installment is required in the system.

Start the docker service using command, "systemctl start docker".

Check the status of docker service using command, "systemctl status docker".

Check the port availability of your host system using command, "netstat -tnlp" and change the specified listening port accordingly in the file.
Install the images of the container specified in the file or it will download and install at the run-time.

After setting up the environment run file using commad, "docker-compose.yml up". This will also show the runtime logs of the container.

To run the file without showing logs use command, "docker-compose.yml up -d" in detatch mode.
