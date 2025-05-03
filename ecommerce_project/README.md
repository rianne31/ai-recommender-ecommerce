# AI Recommender E-commerce

A modern e-commerce platform with AI-powered product recommendations.

## Features

- Product listing with categories
- Add new products
- Modern, responsive UI
- MongoDB integration
- AI-powered recommendations (coming soon)

## Tech Stack

- Python 3.10+
- Django 5.2
- MongoDB
- Bootstrap 5
- HTML5/CSS3

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-recommender-ecommerce.git
cd ai-recommender-ecommerce
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up MongoDB:
- Install MongoDB on your system
- Start MongoDB service
- The application will automatically connect to localhost:27017

5. Run migrations:
```bash
python manage.py migrate
```

6. Start the development server:
```bash
python manage.py runserver
```

7. Visit http://localhost:8000 in your browser

## Project Structure

```
ecommerce_project/
├── ecommerce_project/    # Project settings
├── store/               # Main application
│   ├── templates/      # HTML templates
│   ├── models.py       # Database models
│   ├── views.py        # View functions
│   └── urls.py         # URL routing
└── manage.py           # Django management script
```

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 