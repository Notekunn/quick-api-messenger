# QUICK API MESSENGER
Tự build chon bạn api gửi tin nhắn facebook một cách nhanh chóng .
## INSTALL
+ Cài đặt môi trường node js cho server của bạn :
+ Kéo source về:
```
git clone https://github.com/ducy23061999/quick-api-messenger.git
```
+ Chuyển đến thư mục quick-api-messenger
```
cd quick-api-messenger
```
+ Cấu hình account fb trong file account.json
+ Run code

```
node server.js
```

Lúc này hệ thống sẽ tự động login acc đồng thời lắng nghe các request trên port 80. Hoặc bạn có thể set port lại bằng lệnh.
```
PORT=1234 node server.js
```
Trong đó 1234 là port bạn muốn server listen.

Nếu login bị lỗi vui lòng tắt xác thực và accept login trên facebook.
## HOW TO USE
Sau khi build thành công api sẽ lắng nghe request ở cổng mặc định hoặc 80. Bạn có thể set lại cổng này ở hàm app.listen();
+ Với method get
```
url: http://www.domain.com/messenger?id=<your target id>&message=<your Message>
```
+ Với method post
```
url: http://www.domain.com/mesenger
post data:
id=<Target Id>
message=<Your message>
```
## Contribute
[Trầ n Đức Ý](https://www.facebook.com/Tranducy1999)
<br>
[Trần Đức Cường](https://www.facebook.com/ShiinDz) (notekunn)