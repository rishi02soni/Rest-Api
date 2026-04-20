# 🚀 REST API Project (Node.js + Express + MongoDB)

---

### 🔹 Get All Users
**GET /**
```bash
GET /api/users
```

---

### 🔹 Create User
**POST /**
```bash
POST /api/users
```

#### Body (JSON):
```json
{
  "name": "Rishi",
  "email": "rishi@example.com",
  "age": 21
}
```

---

### 🔹 Update User
**PUT /:id**
```bash
PUT /api/users/:id
```

---

### 🔹 Delete User
**DELETE /:id**
```bash
DELETE /api/users/:id
```

---

## 🧪 Testing APIs
You can test APIs using:
- Postman
- Thunder Client (VS Code Extension)
- cURL

---

## ❗ Common Errors & Fixes

### 🔸 MongoDB not connecting
- Make sure MongoDB is running locally
- Check your `MONGO_URI`

### 🔸 Port already in use
- Change PORT in `.env`

---

## 🌟 Future Improvements
- 🔐 Add JWT Authentication
- 🧾 Add Validation (Joi / express-validator)
- 📄 Pagination & Filtering
- 🌍 Deploy to Cloud (Render / AWS)

---

## 🤝 Contributing
Pull requests are welcome! Feel free to fork and improve.

---

## 📜 License
This project is open-source and free to use.

---

## 💡 Author
**Rishi Soni**

---

🔥 If you like this project, don't forget to star it!
