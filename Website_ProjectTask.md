
# Mylo Removalist Website

A beginner‑friendly project to learn **Java web development** with **HTML, CSS, and modular design** hosted on **AWS EC2 Ubuntu**.  
The website includes three main pages: **Landing**, **Services**, and **Contact**, with a focus on **high cohesion, low coupling**.

---

## **Project Objectives**

1. Learn basic **HTML/CSS** structure for a business website.
2. Understand modular web development principles in **Java**.
3. Host and run the project on **AWS EC2 (Ubuntu)**.
4. Practice high cohesion (group related tasks) and low coupling (separate concerns).

---

## **Project Steps**

### **Step 1: Setup**
- Install **Java (JDK 17+)**, **Git**, and a simple IDE (IntelliJ/Eclipse).
- Set up an **EC2 Ubuntu** instance with SSH access.
- Initialize a Git repository:  
  ```bash
  git init
  ```

### **Step 2: Project Structure**
- Create a modular Java project:
  ```
  /MyloWebsite
    /src
      /main/java
      /main/resources
    /web
      index.html
      services.html
      contact.html
    /assets
      /css
      /img
  ```
- Maintain **separate CSS** and **images** folders.

### **Step 3: Landing Page**
- Build a basic **HTML landing page**:
  - Business Name & Motto
  - Rotating Image Gallery
  - Navigation Links: About | Services | Contact
- Add minimal **CSS styling** for layout and typography.

### **Step 4: Services Page**
- Create a **Services** page:
  - Info Blocks for each service
  - Images of vehicles or team in action
  - “Book” buttons (placeholder links)

### **Step 5: Contact Page**
- Add a **Contact** page:
  - Static Info: Name, Phone, Email
  - Contact Form / Booking Module (can embed Google Form or Calendly)
  - Responsive design elements

### **Step 6: Java Backend (Optional for Learning)**
- Use a **simple Java HTTP server** or **Servlets** to serve pages.
- Optional: Store form submissions in a text file or console output.

### **Step 7: Deploy to EC2**
- Copy project files to EC2 with `scp` or Git pull.
- Run your Java server or serve static HTML using Apache.
- Test your website via the EC2 public IP.

---

## **Learning Tasks**
- [ ] Build static HTML pages with proper linking.
- [ ] Add CSS styling for layout and mobile responsiveness.
- [ ] Create modular file structure for high cohesion and low coupling.
- [ ] Set up Java server (optional).
- [ ] Deploy to EC2 and verify.
