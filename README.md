# Hello World

## Running

You can simply `go run .`
Or after building you can run with `docker run -it -p 8080:8080 hello_world`
Or even using [tilt](http://tilt.dev/) with `tilt up`

## Acessing

You can access the application in the por 8080 eg: `curl 127.0.0.1:8080`

## Kubernetes Manifests

You can `kubectl apply -f kustomize/base` or `kustomize build kustomize/ | kubectl apply -f -`

## Dockerfile

You can build locally with `docker build -t yurifl/hello_world .` de build and deploy are automated on docker hub

## Terraform

Inside the terraform folder can `terraform plan` after you configured your credentials and runned `terraform init`
