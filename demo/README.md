# demo

- 簡介
    - 這是一個用 Django、Bootstrap架設並部署在 Heroku的購物網站。
    - Demo 網址：[https://vast-thicket-68423.herokuapp.com/](https://vast-thicket-68423.herokuapp.com/)  (管理介面帳號：superuser，密碼：a123456a)
    - <<截圖>>
- 功能
    - 支持：
        - 第三方登入 (Facebook、Instagram、Github)、
        - 將商品加入購物車並提交訂單 (session)、
        - 異步發送訂單確認電子郵件給客戶 (Celery + Redis + Gmail)、
        - 分享到 Facebook、
        - 後台管理商品清單。
    - 國際化 (i18n)。
    - 部署-Heroku
- 使用技術與工具
    - 後端
        - [Django (3.0)](https://www.djangoproject.com/)
            - social-auth-app-django (Facebook, Instagram, Github)
            - session
            - form
            - email
            - management
            - i18n
    - 前端
        - [Bootstrap](https://getbootstrap.com/)
    - 部署
        - Heroku

    - 資料庫
        - Heroku內建

- demo展示圖片

    <截圖>

- 參考資料
    - [twtrubiks/docker-django-nginx-uwsgi-postgres-tutorial](https://github.com/twtrubiks/docker-django-nginx-uwsgi-postgres-tutorial)

## Notion **筆記**

- Django框架
- **Bootstrap**

- **部署**
- 開源
