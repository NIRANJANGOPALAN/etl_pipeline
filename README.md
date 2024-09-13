# ETL Process: Storing REST API Data into SQL and NoSQL Databases

This project implements an ETL (Extract, Transform, Load) process to fetch joke data from a REST API and store it in a NoSQL database (MongoDB Atlas). The project also demonstrates how to structure the data for potential use in SQL databases.

## Description

This project extracts joke data from the JokeAPI, transforms it into a suitable format, and loads it into a MongoDB database. The process includes:

1. **Extracting** data from the JokeAPI.
2. **Transforming** the data by structuring it into a JSON format suitable for storage.
3. **Loading** the data into a MongoDB Atlas collection named `userData`.

### Key Features
- Connects to MongoDB Atlas using credentials stored in environment variables.
- Fetches jokes from the JokeAPI and stores them in the database.
- Provides functionality to display all stored jokes.
- Prepares data for potential conversion to CSV format.

## Prerequisites

- Python 3.x
- MongoDB Atlas account
- `pymongo`, `requests`, `dotenv`, and `pandas` libraries


