# Full Stack Open 2021
## Part 11
### Exercise 1


In this hypothetical scenario, we will consider a Tensorflow microservice being built in Flask. The primary goal is to offer machine learning inference over an API. Presumably, this microservice will be connected to a gateway. Furthermore, the team's coding environment will be based in Visual Studio Code.
	
Given the abundant Python ecosystem, there are a number of tools to choose from in the development process. Linting may be done with the PyLint extension (the default choice in VS Code) following either the conventional, automatic style or pycodestyle (formerly pep8), according to team preference. Testing may be done with the PyTest library. This choice of testing library is particularly useful as it covers both the general Python code as well as Flask-specific code. In a Flask environment, building is mostly a matter of installing the appropriate libraries and their dependencies using the pip package manager. Good control of dependency versions will be key due the machine learning libraries required for the project.
	
In the event of Jenkins and GitHub Actions not being chosen as CI tools, there a number of alternatives. A few popular ones are TravisCI, CircleCI, IBM's UrbanCode, Buildkite, and TeamCity. Given our machine learning objectives, a self-hosted environment is most appropriate as there will be a need for specific hardware (i.e. GPUs or TPUs) in the integration process. 
