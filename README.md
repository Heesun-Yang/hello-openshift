# hello-openshift

$ go build -tags netgo   # avoid dynamic linking (we want a static binary)

$ mv hello-openshift bin

$ docker build -t my-hello-openshift .
