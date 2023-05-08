Download Link: https://assignmentchef.com/product/solved-statsm232a-project-2-backpropagation-code
<br>
In this project you will practice writing backpropagation code, and training fully-connectedNeural Networks. The goals of this projectare as follows:

– understand **Neural Networks** and how they are arranged in layeredarchitectures– understand and be able to implement (vectorized) **backpropagation**– implement various **update rules** used to optimize Neural Networks– effectively **cross-validate** and find the best hyperparameters for NeuralNetwork architecture

## SetupHere’s how you install the necessary dependencies:

**Installing Python 3.5+:**To use python3, make sure to install version 3.5 or 3.6 on your local machine. If you are on Mac OS X, you can do this using [Homebrew](https://brew.sh) with `brew install python3`. You can find instructions for Ubuntu [here](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-ubuntu-16-04).

**Virtual environment:**We recommend using [virtual environment](http://docs.python-guide.org/en/latest/dev/virtualenvs/) for the project. If you choose not to use a virtual environment, it is up to you to make sure that all dependencies for the code are installed globally on your machine. To set up a virtual environment, run the following:

“`bashcd project2sudo pip3 install virtualenv # This may already be installedvirtualenv -p python3 .env # Create a virtual environment (python3)source .env/bin/activate # Activate the virtual environmentpip3 install -r requirements.txt # Install dependencies

# Work on the project for a while …# … and when you’re done:deactivate # Exit the virtual environment“`

Note that every time you want to work on the project, you should run `source .env/bin/activate` (from within your `project2` folder) to re-activate the virtual environment, and `deactivate` again whenever you are done.

### Download data:Once you have the starter code (regardless of which method you choose above), you will need to download the MNIST and CIFAR-10 datasets.Run the following from the `project2` directory:

“`bashcd stats232a/datasets./get_datasets.sh“`

### Start IPython:After you have datasets, you should start the IPython notebook server from the`project2` directory, with the `jupyter notebook` command.

### Submitting your work:Please zip your working folder (project2), but don’t include folder ./stats232a/datasets. Submit this zip file to CCLE.

To do this project, follow the instruction in the IPython notebook `FullyConnectedNets.ipynb`. It will introduce you to themodular layer design, and then use those layers to implement fully-connectednetworks of arbitrary depth. To optimize these models you will implement severalpopular update rules.


