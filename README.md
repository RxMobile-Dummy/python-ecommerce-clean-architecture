# python-ecommerce-clean-architecture
- Ecommerce API built with Flask followed by clean architecture

#### Features

- ##### Admin Users Can
  - Manage Category (Add, Update, View and Delete).
  - Manage Products (Add, Update, View and Delete).
  - Manage Users (Add, Update, View and Delete).
  - Manage Orders (View and Process).
   
    
- ##### Users Can
  - Signup
  - Login
  - Update Profile.
  - Add to Cart.
  - While Checkout, User should give the address to deliver.
  - Manage delivery address


#### Steps to run the project
  - Add environment variables and same in pytest.ini

#### Command to create vertual environment : 
```sh
python3 -m venv <Environment_name>
```

#### Command to install packages : 
```sh
pip3 install -r requirements.txt
```

#### Command to start db in docker : 
```sh
docker-compose up
```

#### Command to run App : 
```sh
Flask run
```

#### Command to run test cases : 
```sh
pytest
```
