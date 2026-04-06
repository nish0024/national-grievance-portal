National Grievance Redressal Portal

Team ByteQuest

Problem Statement
<img width="1318" height="972" alt="image" src="https://github.com/user-attachments/assets/81fc9a4d-194d-4e98-ad8d-bf306f6ac92e" />

The objective of this project is to design and implement a transparent, AI-driven National Grievance Redressal Portal that automates grievance categorization, priority assessment, and real-time tracking in order to improve communication, accountability, and responsiveness between citizens and government authorities.

Project Overview

The National Grievance Redressal Portal is a full-stack web application built using the MERN stack and integrated with Google Gemini AI. The platform enables citizens to submit grievances through a simple interface. Each grievance is automatically analyzed by the AI system to generate a concise summary, assign a relevant category such as roads, water, or electricity, and determine its urgency level.

Government officials interact with the system through a secure admin dashboard that provides real-time visibility into all submitted grievances. This dashboard supports monitoring, analysis, and status updates, ensuring faster resolution and improved transparency in grievance handling.

Key Features

The system uses Gemini Flash for automated grievance analysis, including one-line summarization, category classification, and priority assessment. The admin dashboard updates in real time through a backend service running on Port 5000, allowing officials to track grievances as they are submitted. Citizens are able to track the complete lifecycle of their grievance using a unique MongoDB ObjectID. A built-in fail-safe demo mode ensures the user interface remains functional even during network interruptions or offline demonstration scenarios.

Technology Stack
<img width="1017" height="841" alt="image" src="https://github.com/user-attachments/assets/38822bdc-9b96-48b8-b0b2-a06780c14157" />

The application is developed using MongoDB for data storage, Express.js and Node.js for the backend, and React for the frontend. Google Gemini AI is used for natural language processing and grievance analysis.

Setup and Installation

To run the project locally, the backend server must be configured with a MongoDB connection string and a Gemini API key stored in a .env file. The database can be populated using the provided seed script. The backend runs on Port 5000, while the frontend runs as a separate client application. The admin dashboard is accessible through the /admin-dashboard route.

Usage

Citizens can file a grievance by entering their name and a brief description of the issue, such as a water supply problem. The system automatically processes the grievance using AI to determine its category and priority. Government officials can log in to the admin dashboard using the provided credentials to view AI-generated summaries, analytics, and grievance statuses. Citizens can track their grievance in real time using the generated grievance ID.
<img width="1885" height="913" alt="image" src="https://github.com/user-attachments/assets/a4e2e141-dfdc-43a3-b396-912d6cd90266" />

Demo and Presentation

A two-minute demonstration video showcasing the system workflow is available at
https://drive.google.com/file/d/18y9mMl5JG7jzAZJm6BnCYJw5oEtGThJo/view

The project presentation slides are available at
https://drive.google.com/file/d/19N-j7ogyM3la1G3vwzAlpVxei1zPnqIc/view

## 🔗 Live Demo
🚀 **Deploy Link:** [National Grievance Portal](https://byte-quest-ai-grievance-portal.vercel.app/)

Conclusion

The National Grievance Redressal Portal demonstrates how AI-driven automation can significantly improve governance workflows by reducing response time, increasing transparency, and empowering citizens with real-time grievance tracking. The system is scalable and can be extended with features such as multilingual support, notification services, and advanced analytics for policy-level insights.
