# E-Commerce Platform

This is a full-stack e-commerce platform developed with:

- ⚙️ Spring MVC (Backend)
- ⚛️ ReactJS (Frontend)

## Project Structure

```
ecommerce/
├── backend/   → Spring MVC project
├── frontend/  → ReactJS project
```

## Technologies

- Java 17 + Spring MVC + Thymeleaf + MySQL
- ReactJS + Tailwind CSS + Axios
- WebSocket (chat)
- Google OAuth 2.0 (login)
- Payment integrations: VnPay

## Getting Started

### Clone the project with submodules

```bash
git clone --recurse-submodules https://github.com/letrung2004/ecommerce.git
cd ecommerce
```

If you already cloned it without `--recurse-submodules`, run:

```bash
git submodule update --init --recursive
```

---

## Backend Setup (Spring MVC)

1. Open the `backend/` folder in your IDE (e.g., IntelliJ or Eclipse)
2. Configure MySQL connection in `application.properties`
3. Add your `firebase-service-account.json` if using Firebase
4. Run the project with **Tomcat 10+** or embedded Spring Boot

### Tomcat setup

- JDK 17
- Tomcat 10.x (Servlet 5.0+)
- Make sure `/backend` is deployed correctly in the server context

---

## Frontend Setup (ReactJS)

```bash
cd frontend
npm install
npm start
```

The React app will run at: `http://localhost:5173/`

---

## Notes

- Do **not** commit API keys or credentials to GitHub
