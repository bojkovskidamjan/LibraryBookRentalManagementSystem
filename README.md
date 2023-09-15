# Library Book Rental Application

## Technologies Used

- Spring Boot for the backend API
- React for the frontend user interface
- H2 Database for data storage

## Project Structure

The project follows a layered architecture with the following components:

- Controllers: Handle HTTP requests and interact with services.
- Services: Contain business logic and interact with repositories.
- Repositories: Interface with the database.
- React Components: Build the user interface.
- React Hooks: Used for state management and effects.

## Data Model

The application stores the following data for books:

- ID (Long)
- Name (String)
- Category (Enum)
- Author (Author Entity)
- Available Copies (Integer)

Book categories can be NOVEL, THRILLER, HISTORY, FANTASY, BIOGRAPHY, CLASSICS, and DRAMA.

Author data includes:

- ID (Long)
- Name (String)
- Surname (String)
- Country (Country Entity)

Country data includes:

- ID (Long)
- Name (String)
- Continent (String)

## Features

- Add new books to the library.
- Update book information.
- Delete books that are no longer in good condition or will not be rented.
- Mark books as rented.
- View all books and book categories.
- Pagination to display a limited number of books per page.
- Navigation menu for easy access to different sections of the application.

## Getting Started

Follow these steps to set up and run the Library Book Rental Application:

### Backend (Spring Boot API)

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/bojkovskidamjan/LibraryBookRentalManagementSystem.git

2. Navigate to the project directory:

   ```bash
    cd library-book-rental

3. Run the Spring Boot application

### Frontend (React UI)

4. Navigate to the frontend directory within the project:
   
     ```bash
    cd frontend

5. Install the frontend dependencies:

    ```bash
      npm install

6. Start the React development server:

    ```bash
      npm start

7. Visit the localhost port http://localhost:3000/.


  

