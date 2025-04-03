# Writeit - Social Media Platform (Frontend)

![Writeit Logo](/imgs/logo.png)

Writeit is a modern social media platform focused on content sharing and community engagement. This repository contains the frontend implementation built with HTML, CSS, Bootstrap, and JavaScript.

## Features

### User Authentication
- Registration flow with profile completion
- Account verification system
- Profile management

### Content Feed
- Personalized post feed
- Upvote/downvote system (instead of traditional likes)
- Content sharing functionality
- Post creation with rich media support

### User Interaction
- Notification system
- Responsive design for all devices
- Dark mode support
- Interactive UI elements

## Technologies Used

### Frontend
- HTML5
- CSS3
- Bootstrap 5.3
- Bootstrap Icons
- Vanilla JavaScript

## Project Structure
```
writeit-frontend/
├── index.html               # Home/Landing page
├── feed.html                # Main content feed
├── profile.html             # User profile page
├── register.html            # Registration page
├── verify-account.html      # Account verification page
├── complete-profile.html    # Profile completion page
├── css/
│   └── style.css            # Main stylesheet
├── js/
│   └── main.js              # Main JavaScript file
└── imgs/                    # All image assets
    ├── logo.png             # Application logo
    ├── avatar/              # User avatars
    └── posts/               # Post images
```

## Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- GitHub account (for cloning)
- (Optional) Local web server for testing

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/writeit-frontend.git
   ```
2. Navigate to the project directory:
   ```bash
   cd writeit-frontend
   ```
3. Open the desired HTML file in your browser:
   ```bash
   # On macOS
   open index.html  
   
   # On Windows
   start index.html
   ```

## Usage

### Home Page (index.html)
- Landing page with platform introduction
- Navigation to registration/login

### Registration Flow
- `register.html` - Basic account creation
- `verify-account.html` - Email verification
- `complete-profile.html` - Profile customization

### Main Feed (feed.html)
- View and interact with posts
- Create new content
- Upvote/downvote system
- Share interesting content

### Profile Page (profile.html)
- View user profile
- See post history
- Edit profile info

## Customization

### Change Colors
Modify the CSS variables in `style.css`:
```css
:root {
  --primary-color: #198754; /* Bootstrap success green */
  --secondary-color: #146c43;
}
```

### Update Images
Replace files in the `imgs/` directory while maintaining the same filenames.

### Modify Content
Edit the HTML files to update text content.

## Contributing
Contributions are welcome! Follow these steps:

1. Fork the project
2. Create your feature branch:
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add some amazing feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request

## Screenshots

### Home Page
Landing Page

### Feed Page
Main Content Feed

### Profile Page
User Profile

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
Ahmed Bdiwy - [@bdiwy_](https://twitter.com/bdiwy_) - ahmed@example.com

Project Link: [https://github.com/your-username/writeit-frontend](https://github.com/your-username/writeit-frontend)

---

## Key Features of this README:

1. **Clear Structure**: Organized sections for easy navigation.
2. **Visual Elements**: Includes a logo and placeholders for screenshots.
3. **Comprehensive Documentation**: Covers all aspects of the frontend.
4. **Technical Details**: Lists all used technologies.
5. **Contribution Guidelines**: Encourages community involvement.
6. **Responsive Design**: The README itself is well-formatted for GitHub.

### How to Use This README:
1. Replace placeholder URLs with actual project links.
2. Add real screenshots to the `imgs/screenshots/` directory.
3. Update contact information.
4. Customize any sections to better match your project.

This README follows GitHub best practices, providing all necessary information for users and contributors to understand your frontend implementation.

