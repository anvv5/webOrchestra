

# dockerContainer
<img src="./img/logo.png" width="100%" />
I discovered Docker and set up my first web server.

## Functional


- The container OS is debian buster.
- Web server is set up with Nginx.
- On web server is running:
  - [x] Website based on WordPress
  - [x] phpMyAdmin
  - [x] MySQL linked with other services
- Server uses the SSL protocol.
- Server redirects to the correct website.
- Server is running with disbled autoindex.

<img src="./img/schema.png" width="100%" />

## Quick start

```bash
git clone https://github.com/anvv5/dockerContainer.git ; cd dockerContainer ; docker build -t server . ; docker run -it -p 80:80 -p 443:443 server ;

```

