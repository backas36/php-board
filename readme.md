## 小作品說明

### PHP 留言板
一個可以註冊帳號留言的簡易留言板，密碼有經過 hash，並且把 SQL injection 與 XSS 漏洞解決掉了，admin 帳號可以刪除留言，也可以調整使用者的權限。

權限分類：
- admin 管理員（可以新增留言，也可以編輯與刪除任意留言）
- normal 一般使用者（可以新增留言，且編輯與刪除自己的留言）
- ban 遭停權使用者（不能新增留言，但是可以編輯與刪除自己的留言）

管理者測試帳密 admin/admin
http://mentor-program.co/mtr04group5/yang36/week11_hw1/index.php

### 心得
雖然跟 PHP 不太熟，但是做出一個像樣的留言板也是蠻有成就感了。

