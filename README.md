A [Docker](https://www.docker.com) image for the [Amazon ECS CLI]
(https://github.com/aws/amazon-ecs-cli) tool.

To use the container with a project, do the following:

* Copy the bin directory into your project.

* Ensure that your profile PATH includes `./bin` and that it takes priority over
any other directory that may include a php executable:

`PATH=./bin:$PATH`

Now whenever you are in your project's directory, you can simply execute
`ecs-cli` as you would with a typical installation, and the command will
execute in the container instead:

`ecs-cli help configure`

Docker Hub : https://hub.docker.com/r/chekote/ecs-cli/
