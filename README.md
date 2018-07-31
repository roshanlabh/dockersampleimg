This is just a sample HTML project, which demonstrate Docker functionality.


Just clone this repo.
Then run "docker build -t <new-image-name> ." command.
	
	docker build -t sample-html-app .

It will create image from your Dockerfile. Then to run this image, use "docker run -dit --name <new-container-name> -p <port-number>:80 <above-image-name>"

	docker run -dit --name jumboapp -p 8080:80 my-apache2
