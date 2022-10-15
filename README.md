<h1 align="center">Homework 27<br>"Getting to know Django"</h1>


## Setup

1. Clone code to your directory (need git installed):
    ```shell
    git clone https://github.com/YuZu-original/homework_27.git <PATH_TO_YOUR_FOLDER>
    ```
    and go to the folder `cd <PATH_TO_YOUR_FOLDER>`

2. Create and activate new virtual environment:
   - Windows
       ```shell
       python -m venv venv
       venv/Scripts/activate # or venv/Scripts/activate.bat
       ```
   - Linux/Mac
       ```shell
       python3 -m venv venv
       source venv/bin/activate
       ```
3. Install requirements `pip install -r requirements.txt`
4. Run server `./manage.py runserver`

<details><summary><h2>API</h2></summary>

| url         | methods | description        |
|-------------|---------|--------------------|
| `ad/`       | `GET`   | get all ads        |
| `ad/`       | `POST`  | add new ad         |
| `cat/`      | `GET`   | get all categories |
| `cat/`      | `POST`  | add new category   |
| `ad/<id>/`  | `GET`   | get ad by id       |
| `cat/<id>/` | `GET`   | get category by id |
</details>

> made by YuZu