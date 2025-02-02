# Weather Update App

The Weather Update App provides weather information and allows users to subscribe to daily weather updates via email.

## Backend

### Prerequisites

- Flask
- Flask-Mail
- Flask-Cors
- Flask-APScheduler
- requests
- schedule


### Installation and Setup

1. Clone the repository:

    ```
    git clone https://github.com/Acutapugione/weather-app.git
    cd weather-app/backend
    ```

2. Set up the database:

    ```
    python3 backend/database.py
    ```

4. Run the Flask app:

    ```
    python3 backend/app.py
    ```
    ```
    python3 backend/mail.py
    ```

### Installation and Setup

1. Change directory to the frontend:

    ```
    cd ../frontend
    ```

2. Start a local HTTP server to serve the frontend:

    ```
    python3 -m http.server 9000
    ```

3. Access the app in your web browser at `http://localhost:9000`.

## Usage

- Visit the app in your web browser to view weather information and subscribe to updates.
- Enter your email to receive daily weather updates.
