# 🌐 **Computer Networks Project 1** 🌐

### **Completed By**  
Justice Gauldin  

---

## 🌍 **Domain & Hosting** 🌐  
For this project, I chose to host the website using **GitHub Pages**, a free hosting service that allows deployment of static websites directly from a repository. I used a **GitHub subdomain** as it provides a simple and effective solution without the need for a paid domain.  

The setup process involved:  
- Configuring the repository ⚙️  
- Enabling **GitHub Pages** 🔧  
- Ensuring that the `index.html` file was placed in the root directory (or the designated branch) 🗂️  

---

## 🛠️ **Website Setup**  
The website was developed using basic web technologies:  

### **HTML** 📝  
I structured the website using HTML elements such as:  
- Headings 🔠  
- Paragraphs 📜  
- Lists 📋  

This ensured that the content was organized and easily accessible.  

### **CSS** 🎨  
Styling was applied using CSS, which included:  
- Background colors 🎨  
- Font selection 🖋️  
- A responsive container to ensure a clean and functional layout 📱  

---

## 🔐 **Security Enhancements**  
To ensure a secure browsing experience, I implemented the following security features:  

### **HTTPS Enforcement** 🔒  
- Since the website is hosted on **GitHub Pages**, it automatically benefits from **HTTPS**, ensuring encrypted and secure data transmission.  

### **XSS Protection** 🚫  
- Integrated **DOMPurify** to sanitize any potential user-generated content, preventing malicious script injection.  
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/dompurify/2.4.0/purify.min.js"></script>
