# Building python Project and Manage Dependencies with Poetry using python
This project is managed using Poetry, a modern dependency management tool for Python. Creating virtual environments, and packaging your projects for easy sharing.
 Follow the steps below to set up and run the project.

## Prerequisites
Ensure you have Poetry installed. You can check by running the following command:

## 1. Check Poetry Version
 `poetry --version`

## 2. Create a New Poetry Project
 `poetry new project_cloud_native'

## 3. Navigate to the Project Directory
 `cd project_cloud_native`

 ## 4. Check the Python Version
 `poetry run python --version`

 ##  Install the requests Package
 `poetry add requests`

## 6. Run the Main Script
`poetry run python .\project_cloud_native\main.py`

## 7. Install pytest for Testing
 `poetry add pytest`

 ## 8. Run Tests with pytest
 `poetry run pytest`

 ## Notes
Always use poetry run before python to ensure the correct virtual environment is used.

Use poetry add <package_name> to install new dependencies.

Use poetry run pytest to execute unit tests.