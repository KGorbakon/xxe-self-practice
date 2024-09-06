# XXE Lab #

This virtual environment is a simple php web application that contains an example of an XML eXternal Entity vulnerability.

## Docker ##

To run XXELab in a Docker container. Build the image:

	$ git clone https://github.com/KGorbakon/xxelab.git
	$ cd xxelab
	$ docker build -t xxelab .

Run:

	$ docker run -it --rm -p 127.0.0.1:5000:80 xxelab

Open [http://localhost:5000](http://localhost:5000) and have fun.

