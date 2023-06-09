# fastapi-template

A FastAPI template with local development environment

### Uses the following libraries:
[FastAPI](https://fastapi.tiangolo.com/)<br>
[Mangum](https://pypi.org/project/mangum/)<br>
[Lambda](https://aws.amazon.com/lambda/)
<br>

## Setup dev environment:
<br>

### Setup virtualenv environment:
```
virtualenv -p python3.10 env
```

### Activate environment
```
source env/bin/activate
```

### Inatall the following libraries:
```
pip install "fastapi[all]" uvicorn pip install mangum
```

### If you would like to shut down the environment:
```
deactivate
```

---
<br>

## Run local dev environment
<br>

### If the enviromment is not running, activate environment:
```
source env/bin/activate
```

### Run application

```
uvicorn app.main:app --host 0.0.0.0 --port 8080 --reload
```

### App access:

[http://0.0.0.0:8080/](http://0.0.0.0:8080/)
<br><br>
### Swager accees:

[http://0.0.0.0:8080//\docs](http://0.0.0.0:8080/docs)
<br><br>
### Stop local server
```
ctrl + c
```

### Shut down environment:
```
deactivate
```

---
