## Admins Resources

### **註冊管理員**
* **URL:** `/api/v1/admins`
* **Method:** `POST`
* **Body:**
```
{
  "mail": "<註冊的mail>",
  "password": "<登入的密碼>"
}
```
* **Response** 
```
{
  "token": "xxxxxxxxxxxxxxxxxxxxxxxx"
}
```

### **管理員登入**
* **URL:** `/api/v1/admins/session`
* **Method:** `POST`
* **Body:**
```
{
  "mail": "<註冊的mail>",
  "password": "<登入的密碼>"
}
```
* **Response** 
```
{
  "token": "xxxxxxxxxxxxxxxxxxxxxxxx"
}
```

### **檢查管理員token是否可用**
* **URL:** `/api/v1/admins/token`
* **Method:** `GET`
