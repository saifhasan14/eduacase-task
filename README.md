# School Management APIs

This project provides APIs to manage school data using Node.js, Express.js, and MySQL. Users can add schools and retrieve a list of schools sorted by proximity to a specified location.

---

## API Endpoints

### Add School
- **Method**: `POST`
- **URL**: (https://eduacase-task-production.up.railway.app/api/addSchool)
- **Payload Example**:
  ```json
  {
    "name": "Riverdale High",
    "address": "101 Maple St",
    "latitude": 37.7749,
    "longitude": -122.4194
  }

### List Schools
- **Method**: `GET`
- **URL**: (https://eduacase-task-production.up.railway.app/api/listSchools?latitude=40.712776&longitude=-74.005974)
- **Query Parameters**

    `latitude`: User's latitude.

    `longitude`: User's longitude.

## Postman Collection

Access the Postman collection for testing:
- **URL**:[Postman Collection](https://drive.google.com/drive/folders/1Hd6HT2lFKFfN04ub-vZQyds2ovi5BJGO?usp=sharing)


This file includes the complete setup for running locally, Postman collection import, and usage instructions.
