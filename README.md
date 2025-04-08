# Collaborative Word Document

A real-time collaborative word document editor built with React, Express, Socket.IO, and MongoDB. This project allows multiple users to edit the same document in real-time, with changes instantly reflected across all users' screens. The application uses MongoDB for storing and retrieving the document data and Socket.IO for real-time updates.

## Features

- **Real-time Collaboration:** Multiple users can edit the same document at the same time.
- **Instant Updates:** Changes are immediately reflected across all connected users.
- **Document Storage:** All changes are saved to MongoDB, ensuring document persistence.
- **User Count:** Displays the number of active collaborators in the document.
- **Auto-Save:** Document is automatically saved to the backend every 2 seconds.

## Installation

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/) (or use MongoDB Atlas for cloud storage)

### Steps to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/PratyushSharma03/Collaborative_Word_Document.git
