# TheSoftmax

**TheSoftmax** is a data science-focused website designed to share research, topics, and personal projects related to AI, ML, and Data Science. 
It also includes a personal portfolio section to showcase my resume and work.

## 🌐 Live Website
[thesoftmax.com](https://www.thesoftmax.com)

## 🚀 Features
- AI, ML, and Data Science Research Articles
- Personal Portfolio & Resume Section
- Modern, Responsive Design
- Dark/Light Theme Toggle (Auto-detects system preferences)
- Security Measures with GitHub Actions for vulnerability checks

## 🛠️ Technologies Used
- **HTML5**, **CSS3**, **JavaScript**
- **GitHub Pages** for Hosting
- **GitHub Actions** for Security Automation

## 📦 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/thesoftmax.git
2. Navigate to the project folder:
   ```bash
   cd thesoftmax
4. Open index.html in your browser to view the website locally.

🔐 Security
This project uses GitHub Actions to automatically scan for security vulnerabilities with each update. You can find the workflow in the
 .github/workflows/security-check.yml file.

🖼️ Adding Your Own Content
  😎CSS & JS files are located in the assets folder.
  😎Add articles in the content folder (if applicable).
  😎For custom redirects, modify the 404.html file.

📄 License
This project is licensed under the MIT License.

🙋‍♂️ Developed by Vivek

---

### **Adding a Favicon (Logo) to Your Website Tab**

1. **Prepare Your Favicon:**  
   - Create an image (preferably 32x32 pixels) in `.ico`, `.png`, or `.svg` format.  
   - Name it `favicon.ico` (or `favicon.png`).  

2. **Upload the Favicon:**  
   - Place the favicon file in the root directory of your project (same level as `index.html`).  

3. **Add Code to `index.html`:**  
   Inside the `<head>` section, add the following line:  
      ```html
      <link rel="icon" href="favicon.ico" type="image/x-icon">
**Or, if it's a PNG:**
   <link rel="icon" href="favicon.png" type="image/png">
4. **Commit Changes:**
   ```bash
   git add .
   git commit -m "Added favicon to website"
   git push

Refresh your website, and you'll see the favicon appear on the browser tab!
