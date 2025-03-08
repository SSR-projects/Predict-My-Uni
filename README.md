# University Admission Prediction App

This project is a full-stack web application that allows students to register, submit their university ranks and waiting list positions, view admission predictions, and receive recommendations.

## Project Structure

```
university-admission-app
├── backend
│   ├── src
│   │   ├── app.js
│   │   ├── controllers
│   │   │   └── index.js
│   │   ├── models
│   │   │   └── student.js
│   │   ├── routes
│   │   │   └── index.js
│   │   └── services
│   │       └── predictionService.js
│   ├── package.json
│   └── README.md
├── frontend
│   ├── public
│   │   └── index.html
│   ├── src
│   │   ├── App.js
│   │   ├── components
│   │   │   ├── Register.js
│   │   │   ├── SubmitRank.js
│   │   │   ├── ViewPredictions.js
│   │   │   └── Recommendations.js
│   │   ├── services
│   │   │   └── apiService.js
│   │   └── index.js
│   ├── package.json
│   └── README.md
└── README.md
```

## Features

- **User Registration**: Students can create an account by providing their details.
- **Rank Submission**: Users can submit their university rank and waiting list position.
- **Admission Predictions**: The application provides predictions based on user input and historical data.
- **Recommendations**: Users receive recommendations on whether to wait for a preferred university or cancel admission elsewhere.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js with Express
- **Database**: MongoDB (for storing user data)

## Setup Instructions

### Backend

1. Navigate to the `backend` directory.
2. Install dependencies:
   ```
   npm install
   ```
3. Start the server:
   ```
   npm start
   ```

### Frontend

1. Navigate to the `frontend` directory.
2. Install dependencies:
   ```
   npm install
   ```
3. Start the React application:
   ```
   npm start
   ```

## API Endpoints

- `POST /api/register`: Register a new user.
- `POST /api/submit-rank`: Submit university rank and waiting list position.
- `GET /api/predictions`: Get admission predictions.
- `GET /api/recommendations`: Get recommendations based on user data.

## License

This project is licensed under the MIT License.