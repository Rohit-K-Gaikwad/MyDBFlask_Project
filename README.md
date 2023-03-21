```
Project:
create a new flask application to perform CRUD operations.

Define a database table

POST endpoint to make an entry into DB table
perform request validation using pydantic
perform response validation using pydantic

GET endpoint to fetch resources from the table
perform response validation using pydantic

PUT endpoint to fully update record
perform request validation using pydantic
perform response validation using pydantic

PATCH endpoint to partially update record
perform request validation using pydantic
perform response validation using pydantic

DELETE endpoint to delete record (use query param/ path param)
```


### MINIFLASK PROJECT

#### This is a Mini-project that performs CRUD operations of DB.
    C: Create
    R: Retrive/Read
    U: Update
    D: Delete

In MINIFLASK Project [Maharashtra] there are following resources:
  1) General
        (Area,Governor,Capital,Chief minister,Official sport, Official Fruit, 
        Official Animal, Population, Official Language, Official Song,   
     )     
  2) COM (Councils of Ministers)
  3) MP (Member of Parliament)
  4) MLA (Member of Legislative)
  5) Districts
  6) Rivers
  7) Tourist Places

#### Tasks to do in this project: 
````
# TASK - 1 
    
````

````
# TASK - 2

-
````

````
# TASK - 3
 
````

````
# Task - 4

````
    
## Project Structure

```
├── Starwars-API (project root)
│ ├── utils (Custom package)
│ │ ├── __init__.py
│ │ ├── fetch_data.py
│ │ ├── randgen.py
│ │ ├── timing.py
| |
│ ├── models(data validation package)
| | ├── __init__.py
| | ├── basemodel.py
| | ├── datamodels
| | | ├── __init__.py
| | | ├──  Py_Characters.py
| | | ├──  Py_Films.py
| | | ├──  Py_Planets.py
| | | ├──  Py_Species.py
| | | ├──  Py_Starships.py
| | | ├──  Py_Vehicles.pyy
| |
│ ├──resources (resources package)
| | ├── __init__.py
| | ├── base.py
| | ├── R_Characters.py
| | ├── R_Films.py
| | ├── R_Planets.py
| | ├── R_Species.py
| | ├── R_Starships.py
| | ├── R_Vehicles.py