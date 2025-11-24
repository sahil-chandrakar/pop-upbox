# Popup Box - Registration Form

A simple modal-based registration form built with vanilla JavaScript, HTML, and CSS. This project demonstrates the use of the HTML `<dialog>` element to create an interactive popup registration form.

## 📋 Features

- **Modal Dialog Form**: Interactive registration form that appears in a modal popup
- **Form Fields**:
  - Name input field
  - Email input field
  - Course selection dropdown (Java, Python, C++)
  - Skills selection checkboxes (HTML, CSS, Java, Spring, Python)
  - Text area for personal description
  - Submit button
- **Responsive Design**: Modern UI with flexbox layout
- **Clean Styling**: Custom CSS with Poppins font family and shadow effects
- **Vanilla JavaScript**: No framework dependencies, pure JavaScript event handling

## 📁 Project Structure

```
popup-box/
├── index.html          # Main HTML file with form structure and JavaScript
├── readme.md           # Project documentation
└── assests/
    ├── css/
    │   └── style.css   # Styling for the form and modal
    └── videos/         # Directory for video assets
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/sahil-chandrakar/pop_upbox.git
```

2. Navigate to the project directory:
```bash
cd popup-box
```

3. Open `index.html` in your web browser or use a local server:
```bash
# Using Python (if available)
python -m http.server 8000

# Then visit http://localhost:8000
```

## 🎨 How It Works

1. Click the **"Show Registration"** button to open the modal dialog
2. Fill in the registration form with your details:
   - Enter your name
   - Enter your email
   - Select a course from the dropdown
   - Check the skills you possess
   - Write a brief description about yourself
3. Click **Submit** to submit the form

## 🛠️ Technology Stack

- **HTML5**: Semantic markup with `<dialog>` element for modals
- **CSS3**: Flexbox layout, responsive design, custom styling
- **JavaScript (ES6)**: Event listeners and modal control

## 📝 File Descriptions

### `index.html`
Contains the HTML structure and JavaScript logic:
- Registration form with various input types
- Event listener for the "Show Registration" button
- Modal functionality using the HTML `<dialog>` element

### `assests/css/style.css`
Complete styling for the project:
- Global styles and Poppins font import
- Section layout and button styling
- Dialog and form field styling
- Responsive sizing using viewport-relative units (vw)



---

**Author**: Sahil Chandrakar  
**Repository**: [pop_upbox](https://github.com/sahil-chandrakar/pop_upbox)