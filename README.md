# LevelUp Docker homework

This repository contains the homework related to the Docker classes we did this week.

Your task is simple: ensure that the application can be started by simply running `docker compose up`.

The application is a simple `node` server checking if it can connect to the database on a specific port
and writing that status as the response.

To achieve this there are four main things you will need to do:

1. write a `Dockerfile` for the main application
2. find an appropriate image on DockerHub to run MariaDB
3. connect the app with the database on the right port
4. ensure that you can access the application from the host machine.

If you did everything correctly, after navigating to `http://localhost:3000` in your browser you should see the message:

* `Well done you have dockerized your first application!`

Other than the main 4 items mentioned above, you are free to implement the best practices
we've mentioned in the class to make working on this app a truly wonderful developer experience :)
