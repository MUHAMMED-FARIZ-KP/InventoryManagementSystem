


https://github.com/user-attachments/assets/67bb6222-7025-4896-ab64-25b72cb55567


## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/MUHAMMED-FARIZ-KP/InventoryManagementSystem.git
cd InventoryManagementSystem

# Set up a virtual environment (optional but recommended)
python -m venv env
source env/bin/activate   # Linux/MacOS
env\Scripts\activate      # Windows

# Get into Inventory folder
cd inventory

# Install dependencies
pip install -r requirements.txt

# Run migrations to set up the database
python manage.py migrate

# Start the development server
python manage.py runserver

# Access the application backend
# Open your browser and navigate to http://127.0.0.1:8000/

# Get into Front end Folder
cd inventory-frontend
npm install

# Access the application Frontend
npm start
# Open your browser and navigate to http://localhost:3000

