# Portfolio Website with Backend

This is a full-stack portfolio website with a Node.js backend for handling contact form submissions.

## Features

- **Modern Design**: Glassmorphism, gradients, and smooth animations
- **Dark Mode**: Toggle between light and dark themes
- **Responsive**: Mobile-first design that works on all devices
- **Interactive Elements**: Hover effects, scroll animations, and loading screens
- **Backend Integration**: Contact form with email sending
- **Accessibility**: ARIA labels, focus states, and reduced motion support
- **Social Links**: Integrated social media icons
- **Testimonials**: Client feedback section
- **Resume Download**: Call-to-action button for CV

## Setup

1. Install dependencies:
   ```
   npm install
   ```

2. Configure email settings in `.env`:
   - `EMAIL_USER`: Your email address (e.g., your-email@gmail.com)
   - `EMAIL_PASS`: Your email app password (for Gmail, enable 2FA and generate an app password)

3. Start the backend server:
   ```
   npm start
   ```
   The server will run on http://localhost:3001

4. Open the website in your browser (Five Server should be running for the frontend).

## Deployment

- Frontend: Can be deployed to GitHub Pages, Netlify, or Vercel
- Backend: Deploy to Heroku, Railway, or similar platform
- Update email configuration for production

## Technologies Used

- HTML5, CSS3, JavaScript (ES6+)
- Node.js, Express, Nodemailer
- Font Awesome for icons
- Responsive design with CSS Grid and Flexbox

## Customization

- Update personal information in `portfolio.html`
- Modify colors and styles in `portfolio.css`
- Add real project links and images
- Configure social media links
- Add actual testimonials