.PHONY: build

build:
	docker build -t microinfrastructure/scipy-notebook .

push: build
	docker push microinfrastructure/scipy-notebook

run: build
	docker run -it microinfrastructure/scipy-notebook sh

