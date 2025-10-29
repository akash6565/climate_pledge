# 🌍 Climate Action Pledge Microsite

A simple single-page website for users to take a climate pledge and record it to Google Sheets.

## 🚀 Deployment Instructions

1. **Upload to WordPress (or any static host):**
   - Upload `index.html` to your web server or use the WordPress "Custom HTML" block.
   - If using WordPress, paste this code inside a page or use a shortcode integration.

2. **Google Sheets Setup:**
   - Create a Google Sheet with columns: `Name, Email, State, Profile, Timestamp`.
   - Open Extensions → Apps Script, paste the backend code provided earlier.
   - Deploy as a Web App (Anyone can access) and get your Web App URL.
   - Replace `YOUR_SCRIPT_ID` in `index.html` with your Web App URL.

3. **Features:**
   - Responsive layout
   - Google Sheets backend
   - Personalized success message
   - Simple & clean design for all audiences

4. **Customization:**
   - Update colors or styles in the `<style>` tag.
   - Add more form fields or themes as needed.
