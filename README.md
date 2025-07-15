## 📷 Mini Instagram (Console-Based C++ Project)

A fully functional, object-oriented, console-based **social networking simulation** written in **C++**, mimicking core features of platforms like Instagram. This system allows user registration, authentication, post creation, follower management, and private messaging — all without any external libraries or databases.

---

### 🧠 Features

* ✅ User Registration with Strong Password Validation
* 🔐 Login, Logout, and Password Reset (Security Q\&A)
* 👥 Follow/Unfollow Users with Status & Relationship Type
* 🗣️ Private Messaging (Stack-based per-follower)
* 📝 Post Creation with Timestamps
* 🔍 Advanced User Search & Relationship Discovery
* 🌲 Efficient User Storage using Binary Search Tree (BST)
* 📦 Persistent, in-memory data using object pointers and linked lists

---

### 🚀 Technologies Used

* C++ (OOP Concepts)
* Standard Library:

  * `<stack>`, `<string>`, `<ctime>`, `<conio.h>`
* Data Structures:

  * Custom Linked Lists
  * Binary Search Tree (BST)
  * Stack (for messages & posts)

---

### 📸 Core Classes & Structures

* `User` — Manages profile, login, posts, followers, messaging.
* `BST` — Stores users alphabetically by username.
* `Stack` — Used for time-stamped posts & messages.
* `follower_edge` — Represents relationships & message stacks.
* `createUsers` — Manages registration, login, and password reset.

---

### 🧪 How to Use

1. **Clone Repository**

   ```bash
   git clone https://github.com/your-username/mini-instagram.git
   cd mini-instagram
   ```

2. **Compile**

   * Windows (Visual Studio or g++)

     ```bash
     g++ -o mini-instagram main.cpp
     ```

3. **Run**

   ```bash
   ./mini-instagram
   ```

---

### 📖 Menu Overview

```
1. Register a new user
2. Login as a user
3. Logout current user
4. Relationship features (follow, view followers/following)
5. Post content
6. View posts
7. Reset password
8. Search users (basic and advanced)
9. Messaging (send, view latest, view all)
10. Exit
```

---

### 📌 Password Rules

* Minimum 12 characters
* At least:

  * 1 Uppercase letter
  * 1 Digit
  * 1 Special character (e.g., `@`, `!`, `#`)

---

### 📬 Messaging Rules

* Messaging allowed only if:

  * Users follow each other
  * Relationship status is `active`

---

### 👨‍💻 Author

**Bilal Kalyar**
[GitHub Profile »](https://github.com/BilalKalyar-200)

---

### 📄 License

This project is open source and available under the [MIT License](LICENSE).
