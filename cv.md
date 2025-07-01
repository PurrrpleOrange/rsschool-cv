# Akhmat Latyev
---
## 📞 Contact Information
- Email: latyev.me@gmail.com  
- Telegram: [@purrpleorange](https://t.me/purrpleorange)
- GitHub: [purrrpleorange](https://github.com/purrrpleorange)
- Discord: PurrpleOrange
- Discord rs-school: Akhmat Latyev (@PurrrpleOrange)

---
## 👾 About me

![alt text](image-1.png)

---
## 🛠️ Skills
- ☕ Java SE 17
- 🌱 Spring Boot (In progress...)
- 🐘 PostgreSQL
- 🐱 Git & GitHub
- 🎨 Frontend basics: HTML, CSS, JavaScript (ES6), React (basic), Bootstrap
- 💻 IntelliJ IDEA, VS Code, Maven, Postman
- 🗂️ UML, BPMN, IDEF0

---
## 🧾 Code exmaples
```
const filteredDeliveries = deliveries.filter(d => {
    const lowerQuery = searchQuery.toLowerCase();
    const matchesQuery =
      (d.status || '').toLowerCase().includes(lowerQuery) ||
      (d.request?.documentNumber || '').toLowerCase().includes(lowerQuery) ||
      (d.request?.supplierName || '').toLowerCase().includes(lowerQuery) ||
      (d.documentNumber || '').toLowerCase().includes(lowerQuery);

    const matchesDate = !dateFilter || d.deliveryDate === dateFilter;
    return matchesQuery && matchesDate;
  });
  ```
---
## 🧑‍💼 Experience

## 📂 Projects

### 📦 SRM System — Full-Stack Web Application (Diploma Project) 

A full-stack Supplier Relationship Management system for an online bicycle store.  
Developed as a final qualification project during studies at RTU MIREA.

📅 Feb 2025 – Jun 2025  
🧑‍💻 Tech stack: Java SE 17, Spring Boot 3, PostgreSQL, React, REST API

**GitHub Repositories:**  
- 🔗 [Backend](https://github.com/PurrrpleOrange/srm-backend) — Java, Spring Boot, JPA, PostgreSQL  
- 🔗 [Frontend](https://github.com/PurrrpleOrange/srm-frontend) — React, Bootstrap, Axios

#### ✅ Key Features

- RESTful API for managing suppliers, products, supply requests, deliveries, and returns
- Relational PostgreSQL database with normalized schema, foreign keys, and constraints
- Layered backend architecture with clear separation: controller → service → repository
- React frontend with Bootstrap components and integration via axios
- Multi-role access system (ADMIN, MANAGER, WAREHOUSE)
- Business process modeling in BPMN and IDEF0 for system documentation
- Full technical documentation: ER diagrams, endpoint specs, and architecture overview

> 🔸 Authentication with JWT was planned but not implemented due to deadline constraints.

---
## 🎓 Education

**RTU MIREA – Russian Technological University**  
_Bachelor’s Degree in Software Engineering_  
Faculty of Information Technologies, Department of Corporate Information Systems  
📍 Moscow, Russia  
📅 2021 – 2025

---
## 🌍 Languages

- Russian — native  
- English — B1 (Intermediate): can read technical documentation and communicate in writing

