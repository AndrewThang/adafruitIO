## Installation

#### 1. Clone this repository
#### 2. Run redis server 
#### 3. Client
  ```bash
  cd client-adafruit 
  npm install
  npm start

#### 4. Server
  - Move to folder server
  ```bash
  cd server
  - Create a virtual enviroment and activate it
  ```bash
  python -m venv env
  source env/bin/activate
  - Install the required package
  ```bash
  pip install -r requirements.txt
  - Create a `.env` file
  ```bash
  GOOGLE_APPLICATION_CREDENTIALS = path_to_file_config_json
  ADAFRUIT_IO_USERNAME = your_user_io
  ADAFRUIT_IO_KEY = your_key_io
  - Run
  ```bash
  python manage.py runserver
