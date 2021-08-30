# Docker-compose Jenkin
This project use in learning Jenkin , If any mistake, apologize.

Get Started
-----------

#### Requirements

To run this application on your machine, you need at least:
* docker


Application flow pattern:
---------------------
https://github.com/suraboy/test-deploy-jenkins

Run the docker for development:
---------------------
You can start the application and run the containers in the background, use following command inside project root:

```bash
docker-compose up -d
```
```bash
docker-compose down
```

Running Application
------------------------------------
Open the browser
```bash
http://localhost:8080
```
```bash
username : user 
password : bitnami
```

Available environment variables:

##### User and Site configuration

- `JENKINS_USERNAME`: Jenkins admin username. Default: **user**
- `JENKINS_PASSWORD`: Jenkins admin password. Default: **bitnami**
- `JENKINS_EMAIL`: Jenkins admin email. Default: **user@example.com**
- `JENKINS_HOME`: Jenkins home directory. Default: **/bitnami/jenkins/home**
- `JENKINS_HTTP_PORT_NUMBER`: Port used by Jenkins for HTTP. Default: **8080**
- `JENKINS_HTTPS_PORT_NUMBER`: Port used by Jenkins for HTTPS. Default: **8443**
- `JENKINS_EXTERNAL_HTTP_PORT_NUMBER`: Port to used by Jenkins to generate URLs and links when accessing using HTTP. Default: **80**
- `JENKINS_EXTERNAL_HTTPS_PORT_NUMBER`: Port to used by Jenkins to generate URLs and links when accessing using HTTPS. Default: **443**
- `JENKINS_JNLP_PORT_NUMBER`: Port used by Jenkins for JNLP. Default: **50000**
- `JENKINS_ENABLE_HTTPS`: Enable serving Jenkins through HTTPS instead of HTTP. Default: **no**
- `JENKINS_SKIP_BOOTSTRAP`: Skip performing the initial bootstrapping. Default: **no**



