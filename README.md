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



7. Start a new notebook by running `jupyter-lab`



