# Hybrid CircleCI Pipeline Builds

[![CircleCI](https://circleci.com/gh/mwaz/hybrid-circleci-pipeline-builds.svg?style=svg)](https://circleci.com/gh/mwaz/hybrid-circleci-pipeline-builds-config)

<p align="center"><img src="https://avatars3.githubusercontent.com/u/59034516"></p>

An application to show how we can combine traditional and orb development pipelines in CircleCI.

## 1. Cloning repository   

```bash
## Clone repository
git clone https://github.com/mwaz/hybrid-circleci-pipeline-builds.git

## cd into directory
cd hybrid-circleci-pipeline-builds
```

## 2. Create Virtual Environment

**Windows**
```
py -3 -m venv venv 

```
          
**macOS/Linux**
          
```bash

python3 -m venv venv
```

## 2.1 .Activate the environment
          
**Windows** 

```venv\Scripts\activate```
          
**macOS/Linux**

```. venv/bin/activate```

or

```source venv/bin/activate```

## 3 .Install the Dependencies

Applies for windows/macOS/Linux

```pip install -r requirements.txt```


## 4. Run the application 

`python wsgi.py`

## 5. Running tests

`pytest -v`



N.B: Once the application server starts running on the terminal, you can use a tool like [postman](https://www.postman.com/) to make the HTTP requests to the application endpoints. The `api/routes.py` file gives an overview of what endpoints are available and what we need to pass into the HTTP requests. 



## Details

This repo is built following a tutorial published on CircleCI blog under the CircleCI Guest Writer Program.

-   Blog post: [ Hybrid CircleCI Pipeline Builds ][blog]
-   Author's GitHub profile: [Waweru Mwaura][author]

### About CircleCI Guest Writer Program

[blog]: https://circleci.com/blog/hybrid-circleci-pipeline-builds
[author]: https://github.com/mwaz
