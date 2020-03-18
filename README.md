# radocker

Blueplanet applications are built using docker containers.

The main [Dockerfile](./Dockerfile) in this directory builds a base image which is shared by the RA docker [image](./docker/ra/Dockerfile) and the simulator docker [image](./docker/sim/Dockerfile).

## Additional Information

Information about the structure of the project can be found in each directory's README.

- [radocker](.)
	- [docker](./docker)
		- [/ra](./docker/ra)
		- [/sim](./docker/sim)
	- [scripts](./scripts)
	- [radocker](./radocker)
		- [/config/dev](./radocker/config/dev)
		- [/model](./radocker/model)
			- [/commands](./radocker/model/commands)
				- [tests](./radocker/model/commands/tests)
				- [traps](./radocker/model/commands/traps)
				- [/demo-a/demo-a-1](./radocker/model/commands/demo-a/demo-a-1)
			- [/data](./radocker/model/data)
			- [/graphics](./radocker/model/graphics)
				- [/images](./radocker/model/graphics/images)
					- [/demo-a](./radocker/model/graphics/images/demo-a)
			- [/idmappers](./radocker/model/idmappers)
			- [/schema](./radocker/model/schema)
				- [/models](./radocker/model/schema/models)
			- [/templates](./radocker/model/templates)
				- [/traps](./radocker/model/templates/traps)
			- [/resources](./radocker/model/resources)
				- [/resources/ddui-schema](./radocker/model/resources/ddui-schema)
					- [/resources/ddui-schema/views](./radocker/model/resources/ddui-schema/views)
				- [/resources/definitions](./radocker/model/resources/definitions)
				- [/resources/ui-schema](./radocker/model/resources/ui-schema)
					- [/resources/ui-schema/domain-types](./radocker/model/resources/ui-schema/domain-types)
						- [/resources/ui-schema/domain-types/icons](./radocker/model/resources/ui-schema/domain-types/icons)
