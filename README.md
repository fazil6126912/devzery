# Devzery Frontend Technical Assignment: API Chaining Dashboard

## Setup Instructions

To set up the project locally, follow these steps:

1. **Clone the Repository or Download the ZIP File**
   ```bash
   git clone https://github.com/fazil6126912/devzery-assignment.git
   ```
   or extract the downloaded ZIP file.

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Run the Application**
   ```bash
   npm run dev
   ```

4. **View the Live Website**
   Open your browser and navigate to [localhost:5173](http://localhost:5173/).

## Brief Explanation of Your Approach

1. **Project Setup**: I began by setting up a React project using `create-react-app`, and installed the necessary packages, including `axios` for API requests and `tailwindcss` for styling.

2. **Understanding API Workflows**: I utilized Postman to analyze the provided APIs and understand how to chain them together effectively.

3. **UI Development**: The user interface was designed to allow users to select APIs, input required data for POST requests, and visualize the API chaining process. Tailwind CSS was used to ensure a responsive and clean design.

4. **API Chaining Implementation**: 
   - Initially, I fetched the users' list via a GET request.
   - Users could then input details to create a new post using the selected `userId` from the previous API call.
   - Finally, I implemented a GET request to retrieve comments related to the created post.

5. **State Management**: React's `useState` was utilized to manage API responses, loading states, and user inputs effectively.

## Assumptions or Decisions Made

- It was assumed that only the specified mock APIs would be utilized for this assignment.
- The project focuses on functionality rather than aesthetic perfection, ensuring a clean yet functional UI.

## Completed Features

- **API Chaining:** Successfully implemented the chaining of multiple API calls.
- **GET and POST Requests:** Both types of requests were handled correctly, including appropriate state management.
- **Intuitive UI:** Designed a user-friendly interface that allows for API selection and input.
- **Loading and Error States:** Implemented indicators for loading and error states to enhance user experience.
- **Responsive Design:** Ensured the application is responsive across different devices.

## Known Issues

- **Responsiveness:** Although the design is intended to be responsive, further testing may be required to ensure compatibility across all device sizes.
- **Post API Functionality:** The functionality for the Create Post API is currently set up but needs further testing to ensure reliability.
- **Comments Retrieval Limitation:** The comments retrieval feature is currently set to only retrieve comments for a specific postId and may require additional implementation for broader functionality.

## Video Demo Link

- [Demo Video](https://drive.google.com/file/d/1ZGovi3gp35Av0CJRoJbENb_62Szk_mP9/view?usp=drive_link)
