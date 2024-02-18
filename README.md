# docks
Dockerfiles to build images for dockerhub/nesscool

basecpp is an image that provides the essential components for building a cpp project
gcc, nvim

The git/nvim/vim settings of current user will be added to the running container.

To incorporate into one's project, you can follow the script in github.com/nesscool/basecpp,
which is a vanilla cpp project that has a script called 'code'.

When running 'code' from a shell, the basecpp docker container will be spun up and
the current working directory will become the project and working directory of the container.

alpine is a sandbox env where you can build the latest alpine image and step into a running container with './code'.
