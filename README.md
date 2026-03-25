# 🧮 Calculator API

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-2.0+-lightgrey.svg)](https://flask.palletsprojects.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A simple and elegant REST API for basic calculator operations built with Flask. This project provides a clean interface for performing mathematical calculations via HTTP requests.

## ✨ Features

- 🚀 **Fast and Lightweight**: Built with Flask for minimal overhead
- ➕ **Addition**: Perform addition of two numbers
- 🔄 **Extensible**: Ready for more operations (multiplication, subtraction, division, etc.)
- 🧪 **Well Tested**: Comprehensive unit tests included
- 📡 **RESTful API**: Clean JSON-based endpoints

## 📦 Installation

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

### Setup

1. **Clone the repository** (if applicable) or navigate to the project directory:

   ```bash
   cd your-project-directory
   ```

2. **Create a virtual environment** (recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage

### Running the Application

Start the Flask development server:

```bash
python app.py
```

The API will be available at `http://localhost:5000`

### API Endpoints

#### GET `/api/test`

Returns a welcome message.

**Response:**

```json
{
  "message": "Hello World!"
}
```

#### POST `/api/add`

Adds two numbers.

**Request Body:**

```json
{
  "number_1": 5,
  "number_2": 3
}
```

**Response:**

```json
{
  "result": 8
}
```

**Error Response (Invalid Input):**

```json
{
  "error": "Invalid input"
}
```

### Example Usage with curl

```bash
# Test endpoint
curl http://localhost:5000/api/test

# Addition
curl -X POST http://localhost:5000/api/add \
  -H "Content-Type: application/json" \
  -d '{"number_1": 10, "number_2": 20}'
```

## 🧪 Testing

Run the test suite using pytest:

```bash
pytest test_app.py
```

Or using unittest:

```bash
python -m unittest test_app.py
```

## 🤝 Contributing

We welcome contributions! Here are some ways you can help:

### Current TODOs

- [ ] Implement multiplication operation (`/api/multiply`)
- [ ] Implement subtraction operation (`/api/subtract`)
- [ ] Implement division operation (`/api/divide`)
- [ ] Add advanced operations (square root, exponentiation, trigonometry)
- [ ] Add input validation and error handling
- [ ] Add API documentation with Swagger/OpenAPI

### How to Contribute

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Make your changes and add tests
4. Run tests: `pytest test_app.py`
5. Commit your changes: `git commit -am 'Add some feature'`
6. Push to the branch: `git push origin feature/your-feature-name`
7. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

If you have any questions or issues, please open an issue on GitHub or contact the maintainers.

---

_Made with ❤️ and Flask_</content>
<parameter name="filePath">c:\Users\win 10\Desktop\Code\DevOps\README.md
