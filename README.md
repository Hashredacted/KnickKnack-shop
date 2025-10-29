# 🛍️ KnickKnack-Shop
### A Full-Stack E-Commerce Platform

**Version:** 1.0.0  
**Author:** Mohammad Afnan Mirza  
**Department:** Computer Science / MCA / CAMS-3P01  
**Date:** October 2025  

---

## 🌐 Live Demo  
Deployed on **Render** — click below to explore the live application:  
👉 **[KnickKnack-Shop on Render](https://knickknack-shop.onrender.com)**  

*(Replace the link with your actual Render deployment URL once available.)*

---

## 📸 Screenshots  

| Screenshot | Description |
|-------------|--------------|
| ![Product Display](./assets/a.jpeg) | **Product Showcase:** Highlights featured KnickKnacks and categories |
| ![Product Details](./assets/c.jpg) | **Product Details Page:** Displays description, price, and Add-to-Cart options |
| ![Dashboard](./assets/img.webp) | **Admin Dashboard:** Product management and order tracking interface |

---

## 📘 Overview  

**KnickKnack-Shop** is a full-stack e-commerce application for selling and managing decorative items (“knickknacks”).  
It features a responsive user interface, secure payment gateway, and a powerful admin dashboard for inventory and order control.  

This project was built using the **Prototyping SDLC Model**, emphasizing iterative design, rapid user feedback, and continuous refinement to achieve optimal usability and system performance.

---

## ⚙️ Features  

### 👥 User Features  
- Register, login, and authenticate securely  
- Browse, filter, and view product listings  
- Add items to shopping cart and manage quantities  
- Checkout via **Stripe** payment gateway  
- Download order invoices in PDF format  
- Reset forgotten passwords via email (SendGrid API)  

### 🛠️ Admin Features  
- Add, update, or delete products with image uploads  
- Manage orders and invoices  
- Validate inputs using **express-validator**  
- Handle file uploads securely with **Multer**  

### 🔐 Security Features  
- CSRF protection with **csrf-csrf**  
- Password encryption using **bcrypt.js**  
- Input sanitization and session-based authentication  
- Secure environment variable configuration  

---

## 🧱 Tech Stack  

| Layer | Technology |
|-------|-------------|
| **Frontend** | HTML5, CSS3, EJS Templates |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (via Mongoose ODM) |
| **Authentication** | bcrypt.js, express-session |
| **Payments** | Stripe API |
| **Email Service** | SendGrid |
| **File Uploads** | Multer |
| **PDF Generation** | PDFKit |

---

## 🧩 SDLC Model Used  

**Model:** *Prototyping Model (Iterative Development)*  

The **Prototyping Model** was chosen for this project due to its flexibility and user-centric design process.  
Each prototype version was evaluated by users and supervisors to improve system flow, usability, and functionality before final deployment.

**Phases Followed:**  
1. Requirement Analysis  
2. Quick Design (Prototype)  
3. User Evaluation & Feedback  
4. Refinement of Prototype  
5. Final Development  
6. Testing & Deployment  

---

## 🧪 Testing and Validation  

### **Testing Summary**  
- **Total Test Cases:** 47  
- **Passed:** 43 (91.5%)  
- **Failed:** 2 (4.3%)  
- **Pending:** 2 (4.3%)  
- **Defects Found:** 4 (2 Critical, 1 Major, 1 Minor)  

### **Testing Types Performed**  
- ✅ Unit Testing (Controllers, Models)  
- ✅ Integration Testing (Routes, APIs)  
- ✅ System Testing (End-to-End Functionality)  
- ✅ Security Testing (CSRF, Session, Validation)  
- ✅ Performance Testing (Load & Stress Tests)  
- ✅ Usability Testing (UI/UX Review)  

### **Testing Conclusion**  
The system met all core functional and performance requirements.  
Minor issues were resolved post-validation.  
Application is **ready for deployment** with future scalability provisions in place.

---

## 🚀 Installation and Setup  

### **1️⃣ Prerequisites**  
- Node.js v16+  
- MongoDB v6+  
- npm v8+  

### **2️⃣ Clone Repository**
```bash
git clone https://github.com/yourusername/knickknack-shop.git
cd knickknack-shop
```

### **3️⃣ Install Dependencies**
```bash
npm install
```

### **4️⃣ Configure Environment Variables**  
Create a `.env` file in your project root:
```
db_url=mongodb://localhost:27017/knickknack-shop
S_Secret=<session-secret>
C_Secret=<csrf-secret>
stripe_key=<stripe-secret-key>
SG_API=<sendgrid-api-key>
Port=3000
```

### **5️⃣ Run the Application**
```bash
npm start
```

Then open:  
👉 [http://localhost:3000](http://localhost:3000)

---

## 📈 Future Enhancements  

### Short-Term (Next Update)
- Product search and filtering  
- Wishlist functionality  
- Mobile-friendly UI optimization  

### Medium-Term
- Admin analytics dashboard  
- Product ratings and review system  
- Coupon and discount management  

### Long-Term
- Redis caching for scalability  
- Microservices migration  
- AI-driven product recommendations  
- Android/iOS mobile app  

---

## 📚 References  

- [Express.js Documentation](https://expressjs.com/en/4x/api.html)  
- [MongoDB Official Docs](https://www.mongodb.com/docs/manual/)  
- [Mongoose Guide](https://mongoosejs.com/docs/guide.html)  
- [Stripe Checkout API](https://stripe.com/docs/api/checkout/sessions)  
- [Node.js API Docs](https://nodejs.org/docs/latest-v20.x/api/)  
- [OWASP Security Best Practices](https://owasp.org/www-project-top-ten/)  

---

## 👨‍💻 Author  

**Mohammad Afnan Mirza**  
📧 *mohammadafnanmirza@gmail.com*  
🎓 Department of Computer Science — MCA / CAMS-3P01  
🗓️ *October 2025*  
