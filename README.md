## 📌 Student Website Development - Agile Process

This project follows an **Agile methodology** to develop a **Student Website**, utilizing **sprints** for iterative development, testing, and deployment.

### 📊 Agile Workflow Diagram

```mermaid
graph TD
A((Student Website)) --> B(Backlog Creation)
B --> C(Sprint Planning)
C -->D{Sprint 1}
D --> D1[Design Login Page]
D --> D2[Setup Database]
D --> D3[Implement Authentication]
D1-->E1[Code Review]
D2-->E2[Code Review]
D3-->E3[Code Review]
E1-->F1[Test Login Page]
E2-->F2[Test DB Connection]
E3-->F3[Test Authentication Security]
F1-->G1[Sprint1 Review]
F2-->G1
F3-->G1
G1-->H1[Sprint Retrospective]
H1-->I{Sprint2}
I-->I1[Student Activities Dashboard]
I-->I2[Add Course]
I1-->J1[Test Dashboard]
I2-->J2[Test Course Flow]
J1-->K1[Sprint 2 Review]
J2-->K1
K1-->L((Deployment and Maintenance))
```

---

### 🔹 Development Process  

#### 📍 **1. Backlog Creation**  
- Define the core features required for the **Student Website**.  

#### 📍 **2. Sprint Planning**  
- Identify tasks for each sprint cycle.  

#### 📍 **3. Sprint 1 - Core Features**  
✅ Design and Implement:  
   - **Login Page UI**  
   - **Database Setup**  
   - **User Authentication**  

✅ **Code Review & Testing:**  
   - Review Login, DB Setup, and Authentication.  
   - Test login flow, DB connection, and security vulnerabilities.  

✅ **Sprint 1 Review & Retrospective**  

#### 📍 **4. Sprint 2 - Advanced Features**  
✅ Implement:  
   - **Student Dashboard**  
   - **Course Management**  

✅ **Testing & Review:**  
   - Validate Dashboard UI & Course addition functionality.  
   - Sprint review and feedback incorporation.  

#### 📍 **5. Deployment & Maintenance**  
- Deploy the system on a cloud platform (e.g., Vercel, Firebase, Heroku).  
- Regular maintenance and feature updates.  

---

### 🚀 **How to Use**  
- Modify the **Mermaid diagram** based on project requirements.  
- Track sprint progress using Agile boards like **JIRA or Trello**.  
- Ensure continuous integration and deployment (CI/CD).  

📌 **Contribute:** Open for pull requests and improvements!  

---

### 🔗 **Author**  
Developed by **Chandra Prakash Bathula** | Passionate about **Agile & Web Development**  
