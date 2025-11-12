# Personal Profile Page

A simple, elegant web application for displaying a personal profile page.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Dark/Light Mode**: Toggle between dark and light themes with persistent preference
- **Animated Skills**: Visual skill bars with smooth animations
- **Modern UI**: Clean and professional design with smooth transitions
- **Contact Information**: Easy-to-update contact details and social links

## How to Run

### Option 1: Open directly in browser
Simply open the `index.html` file in your web browser:
- Double-click on `index.html`, or
- Right-click and select "Open with" your preferred browser

### Option 2: Using a local server (recommended)
For the best experience, run a local web server:

**Using Python 3:**
```bash
python -m http.server 8000
```

**Using Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

**Using Node.js (with npx):**
```bash
npx http-server
```

Then open your browser and navigate to `http://localhost:8000`

## Customization

To personalize the profile page, edit the following files:

### index.html
- Update your name, title, and profile information
- Modify the skills section with your own skills
- Update contact information and social links
- Replace the profile picture URL

### styles.css
- Change color scheme by modifying CSS variables in `:root`
- Adjust spacing, fonts, or layout as needed

### script.js
- Add additional interactivity or animations
- Customize theme toggle behavior

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript (ES6+)
- LocalStorage API for theme persistence

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)
