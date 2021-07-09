Dockerfile and docker-compose files to use as development environments.

I have multiple computers and can use these to work on projects instead of setting up a development environment on each one.

Local PC requirements:

Docker or Docker Desktop installed.
Git installed.
Microsoft VS Code installed. Remote-Containers extension installed.

Use 'docker-compose up -d' to start a container. Connect to the container using VS Code.

docker-buster-python-node
- uses debian buster official image
- installs python3 with dev and pip modules
- installs node lts version via nvm
- used for both python and javascript development

docker-node
- uses node official image
- uses lts tag
- used for javascript development

docker-python
- uses python 3 official image
- uses 3 tag to get latest version
- used for python / django development

git is installed in each container as well.