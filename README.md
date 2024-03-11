
Build locally
-------------

Instead of pulling the image from a remote repository, you can build it locally:

1. Clone the repository:

       git clone https://github.com/khushijain21/docker-rsyslog.git

2. Build Victoria Metrics image and change tag name

3. Change into the newly created directory and use `docker-compose` to build and
   launch the container:

       cd docker-rsyslog && docker-compose up --build -d

4. Exec into docker

       docker exec -it rsyslos-server bash

5. Check logs under `cat /var/log/kern.log`

[1]: https://github.com/aguslr/docker-rsyslog
[2]: https://www.rsyslog.com/
