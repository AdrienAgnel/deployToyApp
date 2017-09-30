Adding a module to the frontend
===============================

Enter the following command

    docker exec -i <FRONTEND_CONTAINER_NAME> yarn add <YOUR_LIB>

Example:

    docker exec -i djangoreactreduxbase_frontend_1 yarn add lodash

Check that it's all right :
- In package.json file there should be a new line with the name and the version of the module
- import the new module in your component and start working
