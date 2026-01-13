# Medical Appointment Booking Website

A comprehensive frontend application for booking medical appointments online. This project provides a user-friendly interface for patients to schedule appointments with healthcare providers.

## 📋 Project Overview

This Medical Appointment Booking website is designed to streamline the process of scheduling medical appointments. The application focuses on providing an intuitive and accessible platform for patients to manage their healthcare appointments efficiently.

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. Clone or download this repository
2. Navigate to the project directory
3. Open the HTML files in your web browser or use a local development server

### Running the Project

You can run the project in several ways:

**Option 1: Direct File Opening**
- Simply open `Landing_Page/LandingPage.html` in your web browser

**Option 2: Using a Local Server (Recommended)**
- Use Python's built-in server:
  ```bash
  python -m http.server 8000
  ```
- Or use Node.js http-server:
  ```bash
  npx http-server
  ```
- Then navigate to `http://localhost:8000` in your browser

## 📁 Project Structure

```
grihf-frontend_capstone_starter_code/
├── README.md
├── Landing_Page/
│   ├── LandingPage.html
│   ├── LandingPage.css
│   └── README.md
├── Navbar/
│   ├── Navbar.html
│   └── Navbar.css
├── Sign_Up/
│   ├── Sign_Up.html
│   └── Sign_Up.css
└── Login/
    ├── Login.html
    └── Login.css
```

## 🎨 Features

### Current Features
- **Landing Page**: Modern, responsive landing page with gradient text effects
- **Navigation Bar**: Fixed navigation with Home, Appointments, Sign Up, and Login links
- **Sign-Up Form**: User registration form with role selection (Patient/Doctor)
- **Login Form**: User authentication form with email and password fields
- **Responsive Design**: Mobile-friendly layout that adapts to different screen sizes
- **Modern UI**: Clean and professional design with animated effects
- **Form Validation**: Required field validation on all forms

### Planned Features
- User authentication and session management
- Doctor/Provider listing and search
- Appointment scheduling calendar
- Appointment management (view, edit, cancel)
- Patient profile management
- Notification system
- Appointment reminders

## 🛠️ Technology Stack

- **HTML5**: Structure and content
- **CSS3**: Styling and animations
- **JavaScript**: Interactivity (to be implemented)
- **Google Fonts**: Poppins font family
- **Font Awesome**: Icons (referenced in HTML)

## 📝 Development Notes

### Design Guidelines
- **Color Scheme**: 
  - Primary Blue: `#2190FF`
  - Gradient: Blue (`#2190FF`) to Purple (`#b673f8`)
  - Text Color: `#969BA5` for secondary text
- **Typography**: Poppins font family (weights: 100-900)
- **Responsive Breakpoints**:
  - Desktop: Default styles
  - Tablet: Max-width 980px
  - Mobile: Max-width 400px

### Code Style
- Use semantic HTML5 elements
- Follow BEM naming convention for CSS classes (where applicable)
- Maintain consistent indentation (spaces, not tabs)
- Comment complex CSS animations and JavaScript logic

### File Organization
- Keep HTML, CSS, and JavaScript files separate
- Use descriptive file names
- Group related components in folders
- Maintain a clear folder structure as the project grows

## 🔧 Customization

### Modifying Colors
Edit the CSS variables or direct color values in `LandingPage.css`:
- Primary button color: `.hero-section .button` background-color
- Gradient colors: `.text-gradient` background property

### Adding New Pages
1. Create a new HTML file in the appropriate folder
2. Link the corresponding CSS file
3. Update navigation links if applicable
4. Maintain consistent styling with existing pages

## 📱 Browser Compatibility

This project is designed to work on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🐛 Known Issues

- Currently, the landing page is a static page with limited functionality
- JavaScript interactivity needs to be implemented
- Backend integration is pending

## 🔮 Future Enhancements

1. **Backend Integration**: Connect to a REST API for data management
2. **Database**: Implement user and appointment data storage
3. **Authentication**: Add secure user login and registration
4. **Payment Integration**: Enable online payment for appointments
5. **Email Notifications**: Send appointment confirmations and reminders
6. **Admin Dashboard**: Create an interface for healthcare providers
7. **Search & Filters**: Advanced search for doctors by specialty, location, etc.
8. **Reviews & Ratings**: Allow patients to rate and review doctors

## 📚 Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS-Tricks](https://css-tricks.com/)
- [Google Fonts - Poppins](https://fonts.google.com/specimen/Poppins)

## 🤝 Contributing

When contributing to this project:
1. Follow the existing code style
2. Test your changes across different browsers
3. Ensure responsive design works on mobile devices
4. Update documentation as needed
5. Test all interactive features thoroughly

## 📄 License

This project is part of a capstone assignment. Please refer to your institution's guidelines for usage and distribution.

## 📞 Support

For questions or issues related to this project, please refer to your course instructor or project guidelines.

---

**Note**: This is a starter code template. Additional features and functionality need to be implemented as per project requirements.
