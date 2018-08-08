# codeigniter-rest-api
PHP codeigniter rest api 

# Setup
1. Step One
  * Copy "REST_Controller.php" and "Format.php" to "\application\libraries" Folder
  * Replace your "language" Folder
  * Copy "API" Folder into "controllers"
  
2. Step Two
  * Open Postmen 
  * Try Get Request "index.php/api/example/users" 
  ```JSON
  "[
    {
        "id": 1,
        "name": "John",
        "email": "john@example.com",
        "fact": "Loves coding"
    },
    {
        "id": 2,
        "name": "Jim",
        "email": "jim@example.com",
        "fact": "Developed on CodeIgniter"
    },
    {
        "id": 3,
        "name": "Jane",
        "email": "jane@example.com",
        "fact": "Lives in the USA",
        "hobbies": [
            "guitar",
            "cycling"
        ]
    }
]
```
  ### Enjoy !!!
