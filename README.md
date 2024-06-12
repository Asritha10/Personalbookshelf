# Personalbookshelf
Developed a React app that helps book lovers like us discover new reads and keep track of personal library. The key is to leverage the power of the Open Library API to search for books, and then use the browser's localStorage to store our own custom bookshelf.

## Screenshots

<img width="1435" alt="Screenshot 2024-06-12 at 8 41 18 PM" src="https://github.com/Asritha10/Personalbookshelf/assets/95580777/5243e4b8-0629-4b61-9630-e11efc9113b2">
<img width="1440" alt="Screenshot 2024-06-12 at 8 42 06 PM" src="https://github.com/Asritha10/Personalbookshelf/assets/95580777/0862ed78-6171-4c3e-a1ac-8f2f3d4b6f46">
<img width="1421" alt="Screenshot 2024-06-12 at 8 42 39 PM" src="https://github.com/Asritha10/Personalbookshelf/assets/95580777/5996a3a3-f7fd-47d9-976e-414b459e1049">

## Tech Stack

- React
- JavaScript
- JavaScript XML
- CSS

## Setup

To set up the project locally, follow these steps:

1. Clone the repository: git clone https://github.com/Asritha10/Personalbookshelf.git

2. Navigate to the project directory: cd personal-bookshelf

3. Install dependencies: npm install

## Usage

To run the application on a local machine, use the following command: npm start

This will start the development server. Open http://localhost:3000 to view it in the browser.

## Pages

### Book Search Page

- Enter a book's name in the input field to search.
- Search results will be displayed in real-time as you type.
- Click on the "Add to Bookshelf" button to add a book to your personal bookshelf.

### Personal Bookshelf Page

- View all the books you have added to your personal bookshelf.
- Books are stored persistently using the Web Storage API (localStorage).
- The pages are responsive to different screen sizes for a seamless experience across devices.

### API Usage and Data Fetching

The application efficiently utilizes the Open Library API for fetching book search results.

### React Component Structure and Interactivity

The React components are structured properly, ensuring smooth interactivity and user experience.

### Styling and Layout Presentation

The application is styled effectively, providing an intuitive interface and pleasing layout presentation.

## Deployment

The project is deployed on Netlify and can be accessed [here] https://asrithav.netlify.app/
