![WhatsApp Image 2025-09-13 at 16 39 35_64af2510](https://github.com/user-attachments/assets/d243e08d-752d-45f4-948b-f7f4eb46a47a)
![WhatsApp Image 2025-09-13 at 16 40 18_8becca4b](https://github.com/user-attachments/assets/7dd75eb9-7636-4320-a4c5-7a9c1a606b4c)
![WhatsApp Image 2025-09-13 at 16 44 08_9329d77c](https://github.com/user-attachments/assets/97e45a61-7352-4967-8dc6-77f287a7ee4c)
![WhatsApp Image 2025-09-13 at 16 44 29_24fe3379](https://github.com/user-attachments/assets/1ffabb7c-f3a3-4d60-807c-45fb04e83c5d)


The following screenshots show the working of the Student CRUD REST API developed using Express + Mongoose and tested in Postman:

Create (POST /api/students)

Added a new student record with fields name, age, and major.

API responded with 201 Created and returned the saved student object with _id.

Read (GET /api/students)

Retrieved all students stored in the MongoDB collection.

API responded with 200 OK and returned an array of student objects.

Update (PUT /api/students/:id)

Updated an existing student’s details using their unique _id.

API responded with 200 OK and returned the updated student object.

Delete (DELETE /api/students/:id)

Deleted a student record from the database using _id.

API responded with 200 OK and returned a success message.
