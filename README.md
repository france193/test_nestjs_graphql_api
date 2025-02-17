# 🟢 NestJS GraphQL CRUD API with Users Module

This project is a **NestJS GraphQL API** implementing full **CRUD operations** for a **Users** module. The GraphQL API is built using the **Code-First** approach and utilizes **TypeORM** for database operations with **SQLite**.

## 📂 Project Structure

```
nestjs-graphql-crud/
├── src/
│   ├── app.module.ts
│   ├── main.ts
│   └── users/
│       ├── dto/
│       │   ├── create-user.input.ts
│       │   ├── update-user.input.ts
│       ├── entities/
│       │   └── user.entity.ts
│       ├── users.module.ts
│       ├── users.resolver.ts
│       └── users.service.ts
├── .env
├── users.graphql.http
├── package.json
└── tsconfig.json
```

---

## 🛠️ Installation and Setup

### 1️⃣ **Install Dependencies**

```bash
npm install
```

### 2️⃣ **Environment Setup**

Create a `.env` file:

```env
PORT=3000
DATABASE_URL=sqlite://database.sqlite
```

### 3️⃣ **Run the Server**

```bash
npm run start:dev
```

The GraphQL Playground will be available at:
🔗 [http://localhost:3000/graphql](http://localhost:3000/graphql)

---

## 🚀 GraphQL Operations

### 📌 Using `users.graphql.http` for Testing

You can test all operations using the provided `users.graphql.http` file with the **REST Client extension** in VSCode. Simply run each request from the file.

To install the extension, search for **"REST Client"** in the VSCode Extensions Marketplace.

---

## 🧪 Running Tests

```bash
# Run HTTP requests from users.graphql.http
# Ensure REST Client extension is installed
```

---

## 📝 Technologies Used

- **NestJS**
- **GraphQL (Apollo)**
- **TypeORM**
- **SQLite**
- **TypeScript**
- **Class-validator/Class-transformer**

---

## 🚀 Commands Summary

```bash
# Create Users Module
nest g module users
nest g service users
nest g resolver users
```

---

## 📜 License

This project is licensed under the MIT License.
