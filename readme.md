# Milestone application. 
_Note: The following requirements are made by making use of ChatGPT._

## Project description: 
The aim of this web application is to provide users with a platform to track and celebrate their personal achievements. 
The application enables users to create, update, and delete milestones that represent significant milestones or 
accomplishments in their lives. 

Each milestone consists of a title, description, date of achievement, and status. Users 
can view their own milestones in a user-friendly interface, sort them chronologically, and search for specific 
achievements. The application incorporates user authentication to ensure secure access to personal milestones.

In addition, there is a separate frontend designed specifically for administrators, who have the ability to manage user 
accounts and milestones. The backend of the application is built using the Laravel framework, while the frontend utilizes 
React for both regular users and administrators. The application emphasizes the importance of personal growth, motivation, 
and progress tracking, providing a meaningful and satisfying user experience.

## Requirements
### Backend (Laravel):
#### User Authentication:
- Integrate with the user authentication API to authenticate users and generate authentication tokens.
- Implement token-based authentication in Laravel to validate and authorize API requests.

#### User Management:
- Utilize the user management API to create, update, and delete user profiles.
- Implement user authentication and authorization mechanisms in Laravel based on the user management API.

#### Milestone Management:
- Integrate with the milestone management API to create, retrieve, update, and delete milestones.
- Implement API endpoints and controllers in Laravel to handle milestone-related operations and data validation.

### Frontend (React):
#### User Interface:
- Design and develop React components for user registration, login, profile management, and password reset for regular 
users.
- Design and develop separate React components for admin tasks and views.

#### Authentication:
- Utilize React libraries like react-router-dom for handling client-side routing.
- Implement authentication forms and logic using libraries like react-hook-form or Formik.
- Use the user authentication API to authenticate users and store authentication tokens.

#### User Management:
- Integrate with the user management API to manage user profiles (e.g., create, update, delete) for regular users.
- Implement React components and forms for user profile management, making appropriate API requests.

#### Milestone Display (Regular User Views):
- Consume the milestone management API to fetch milestones for the authenticated regular user.
- Develop React components to display milestones in a list or card format for regular users.
- Implement pagination or infinite scrolling using React libraries like react-infinite-scroll-component or react-paginate.

#### Admin Tasks and Views:
- Create a separate set of React components for admin tasks and views.
- Utilize the appropriate APIs for admin-related operations (e.g., CRUD operations on milestones, user management).
- Implement authentication and authorization mechanisms for admin tasks based on the user authentication and authorization provided by the backend.

> Remember to handle authentication tokens securely, use proper authorization mechanisms, and make authenticated API requests to the respective APIs for user authentication, user management, and milestone management.

> With this approach, your web application will have separate frontends for regular user tasks and admin tasks while  utilizing Laravel for backend operations and React for both frontend interfaces.
