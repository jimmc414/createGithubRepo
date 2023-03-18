# Create GitHub Repository and Upload Files
This Python script allows you to create a new GitHub repository and upload files from your local directory to the repository.

Usage:
Make sure you have Python installed.
Set your GitHub personal access token as an environment variable or enter it when prompted.
Place the creategithubrepo.py file in the directory you wish to upload to a new GitHub repository.
Run the script using the following command:

python creategithubrepo.py
The script will create a new GitHub repository with the same name as the local directory, and upload all the files in the directory to the repository.

Run to install prerequisites:
```
pip install requests
```
Script Overview
The script consists of three main functions:

create_github_repo(repo_name, access_token): Creates a new GitHub repository with the given name and access token.
upload_file_to_github(repo_info, file_path, access_token): Uploads a file to the created GitHub repository.
Main script block: Handles the repository creation and file uploading process.
Make sure to provide the necessary GitHub personal access token to authenticate and authorize the script to perform the repository creation and file upload actions.
