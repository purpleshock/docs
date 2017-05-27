## Session Resources

### **玩家使用uuid註冊**
* **URL:** `/api/v1/players/uuid`
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

### **玩家使用uuid登入**
* **URL:** `/api/v1/players/uuid/session`
* **Method:** `POST`
* **Body:**
```
{
  "uuid": "xxxx-xxxx-xxxx-xxxx"
}
```
* **Response** 
```
{
  "token": "xxxxxxxxxxxxxxxxxxxxxxxx"
}
```
