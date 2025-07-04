## Description
This is a `Post Quantum Cryptography` tool,
<br/>
using Python framework.


## Pre-requisite
[Python](#https://www.python.org/downloads)(includes pip) has to be installed on your system in order to run this project.

## Installation

1. To start, clone the qujata repository:
```bash
git clone https://github.com/atisorg/qujata.git
cd qujata/api
```
2. Install python packages:
```bash
pip3 install -r requirements.txt
```

3. Running the application:
```bash
python3 -m src.main
```

4. Application is available now in: `http://localhost:3020`, curl example:
```bash
curl --location 'http://localhost:3020/qujata-api/analyze' \
--header 'Content-Type: application/json' \
--data '{
    "experimentName": "name",
    "description" : "test description",
    "algorithms": ["kyber512"],
    "iterationsCount": [5],
    "messageSizes": [10]
}'
```

5. Running unit test:
```bash
coverage run -m unittest discover -s tests
coverage html
```
You can see your coverage on the `api/htmlcov/index.html` file. <br />
Please make sure you have 100% coverage.


