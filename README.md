# HolistiFit

HolistiFit is a full-stack fitness application integrating AI to provide personalized fitness guidance. The project is structured as follows:

## Project Structure

```
HolistiFit/
│── frontend/       # React.js frontend
│── backend/        # Node.js + Express backend
│── models/         # MongoDB schemas
│── routes/         # API endpoints
│── controllers/    # Logic handlers
│── chatbot/        # AI chatbot code
│── public/         # Static assets
│── package.json    # Project dependencies
│── .env            # Environment variables
│── README.md       # Project documentation
```

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **AI Chatbot**: Custom AI model integration

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm or yarn
- MongoDB

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/krtarun7/FitnessTracker.git
    ```

2. Navigate to the project directory:
    ```bash
    cd FitnessTracker
    ```

3. Install dependencies:
    ```bash
    cd frontend && npm install
    cd ../backend && npm install
    ```

4. Configure environment variables in `.env`.

### Running the Project

#### Start the Backend

```bash
cd backend
npm start
```

#### Start the Frontend

```bash
cd frontend
npm start
```

## Contribution

Feel free to contribute by submitting issues or creating pull requests.

## License

This project is licensed under the MIT License.