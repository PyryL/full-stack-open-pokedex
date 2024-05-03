# Exercise 11.1

In a Python environment, there are many good options for tools use.
I would prefer Poetry as the backbone of the project since it is simple and easy to use.
In addition to being the go-to option for dependency management,
Poetry can also be used to build the project and, if needed, publish it to a package index.
Linting would obviously be done with Pylint and a proper configuration.
Tests would be run with Pytest.
In addition, if higher-level tests are needed, Robot Framework can also be used.

Besides Github Actions and Jenkins, CircleCI seems to be a solid alternative. It offers both cloud and self-hosted solutions, and has an appealing free price tier. Another competitive service seems to be Azure Pipelines, which can be used, for example, to build and deploy to any cloud environment.

When developing a Python project, I would use some cloud-based CI environment. In my experience, build times in Python are usually shorter than in other languages, so there would be no worries about time-based billing in the cloud. Cloud CI is also much easier to maintain compared to a self-hosted one. I think that the project should be very large or have some other special characteristics before a self-hosted CI environment would be worthwhile.
