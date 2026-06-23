# Create Your First Request (EchoAPI)

EchoAPI works just like Postman but inside VS Code.

You will manually create requests inside the EchoAPI panel.

---

# 🟢 GET ALL USERS

**Method:** GET  
**URL:**

```
http://localhost:3001/api/users
```

---

# 🔵 GET USER BY ID

**Method:** GET  
**URL:**

```
http://localhost:3001/api/users/PASTE_ID_HERE
```

---

# 🟡 CREATE USER

**Method:** POST  
**URL:**

```
http://localhost:3001/api/users
```

**Body (JSON):**

```json
{
  "name": "Charlie",
  "role": "Student"
}
```

---

# 🟠 UPDATE USER

**Method:** PUT  
**URL:**

```
http://localhost:3001/api/users/PASTE_ID_HERE
```

**Body (JSON):**

```json
{
  "role": "Instructor"
}
```

---

# 🔴 DELETE USER

**Method:** DELETE  
**URL:**

```
http://localhost:3001/api/users/PASTE_ID_HERE
```

---

# 🧪 WHAT YOU ACTUALLY DO IN ECHOAPI

Inside the VS Code panel:

1. Click ➕ New Request
2. Fill in request details

---

## GET ALL USERS

**Method:** GET  
**URL:**

```
http://localhost:3001/api/users
```

---

## CREATE USER

**Method:** POST  
**URL:**

```
http://localhost:3001/api/users
```

**Body → JSON tab:**

```json
{
  "name": "Charlie",
  "role": "Student"
}
```

---

3. Click ▶ Send

---

# 🎯 THAT’S IT

EchoAPI sends your request to the backend server, and your server returns the response.
