# XXE Lab #

This virtual environment is a simple php web application that contains an example of an XML eXternal Entity vulnerability.

## Docker ##

To run XXELab in a Docker container. Build the image:

	$ git clone https://github.com/KGorbakon/xxe-self-practice.git
	$ cd xxe-self-practice
	$ docker build -t xxe-self-practice .

Run:

	$ docker run -it --rm -p 127.0.0.1:5000:80 xxe-self-practice

Open [http://localhost:5000](http://localhost:5000) and have fun.

