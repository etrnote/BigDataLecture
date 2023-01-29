#### Install Environment

1. clone repo

```bash
git config --global http.sslVerify false
git clone https://github.com/etrnote/BigDataLecture.git
```



2. create a new python virtual environment

```bash
python -m venv .
```



3. Activate virtual env

```bash
venv\Scripts\activate.bat
```



4. Cd into the project directory


5. run the following command to avoid certificate issues:
```bash
pip config set global.trusted-host \
    "pypi.org files.pythonhosted.org pypi.python.org" \
    --trusted-host=pypi.python.org \
    --trusted-host=pypi.org \
    --trusted-host=files.pythonhosted.org
 ```

6. installl the requirement file

```bash
> pip install -r requirements.txt
```
If that doesn't work, try installing these packages separately:
```bash
pip install --trusted-host pypi.org --trusted-host pypi.python.org --trusted-host files.pythonhosted.org pyspark
pip install --trusted-host pypi.org --trusted-host pypi.python.org --trusted-host files.pythonhosted.org jupyter
pip install --trusted-host pypi.org --trusted-host pypi.python.org --trusted-host files.pythonhosted.org pandas
pip install --trusted-host pypi.org --trusted-host pypi.python.org --trusted-host files.pythonhosted.org numpy
```


7. Start a new notebook by running `jupyter-lab` or if that doesn't work: `python -m jupyterlab`

8. If the web interface doesn't open automatically, manually insert this link: `http://localhost:8888/`



