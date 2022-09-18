# News Aggregator

## Setup full application using Docker

1. Ensure `Docker` and `Node` are installed.
   Docker installation: https://docs.docker.com/get-docker/
2. Clone/Pull repo from Github.
3. Install Python Poetry:
    ```
    curl -sSL https://install.python-poetry.org | python3 -
    ```

    For Windows:

    ```
    (Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | py -
    ```


4. Run Docker:
    ```
    cd news-aggregator
    docker-compose up
    ```

5. Check that backend is functional at http://localhost:8000 and check API docs is available at http://localhost:8000/docs.

6. Check frontend works at http://localhost:5173.