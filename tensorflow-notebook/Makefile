.PHONY: build

build:
	docker build -t microinfrastructure/tensorflow-notebook .

push: build
	docker push microinfrastructure/tensorflow-notebook

run: build
	docker run -it microinfrastructure/tensorflow-notebook sh

