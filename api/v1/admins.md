## Admins Resources

### **使用註冊**
* **URL:** `/api/v1/session/uuid`
* **Method:** `POST`
* **Body:**
```
{
  "displayName": "<玩家顯示的名字>"
}
```
* **Response** 
```
{
  "uuid": "xxxx-xxxx-xxxx-xxxx"
  "token": "xxxxxxxxxxxxxxxxxxxxxxxx"
}
```

### **取得玩家資訊**
* **URL:** `/api/v1/admins`
* **Method:** `GET`
* **Header:** `Authorization: JWT <Token String>`
* **Response:**
```
{
  "displayName": "<玩家顯示的名字>"
}
```

### **玩家登入**
* **URL:** `/api/v1/session`
* **Method:** `POST`
* **Body:**
```
{
  // 使用uuid登入
  "uuid": "xxxx-xxxx-xxxx-xxxx",
  // 使用facebook登入
  "facebookId": "xxxxxxxxxxxxxxxxx"
}
```
* **Response** 
```
{
  "token": "xxxxxxxxxxxxxxxxxxxxxxxx"
}
```
