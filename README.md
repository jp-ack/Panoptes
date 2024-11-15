# Panoptes Project

## Authors

- Jean-Pierre Martinez/jp-ack
- Brian Chen/VX1632
- Ina Shanelle Noceja/hurinah
- Justin Ross/jross1092
## Overview
The Panoptes Project is designed to leverage advanced ChatGPT 3.5 models for text analysis and connect seamlessly with a MySQL database for data management. This project uses Docker containers to ensure easy setup and reproducibility.
- ChatGPT 3.5-based text processing.
- Integration with MySQL for persistent data storage.
- Dockerized environment for easy setup and cross-platform compatibility.

## Technology Stack

- Python 3.8
- MySQL
- Docker & Docker Compose

## Directory Structure

View this in markdown view for a better view

C:\Your_Docker_Directory\Panoptes_Project_2
│ docker-compose.yml
│ .env # remember to add your own key!
│ .gitignore
│ wait-for-it.sh
│ Panoptes_GPT
├── C:\Your_Docker_Directory\Panoptes_Project_2\Panoptes_GPT
│ ├── \app.data\
│ ├── \.streamlit\
│ │ └──  config.toml
│ ├── app.py
│ ├── app.txt  # output dump
│ ├── Dockerfile
│ ├── requirements.txt
│ └── wait-for-it.sh
└── C:\Your_Docker_Directory\Panoptes_Project_SQL
    └──init.sql
## Prerequisites

- Docker
- Docker Compose

## Dependencies

- openai==0.10.5
- streamlit==1.14.0
- sqlalchemy==1.4.31
- pandas==1.3.3
- pymysql==1.0.2


## Installation

1. **Clone the repo**:
git clone https://github.com/your_username/Panoptes_Project_GPT.git

2. **Navigate to the project directory**:
cd Panoptes_Project

3. Create a .env file
Add the following line without any quotation marks: 
OPENAI_API_KEY="your api key here"

5. **Start the services**:
docker-compose up --build


## Usage

This is still under development. This is only the backend part of the project; the front-end is still being developed and hammered out.

## License

Distributed under the MIT License. See LICENSE for more information.

## Acknowledgements

Project Dependencies:
- ChatGPT 3.5 API: Used for generating text based on user input.
- Streamlit: Used for building interactive web apps.
- SQLAlchemy: Used for database operations.
- Pandas: Used for data manipulation and analysis.
- Langchain-openai: Used for language processing tasks.
- PyMySQL: Used for interfacing with MySQL databases.
