# SFD-Data-Format
## 服務的URL Path

- 會員模組-登入-request.json
    - HTTP Method: Post
    - URL: /LoginServlet
    - ContentType: application/x-www-form-urlencoded 或 multipart/form-data
- 會員模組-獲取登入資訊-request.json
    - HTTP Method: GET
    - URL: /LoginServlet
    - ContentType: application/json;charset=UTF-8
- 會員模組-註冊-request.json
    - HTTP Method: Post
    - URL: /SignUpServlet
    - ContentType: application/x-www-form-urlencoded 或 multipart/form-data
- 會員模組-切換切換身份-request.json
    - HTTP Method: Post
    - URL: /SwitchTypeServlet?userNow=${userNow}
    - ContentType: application/json;charset=UTF-8
- 會員模組-切換登入狀態及切換身份-request.json
    - HTTP Method: Post
    - URL: /SwitchStatusServlet?userStatus=${userStatus}
    - ContentType: application/json;charset=UTF-8
- 會員模組-管理員-修改使用者狀態-request.json
    - HTTP Method: Post
    - URL: /MemberServlet/modify?cmd=USER_BAN/DELETE&userID=${user_id}
    - ContentType: application/json;charset=UTF-8

- 菜單模組-查看餐廳-request.json
    - HTTP Method: GET
    - URL: /ShowRestInfoServlet
    - ContentType: application/json;charset=UTF-8
- 菜單模組-查看菜單-request.json
    - HTTP Method: Post
    - URL: /ShowMenuServlet
    - ContentType: application/json;charset=UTF-8

- 訂單模組-食客-送出訂單-request.json
    - HTTP Method: Post
    - URL: /SendOrderServlet
    - ContentType: application/json;charset=UTF-8
- 訂單模組-食客/外送員-查看已接單頁面-request.json
    - HTTP Method: GET
    - URL: /ShowCurrentOrderServlet
    - ContentType: application/json;charset=UTF-8
- 訂單模組-外送員/食客-查看購買紀錄-request.json
    - HTTP Method: GET
    - URL: /ShowHistoryOrderServlet
    - ContentType: application/json;charset=UTF-8
