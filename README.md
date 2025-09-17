![WhatsApp Image 2025-09-13 at 16 35 28_5dc535b4](https://github.com/user-attachments/assets/306e8b95-0d03-4486-8aa9-7274d58b6274)


API Testing – GET /api/students

This screenshot demonstrates the successful execution of the GET request to retrieve all student records from the database. Using Postman, we accessed the endpoint at:

http://localhost:3000/api/students

The server responded with a 200 OK status, indicating that the request was processed successfully. The response is in JSON format and shows an array of student objects, each containing the following fields:

_id: Unique identifier assigned by MongoDB.

name: Student’s name.

age: Student’s age.

major: Student’s major or field of study.

createdAt: Timestamp of when the record was created.

__v: Internal version key used by Mongoose.

This confirms that the API is working correctly and is able to fetch stored student data from the MongoDB collection.
