## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/MUHAMMED-FARIZ-KP/InventoryManagementSystem.git
cd InventoryManagementSystem

# Set up a virtual environment (optional but recommended)
python -m venv env
source env/bin/activate   # Linux/MacOS
env\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt

# Run migrations to set up the database
python manage.py migrate

# Start the development server
python manage.py runserver

# Access the application
# Open your browser and navigate to http://127.0.0.1:8000/
