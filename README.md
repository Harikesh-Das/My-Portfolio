# Portfolio Website

A modern portfolio website built with Flask, featuring a responsive design and clean UI.

## Features

- Responsive design that works on all devices
- Modern and clean user interface
- Animated transitions and effects
- Project showcase with filtering
- Contact form
- About section with timeline for experience/education

## Preview

To see a live preview of the site, run the Flask application and navigate to `http://127.0.0.1:5000` in your web browser.

## Requirements

- Python 3.7 or higher
- Flask

## Installation

1. Clone this repository or download the files

2. Navigate to the project directory:
   ```
   cd portfolio-website
   ```

3. Create a virtual environment ( only if you have OCD else move to step 5, why waste env's XD):
   ```
   python -m venv venv
   ```

4. Activate the virtual environment:
   - Windows:
     ```
     venv\Scripts\activate
     ```
   - macOS/Linux:
     ```
     source venv/bin/activate
     ```

5. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:
   ```
   python app.py
   ```

2. Open your web browser and navigate to:
   ```
   http://127.0.0.1:5000
   ```

## Customization

### Personal Information

Edit the HTML templates in the `templates` folder to include your own information:

- Update your name, profession, and description in `index.html`
- Add your skills and experience in `about.html`
- Include your own projects in `projects.html`
- Update contact information in `contact.html`

### Images

Replace the placeholder images in the `static/images` directory with your own:

- Add your profile picture as `profile.jpg`
- Add project screenshots as `project1.jpg`, `project2.jpg`, etc.

### Styling

Customize the appearance by modifying the CSS in `static/css/styles.css`:

- Change the color scheme by updating the variables in the `:root` section
- Modify fonts, sizes, and other styling elements as needed

## License

This project is open source and available under the [MIT License](LICENSE).

## Credits

- [Font Awesome](https://fontawesome.com/) - Icons
- [Google Fonts](https://fonts.google.com/) - Fonts 
