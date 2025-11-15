# SETUP GUIDE

## Quick 5-Minute Setup Guide
1. Clone the repository:
   ```bash
   git clone https://github.com/albin-shajan-2004/albin_portfolio.git
   cd albin_portfolio
   ```
2. Install the required dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the root directory and set the necessary environment variables.
4. Start the application:
   ```bash
   npm start
   ```

## EmailJS Configuration Steps
1. Sign up for an EmailJS account at [EmailJS](https://www.emailjs.com).
2. Create a new service and generate a new template.
3. In your project's `.env` file, add the following variables:
   ```plaintext
   EMAILJS_USER_ID=your_user_id
   EMAILJS_SERVICE_ID=your_service_id
   EMAILJS_TEMPLATE_ID=your_template_id
   ```
4. Ensure that you have included the EmailJS SDK in your project.

## Personalization Instructions
- Open the email template in EmailJS and customize it according to your needs.
- Change the subject line, add your logo, and adjust the body content to match your branding.

## Color Customization
- Open the `styles.css` file.
- Modify the CSS variables or classes that define the colors:
   ```css
   :root {
       --primary-color: #3498db;
       --secondary-color: #2ecc71;
   }
   ```
- Replace the color codes with your preferred colors.

## Deployment Options
- Deploy your project using either of the following methods:
   - **Vercel:**
     1. Sign up at [Vercel](https://vercel.com).
     2. Import your repository.
     3. Follow the on-screen instructions to deploy.
   - **Netlify:**
     1. Sign up at [Netlify](https://www.netlify.com).
     2. Drag and drop your project folder or link your repository.

## Common Issues Troubleshooting
- **Issue:** Application not starting.
  - **Solution:** Check if all dependencies are installed and ensure you have the correct node version.

- **Issue:** EmailJS not working.
  - **Solution:** Double-check your EmailJS credentials in the `.env` file and ensure the EmailJS service is running properly.

- **Issue:** Custom styles not reflecting.
  - **Solution:** Clear your browser cache and try reloading the page.