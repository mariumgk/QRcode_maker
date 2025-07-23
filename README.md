**QR Code Generator – Flask Project**
📁 Project Structure
├── app.py                # Main Flask application
├── requirements.txt      # Dependencies
├── templates/
│   └── index.html        # UI form
└── README.md             
________________________________________
 How to Run This Project in VS Code
 Prerequisites
•	Python 3.10 or 3.11 installed (some libraries don’t support latest version)
•	VS Code installed
•	Python extension for VS Code installed (usually prompts to install if not)
________________________________________
Step-by-Step Instructions
1. Open the Project in VS Code
•	Unzip the project folder if zipped
•	Open it in VS Code:
File → Open Folder → select qr_code_maker
________________________________________
2. Create and Activate a Virtual Environment 
Open a terminal in VS Code:
Terminal → New Terminal
Then run:
# Create a virtual environment
python -m venv venv

# Activate it
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
Once activated, your terminal will show (venv) prefix.
________________________________________
3. Install Required Packages
pip install -r requirements.txt
________________________________________
4. Run the Flask App
Still inside the virtual environment, run:
python app.py
You’ll see:
* Running on http://0.0.0.0:5000 
________________________________________
5. View in Browser (Desktop or Phone)
•	On PC: Visit
•	http://localhost:5000
•	On phone:
•	http://<your-laptop-IP>:5000
________________________________________
 Troubleshooting in VS Code
•	If Flask isn’t recognized, activate the virtual environment again
