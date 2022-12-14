# Set up Django + Tailwind

1. Create a virtualenv and activate it:
    ```shell
    python3 -m venv .venv
    source .venv/bin/activate
    ```
2. Install dependencies:
    ```shell
    pip install poetry
    poetry install
    ```
3. Install Tailwind Node dependencies:
    ```shell
    ./manage.py tailwind install
    ```
4. Start Django:
    ```shell
    ./manage.py migrate
    ./manage.py runserver
    ```
5. In another console, start Tailwind:
    ```shell
    source .venv/bin/activate
    ./manage.py tailwind start
    ```
