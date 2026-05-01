# Project Name

This project consists of a form validator that verifies user registration.


## Screenshots
<img width="566" height="642" alt="ScreenShot Tool -20260501113604" src="https://github.com/user-attachments/assets/86426e95-6f42-4c93-ac4c-2ccaecb93fa6" />




## Features

- Feature 1: A user can register with their information and thr form validates to confirm everything is valid.
- Feature 2: The form alerts the user when they are successfully registered and the form resets itself.
- Responsive design
- Cross-browser compatible

## Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling and layout
- **JavaScript** - Interactivity and functionality

## Installation

1. Clone the repository:
```bash
git@github.com:kingcollinsdev/form-validator.git
```

2. Navigate to the project directory:
```bash
cd form-validator
```

3. Open `index.html` in your browser or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```

## Usage

Validates if a email input by a user is valid by using a general expression.

```javascript
// Example code snippet
const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
  if(emailRegex.test(email.value.trim())) {
    showSuccess(email);
    return true;
  } else {
    showError(email, "Email is not valid");
    return false;
  }
```

## Project Structure

```
project-name/
│
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── script.js       # Main JavaScript file
├── images/             # Image assets
└── README.md           # Project documentation
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)


## Contact

Your Name - Collins Wachira Ndegwa - collinswachira2004@gmail.com

Project Link: [https://github.com/kingcollinsdev/form-validator.git](https://github.com/your-username/project-name)

## Acknowledgments

- Inspiration :- https://www.youtube.com/watch?v=kAiX0itnonM&t=13648s
  
