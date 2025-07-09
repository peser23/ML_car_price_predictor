# Flask App

This is a simple Flask web application following best practices:
- Uses blueprints for modularity
- Keeps configuration and secrets out of source code

## Project Structure
- `app.py`: Application entry point
- `templates/`: HTML templates
- `.github/copilot-instructions.md`: Copilot custom instructions
- `requirements.txt`: Python dependencies

## Running the App

1. Install dependencies (already handled if using the provided environment):
   ```powershell
   c:/work/Projects/ML/car_data/.venv/Scripts/pip.exe install -r requirements.txt
   ```
2. Start the Flask app:
   ```powershell
   c:/work/Projects/ML/car_data/.venv/Scripts/python.exe app.py
   ```
3. Open your browser to http://127.0.0.1:5000/

## Notes
- For production, use environment variables for configuration and secrets.
- Extend the app using blueprints for additional modules/routes.
