# Dog Walker API

A RESTful API built with Django and Django REST Framework for managing dog walker appointments across multiple cities.

## Models

- **Walker** - A dog walker
- **Dog** - A dog assigned to a walker
- **Appointment** - A scheduled walking appointment
- **City** - A city in which walkers operate

## Setup & Installation

### Prerequisites
- Python 3.10
- pip

### Steps

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd <project-directory>
   ```

2. **Create and activate a virtual environment**
   ```bash
   pipenv install
   pipenv shell
   ```

3. **Run migrations**
   ```bash
   python manage.py migrate
   ```

## API Endpoints

Each resource supports standard CRUD operations via the following routes:

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/walkers` | List all walkers |
| POST | `/walkers` | Create a walker |
| GET | `/walkers/{id}` | Retrieve a walker |
| PUT | `/walkers/{id}` | Update a walker |
| DELETE | `/walkers/{id}` | Delete a walker |
| GET | `/cities` | List all cities |
| POST | `/cities` | Create a city |
| GET | `/cities/{id}` | Retrieve a city |
| PUT | `/cities/{id}` | Update a city |
| DELETE | `/cities/{id}` | Delete a city |
| GET | `/dogs` | List all dogs |
| POST | `/dogs` | Create a dog |
| GET | `/dogs/{id}` | Retrieve a dog |
| PUT | `/dogs/{id}` | Update a dog |
| DELETE | `/dogs/{id}` | Delete a dog |
| GET | `/appointments` | List all appointments |
| POST | `/appointments` | Create an appointment |
| GET | `/appointments/{id}` | Retrieve an appointment |
| PUT | `/appointments/{id}` | Update an appointment |
| DELETE | `/appointments/{id}` | Delete an appointment |
