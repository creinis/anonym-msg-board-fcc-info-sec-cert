# Anonymous Message Board

###### Technologies:
<p align="center">
<img src="https://nodejs.org/static/images/logo.svg" height="35" alt="Node.js" style="margin: 10px 15px 0 15px;" />
<img src="https://expressjs.com/images/express-facebook-share.png" height="35" alt="Express" style="margin: 10px 15px 0 15px;" />
<img src="https://img.icons8.com/color/75/000000/mongodb.png" width="75" height="75" alt="MongoDB" style="margin: 10px 15px 0 15px;" />
<img src="https://img.icons8.com/color/75/000000/javascript.png" width="75" height="75" alt="JavaScript" style="margin: 10px 15px 0 15px;" />
<img src="https://img.icons8.com/color/75/000000/bootstrap.png" width="75" height="75" alt="Bootstrap" style="margin: 10px 15px 0 15px;" />
</p>

- **Node.js:** The JavaScript runtime environment used for building the server-side of the application. It handles HTTP requests and manages the backend logic.
- **Express.js:** A minimal and flexible Node.js web application framework that provides robust features for building web and mobile applications. It is used to create the API endpoints and manage middleware.
- **MongoDB:** A NoSQL database used to store message board data. It offers flexibility and scalability for handling large amounts of data.
- **JavaScript:** The primary programming language for both the backend (Node.js) and frontend logic. It enables interactive and dynamic features on the client-side.
- **Bootstrap:** A front-end framework used to design responsive web pages. It provides pre-designed components and CSS styles.

### Try it!
https://anonymous-message-board.freecodecamp.rocks/

#### Running Locally

1. **Clone the repository:**
   ```sh
   git clone https://github.com/creinis/anonym-msg-board-fcc-info-sec-cert.git
   cd anonymous-message-board
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Set up the environment variables:**
   Create a `.env` file in the root directory and add the following:
   ```env
   MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/anonymous-message-board?retryWrites=true&w=majority
   ```

4. **Connect to the database:**
   Ensure that your MongoDB server is running and accessible with the provided URI in the `.env` file.

5. **Run the server:**
   ```sh
   npm start
   ```

6. **Access the application:**
   Open your web browser and navigate to `http://localhost:3000`.

### Functionality

This project allows users to post and interact with anonymous messages on a message board. It supports creating threads, posting replies, reporting posts, and deleting posts. The board is designed to facilitate open communication while providing moderation features to manage content.

## Project Structure

- `server.js`: Main server file that sets up the Express server and connects to MongoDB.
- `routes/api.js`: Contains API routes for creating threads, posting replies, reporting, and deleting messages.
- `models/thread.js`: Defines the MongoDB schema for threads and messages.
- `public`: Directory containing static assets like CSS and client-side JavaScript.
- `views`: Directory containing the HTML templates rendered by the server.
- `tests`: Contains automated tests for verifying API functionality.
- `README.md`: Documentation file providing an overview of the project and its functionalities.

## Practical Use Case

An anonymous message board is a valuable tool for communities that need a space for open, anonymous communication. It can be used in educational settings, corporate environments, or public forums where users may prefer to share ideas or feedback without revealing their identities.

## Benefits

This project leverages modern web technologies to provide a robust, scalable, and user-friendly message board. The use of Node.js and Express ensures efficient server-side performance, while MongoDB offers a flexible database solution. Bootstrap enhances the frontend with a responsive design that works well on all devices.

---
#### This is a FreeCodeCamp Challenge for Information Security Certification
<p align="center">
<img src="https://cdn.freecodecamp.org/platform/universal/fcc_primary.svg" width="250" height="75" alt="freeCodeCamp" style="margin: 0 15px; opacity: 0.6" />
</p>