# Team-oriented_Project_2023-24
(This is an example Markdown Taken From one of my private repos)
##  For WINDOWS users: Please be aware to installing python interpreter 3.9 and above

#### Create a virtual environment using Python's built-in venv module by executing the following in your project terminal:<br/><br/>


Navigate to the project's root directory using the cd command: <br>
`cd TPRO` 



Create a virtual environment using Python's built-in venv module:<br>
`python -m venv venv` <br><br>


Activate the virtual environment:<br>
On Windows:     `venv\Scripts\activate`<br>
then update pip  `python.exe -m pip install --upgrade pip` 
<br><br>
On macOS and Linux: `source venv/bin/activate` <br>
then update pip ``` python -m pip install --upgrade pip ```

<br><br>


### Installing necessary libraries
Once the virtual environment is activated, you can install the required packages from the **requirements.txt** file:

`pip install -r requirements.txt`


### Installing PyTorch library <br/>
<a href='https://pytorch.org/get-started/locally/' > click to configure your system suitable PyTorch version  </a><br/>
then run the provided command in terminal "last row in table" 

### Installing GraphViz app <br/>
<a href='https://graphviz.org/download/' > download GraphViz app </a><br/>
make sure to set system environment variables path to:<br/>

`C:\Program Files\Graphviz\bin`

### Setup Config
Run The src/config_loader/yml_loader.py This will initalize the Config To Contain The System Specific Variables
See Wiki to read how to utilize the config.

### Start Docker Container
docker-compose up  
to Start specific Docker
docker-compose up  <services-name>
(add --build to rebuild)

=> Changing port etz in case of Port collision should not lead to any issues as the python retrieves the port from the config.

°°° Recommended to use Docker-Desktop :)

#### Modifie Docker-container
=> see docker-compose.yml and Dockerfile

### [Known issues And how to fix them.](data/readme/fixes.md)

### Code documentation To generate the Code Documentation
Install doxygen and run 
doxygen code-doc this should provide a webui for code documentation :)


