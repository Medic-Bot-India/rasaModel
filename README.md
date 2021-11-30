
# RASA Healthcare Assistant Model 
## Introduction
>" Dataset for training an NLU model to provide healthcare assistance. "


The dataset is in the format specified by the requirements of RASA framework as the model is tested and deployed using the same.

## RASA Setup
* Download and extract the zip [file](https://github.com/Medic-Bot-India/rasaModel/archive/refs/heads/main.zip) 
* Create an env for installing rasa
    * We use conda to create the virtual environment, open your preferred command line/terminal/shell in the extracted directory and all the commands are to be performed here
    * Execute <code> conda create --prefix ./env_name python=3.6</code> to create an env in the same directory
* If conda is not installed 
    * Install it from [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) 
    * or use python venv (or) any other env manager, [guide](https://rasa.com/docs/rasa/installation/)
* Activate the env using <code> conda activate ./env_name </code> 
* Install the dependencies
    *  <code> pip install rasa  </code> 
>" Note: The env creation is optional and can also be performed directly in the base env but it is recommended to create a new env as the dependencies are large and might effect the storage/performance if directly installed"


## Usage
* Open the directory and activate the env from comman line.
* Train the model using <code> rasa train </code> this creates a model in the models directory.
* Run the model : <code> rasa shell </code>.
* The trained AI chatbot model will be now active

You can checkout the complete deployed platform [here](https://github.com/Medic-Bot-India/consolidated)

## Testing




<!--![image](/imgs/imagechat.png)
### Purpose-->

<!-- Testing and result images//ss to be added -->

### Contact
[justprateek](https://github.com/justprateek) <br>
[k-v-n-p](https://github.com/k-v-n-p)
