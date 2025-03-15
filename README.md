# FastAPI URL Shortener
 This is a simple URL shortener built with FastAPI as a homework project.

## Features
- Added docker-compose.yml
- Added Dockerfile
- Added motor library for MongoDB
- Switched to MongoDB
- Saves url to DB
- Gets url from DB
- Editing urls
## Installation
Clone the repository:
  ```bash
  git clone <your-repo-url>
  cd <your-repo-folder>
  ```
Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
Run the application:
  ```bash
  uvicorn main:app --reload
  ```
## Usage
Open http://127.0.0.1:8000/ in your browser to access the form.
Submit a long URL to get a shortened version.
Use the generated short URL to be redirected to the original link.
