## Getting Starterd
This is the backend source code from the Python Part 2 Event: Web development with Python & Deployment with Azure. For the purposes of the event we created a simple Todo List App.

### Installation
[Python 3.6](https://www.python.org/downloads/release/python-360/) is needed for the project. Also download [Pip](https://pypi.org/project/pip/) and run
 ```
 pip install pipenv
 ``` 
 to get [Pipenv](https://github.com/pypa/pipenv). In order to download the python dependencies simply run
 ```
 pipenv install
 ```
### Running the project
The project needs a config.yaml file in order to run. Go to `backend/config` and run:
```
cp config.template.yaml config.yaml
```
in order to copy paste the config template. By default the project runs on port `8080`. Check if other app is running on that port.

After this step, in the backend folder run: 
```
pipenv shell
```
to launch the pipenv shell. Then you can run `python app.py` and the server will start.

### Contact
For further questions please contact us on our [Facebook Page](https://www.facebook.com/StudentguruPatras/).