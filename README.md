# InstagramClone
An Instagram clone implemented with client-side dynamic pages. Using REST API, JavaScript programming, and asynchronous programming (AJAX).

How to run:
✅ 1. Create and Activate a Python Virtual Environment
bash
Copy
Edit
python3 -m venv env
source env/bin/activate
✅ 2. Install Python Dependencies
bash
Copy
Edit
pip install -r requirements.txt
pip install -e .
✅ 3. Install Node Dependencies
bash
Copy
Edit
npm ci
⚠️ Do not use npm install. Use npm ci to match the autograder.

✅ 4. Build the Frontend
bash
Copy
Edit
npx webpack

✅ 5. Run the App
npx webpack --watch &
flask --app insta --debug run --host 0.0.0.0 --port 8000
✅ 6. View in Browser
Open:

arduino
Copy
Edit
http://localhost:8000/
✅ 7. Reset the Database (Optional)
bash
Copy
Edit
./bin/instadb reset
