motrap
======

Model Transformation Pipeline Tool

To initialise, enter the details of your model repository into the file:

		model-repository.properties

which should have the structure:

		git{
		  name="Example Models"
		  url="https://github.com/jamesrwelch/motrap-demo-models.git"
		  username=""
		  password=""
		}

The example file committed to the repository downloads a simple Hello, World example.

To checkout the repository, run from the command-line:

		gradle -q cloneGitRepo