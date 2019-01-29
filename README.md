-- Work in Progress --

# Get started:

* Run the notebook and copy/move the 'forGo' folder into this folder
* Run: docker run -it -v $(pwd):/go zerotosingularity/tensorflow-go:0.1
* Run docker exec -it CONTAINER_ID /bin/bash
* go get github.com/tensorflow/tensorflow/tensorflow/go
* go build
* ./go cat.jpg

Dockerfile based on:
https://github.com/minixxie/docker-tensorflow-golang

Interesting links:

https://raw.githubusercontent.com/tensorflow/tensorflow/master/tensorflow/go/op/wrappers.go
https://www.tensorflow.org/install/lang_c
https://www.tensorflow.org/install/docker
https://github.com/tensorflow/tensorflow/blob/master/tensorflow/go/example_inception_inference_test.go


# TODO

* Clean up docker file
* Make it work on Google Colab 
* Document better
