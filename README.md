# RStudio2

Source to build a Docker image of RStudio Server. Include sample R script for testing the weightwatcher2 CEP stateless Decision Server as based on the Drools 6.3.0.FINAL kie-server application.

To build the Docker image:

$ docker build -t spicozzi/rstudio2 .

To pull down the image on docker hub:

$ docker pull spicozzi/rstudio2

To launch an instance of the container:

$ docker run -it -p 8787:8787 spicozzi/rstudio2

To find the IP_ADDRESS of the container if using boot2docker:

$ boot2docker ip

To interact with the RStudio Server, point your Broswer at:

Firefox http://<IP_ADDRESS>:8787

login using credentials guest/guest

