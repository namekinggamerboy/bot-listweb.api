## Welcome to Bot-listweb APIs

> 1. **Server count post api:-**\n
![op](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRy4UlLBtzwSA3qNAv1Cit3gkxAFcK7IUIFVhBbgf-Wy754QdCA&usqp=CAU)
\n
``This api use your bot count 
How to work
And how to use``
1. Node.js :
```
const BW = require("bot-listweb-api");
const botlistApi = new BW("Your_auth_ token", client);

```
2. Python :
```
Python
url = "https://bot-listweb.glitch.me/api/auth/stats/{botid}" 
payload = "{\"server_count\": 11 }" # Replace this number with the server count 
headers = { 'authorization': 'YOUR_AUTH_TOKEN', 'Content-Type': 'application/json' } 
response = requests.request("POST", url, headers=headers, data = payload) 
print(response.text.encode('utf8'))
 
```
