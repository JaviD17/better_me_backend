# BETTERME Backend

## Description
The backend for BETTERME, powered by FastAPI, provides a robust API for managing nutrition and workout data. It serves the browser frontend and will support the future mobile frontend.

## Prerequisites
- **Python**: Version 3.8 or higher.
- **MacOS**: Compatible with your MacBook M3 (16GB RAM).

## Installation
1. **Clone the repository**:
   ```zsh
   git clone https://github.com/username/better_me_backend.git
   cd better_me_backend
   ```
2. **Set up a virtual environment**:
   ```zsh
   python -m venv .venv
   source .venv/bin/activate
   ```
3. **Install dependencies**:
   ```zsh
   pip install -r requirements.txt
   ```

## Usage
1. **Run the FastAPI server**:
   ```zsh
   fastapi dev main.py
   ```
2. The API will be available at `http://localhost:8000` (default FastAPI port).
3. Ensure the frontend(s) are configured to communicate with this API (e.g., update API URLs in the frontend code).
4. Example endpoints:
   - `GET /users`: Retrieve user data.
   - `POST /workouts`: Log a workout.
   - Access the interactive API docs at `http://localhost:8000/docs`.

## Project Structure
- `main.py`: Entry point for the FastAPI application.
- `requirements.txt`: Lists dependencies, including `fastapi[standard]`.
- `.venv/`: Virtual environment (ignored by `.gitignore`).
- `.gitignore`: Ignores `.venv`, `__pycache__`, and other artifacts.

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```zsh
   git checkout -b feature-branch
   ```
3. Make your changes and commit:
   ```zsh
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```zsh
   git push origin feature-branch
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Related Repositories
- **Frontend**: [better_me_frontend](https://github.com/username/better_me_frontend)
- **Mobile Frontend** (Future): [better_me_mobile](https://github.com/username/better_me_mobile)