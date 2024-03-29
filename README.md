## Recipes Demo

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]()
  [![GitHub Issues](https://img.shields.io/github/issues/kevinbowen777/recipes.svg)](https://github.com/kevinbowen777/recipes/issues)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

- demonstration of FastAPI functionality

## Features
 - Create, search and update recipes with site links via an API interface
 - Authenticate users and restrict authorization to certain endpoints
 - Create users and superusers
 -


## Installation

 1. `git clone https://github.com/kevinbowen777/recipes`
 2. `cd recipes`
 3. Create virtualenv
 4. `pip install poetry`
 5. `poetry install`
 6. Run the DB migrations via poetry `poetry run ./prestart.sh` (only required once)
 7. Run the FastAPI server via poetry `poetry run ./run.sh`
 8. URLs:
  - http://localhost:8001/
  - http://127.0.0.1:8001/docs - SwaggerUI


---
## Screenshots

### Homepage
![Homepage](images/recipes_homepage.png)

### API page
![API page](images/recipes_api_page.png)

---
[![License](https://img.shields.io/badge/license-MIT-green)](https://github.com/kevinbowen777/recipes/blob/master/LICENSE)
---
### Live Demo on Linode(not available 24/7):
 - [Homepage](http://23.239.3.242/)
 - [API page](http://23.239.3.242/docs)

### Docker Container Image:

 - TBD

---

### Reporting Bugs

   Visit the [Issues page](https://github.com/kevinbowen777/recipes/issues)
      to view currently open bug reports or open a new issue.
