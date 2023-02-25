# BGApp

A simple web application that lists the top 10 cities in Bulgaria by population.

Used mostly for demonstration in various courses and presentations.

Contains the following set of files:

├── db                        ---> database image files
|   └── db_setup.sql          ---> database seed file
├── web                       ---> web image files
|   ├── bulgaria-map.png      ---> map of Bulgaria
|   ├── config.php            ---> main app config file
|   └── index.php             ---> main app file
├── bgapp.png                 ---> preview of the application
├── Dockerfile.db             ---> used to build the database image
├── Dockerfile.web            ---> used to build the web image. Application files should be mounted on start
├── Dockerfile.web.embedded   ---> used to build the web image with embedded application files
├── README.md                 ---> this file
