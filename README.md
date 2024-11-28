# Flask Calculator Application

## Overview
This is a web-based calculator application built using Flask. It allows users to perform basic mathematical operations such as addition, subtraction, multiplication, and division. The project is designed with a clean UI using **Bootstrap** for styling and animations, and includes a structured folder hierarchy for scalability.

## Features
- Perform basic arithmetic operations: Addition, Subtraction, Multiplication, Division.
- Validates user input, ensuring correct numerical entries.
- Handles division by zero gracefully.
- Responsive design with Bootstrap.
- Simple and clean UI with smooth animations.

## Folder Structure
```
FlaskCalculator
│   app.py                  
│   requirements.txt        
│   README.md               
│
├───templates               
│       index.html          
             
```

## Prerequisites
- Python 3.x installed on your system.
- `pip` package manager.

## Installation
1. Clone the repository or download the source code:
   ```bash
   git clone https://github.com/yourusername/FlaskCalculator.git
   cd FlaskCalculator
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate     # On Windows
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   python app.py
   ```

5. Open your web browser and navigate to:
   ```
   http://127.0.0.1:5000
   ```

## Usage
- Enter two numbers in the input fields.
- Select an operation from the dropdown menu (Addition, Subtraction, Multiplication, Division).
- Click the "Calculate" button to see the result.
- The application will display the result or an error message if the input is invalid.

## Technologies Used
- **Python**: Backend logic.
- **Flask**: Web framework.
- **HTML, CSS, JavaScript**: Frontend.
- **Bootstrap**: Styling and responsiveness.

## Screenshots
_Add screenshots of the application interface here._

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---
