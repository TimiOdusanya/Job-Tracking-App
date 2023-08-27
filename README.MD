#### Project Setup

In order to spin up the project, in the root create .env with these two variables, with your own values.

MONGO_URI
JWT_SECRET

After that run this command

```bash
npm install && npm start
```

Swagger UI

```yaml
/jobs/{id}:
  parameters:
    - in: path
      name: id
      schema:
        type: string
      required: true
      description: the job id
```
# Job-Tracking-App


Welcome to the Job Tracker app repository! This project is designed to simplify and enhance your job search process. With this app, users can easily manage their job applications, track progress, and stay organized throughout their job hunt journey.

Key Features:
- User authentication and secure login.
- Intuitive dashboard to manage job applications and track their statuses.
- User-friendly interface for adding new job applications with details like company, role, date applied, and more.
- Customizable application stages (e.g., applied, interview scheduled, offer received) to fit your job search process.
- Visual progress indicators to quickly assess application statuses.
- Reminder functionality to help you stay on top of follow-ups and interviews.
- Secure storage of sensitive information.
- Responsive design for seamless usage on different devices.

Technologies Used:
- React.js for building dynamic and interactive user interfaces.
- Node.js and Express.js for creating the backend API.
- MongoDB (or your chosen database) for storing user and application data.
- User authentication using JWT tokens for data security.
- RESTful API design principles for smooth data communication.
- Responsive CSS framework (e.g., Bootstrap) for a modern and user-friendly design.

Whether you're actively job hunting or just want to keep your job applications organized, the Job Tracker app is here to help. Feel free to explore, contribute, or use this project as a foundation for your own personalized job tracking solution.

Happy job hunting!

