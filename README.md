# Corestar Website

A modern, responsive website for Corestar, a technology-driven supply chain platform that connects global enterprises with the US market through intelligent logistics solutions.

## Website Structure

- **Home Page (`index.html`)**: Main landing page with company overview and key features
- **Contact Page (`contact.html`)**: Contact form and company information
- **Styling (`styles.css`)**: Custom styles for the website

## How to Test Locally

There are several ways to test this website locally:

### Method 1: Open Files Directly

The simplest way to test the website is to open the HTML files directly in your web browser:

1. Navigate to the folder containing the website files
2. Double-click on `index.html` to open it in your default web browser
3. Navigate between pages using the links in the navigation menu

### Method 2: Use a Local Server

For a more accurate representation of how the site will work when deployed, you can use a local server:

#### Using Python (Simple HTTP Server)

If you have Python installed:

```bash
# For Python 3
python -m http.server

# For Python 2
python -m SimpleHTTPServer
```

Then open your browser and go to `http://localhost:8000`

#### Using Node.js (with http-server)

If you have Node.js installed:

```bash
# Install http-server globally if you haven't already
npm install -g http-server

# Run the server
http-server
```

Then open your browser and go to `http://localhost:8080`

## Deploying to GitHub Pages

To deploy this website using GitHub Pages:

1. Create a new GitHub repository
2. Push all the website files to the repository
3. Go to the repository settings on GitHub
4. Scroll down to the "GitHub Pages" section
5. Under "Source", select "main" branch
6. Click "Save"
7. GitHub will provide you with a URL (https://yourusername.github.io/repository-name)

## Linking a Custom Domain

To link your custom domain to your GitHub Pages site:

1. Go to your domain registrar and add the following DNS records:
   - Type: A, Name: @, Value: 185.199.108.153
   - Type: A, Name: @, Value: 185.199.109.153
   - Type: A, Name: @, Value: 185.199.110.153
   - Type: A, Name: @, Value: 185.199.111.153
   - Type: CNAME, Name: www, Value: yourusername.github.io

2. In your GitHub repository:
   - Go to Settings > Pages
   - Under "Custom domain", enter your domain name
   - Click "Save"
   - Check "Enforce HTTPS" once the certificate is issued

## Customization

- Update the content in the HTML files to match your specific business information
- Modify the styles in `styles.css` to match your brand colors and design preferences
- Replace placeholder images with your own images
- Update the Google Maps embed in the contact page with your actual business location

## Technologies Used

- HTML5
- CSS3
- Bootstrap 5
- Font Awesome
- JavaScript (minimal)
