# Career Growth Path

Career Growth Path is a self-hosted platform designed to help users achieve their career goals by providing structured learning roadmaps, step-by-step guidance, and personalized recommendations.

![Career Growth Path](https://your-image-url.com)

## Features
- User-friendly interface for goal selection
- Step-by-step career roadmaps
- Video lectures, quizzes, and curated learning materials
- Database management for user progress tracking
- Open-source and self-hosted

## Installation

### Using Docker
```shell
# Clone the repository
git clone https://github.com/your-username/career-growth-path.git
cd career-growth-path

# Run the application using Docker Compose
docker-compose up -d
```
Visit `http://localhost:5000`

### Manual Installation
1. Install dependencies:
   ```shell
   pip install flask flask-cors flask-sqlalchemy
   ```
2. Run the application:
   ```shell
   python app.py
   ```
3. Open `http://127.0.0.1:5000` in your browser.

## API Endpoints
### Add Career Goals
```http
POST /add_goals
```
**Request Body:**
```json
{
  "goals": ["Software Engineer", "Data Scientist", "Entrepreneur"]
}
```
**Response:**
```json
{
  "message": "Goals added successfully!"
}
```

## Contributing
We welcome contributions! To contribute:
1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Create a pull request

## License
Career Growth Path is licensed under the MIT License. See `LICENSE` for details.
