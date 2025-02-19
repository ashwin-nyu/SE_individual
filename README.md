# Resume to HTML with Django

This project converts a resume into an HTML format using Django templates.

## Prerequisites
Ensure you have the following installed on your system:
- Python (>=3.10)
- Django (>=4.0)
- Virtual environment tool (optional but recommended)

## Installation and Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ashwin-nyu/SE_individual.git
   cd SE_individual
   ```

2. **Create and Activate a Virtual Environment (Recommended)**
   ```bash
   python -m venv venv  # Create virtual environment
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate  # On Windows
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Migrations** (if applicable)
   ```bash
   python manage.py migrate
   ```

5. **Run the Development Server**
   ```bash
   python manage.py runserver
   ```
   Open your browser and navigate to `http://127.0.0.1:8000/resume` to view the application.

## Customization
- Modify `resume/templates/resume_template.html` to adjust the HTML structure.
- Update `resume/views.py` to handle additional resume data.

## Troubleshooting
If you encounter issues:
- Ensure dependencies are installed correctly: `pip install -r requirements.txt`
- Check for syntax errors in `resume/views.py` or `resume/urls.py`
- Restart the Django development server after making changes

## License
This project is open-source. Feel free to modify and use it as needed.
