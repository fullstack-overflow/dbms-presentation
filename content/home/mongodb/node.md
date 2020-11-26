+++
weight = 30
+++

### Node Runtime?

**NodeJS** là môi trường runtime JavaScript với độ trễ thấp và<br>
thông lượng cao bằng cách thực hiện phương pháp “non-blocking” để cung cấp các yêu cầu. Nói cách khác, NodeJS không lãng phí thời gian hoặc tài nguyên khi chờ các yêu cầu I/O trả về.

---

### Event

[NodeJS]() hỗ trợ các sự kiện trong các ứng dụng rất hoàn hảo.<br>
Mỗi hành động trong máy tính được gọi là 1 sự kiện (event).

```
npm run dev
```

Ví dụ khi bạn đọc một tập tin trên ổ cứng, thì có nghĩa là bạn phải thực hiện 2 hành động **"mở tập tin"** và **"đóng tập tin"** sau khi đọc xong, như vậy ở đây chúng ta có 2 sự kiện **mở & đóng**

---

Dựa trên các sự kiện bạn có, chèn các mã<br>
của bạn để làm một việc gì đó.

```
 var fs = require('fs');

 // Khởi tạo luồng để đọc file
 var rs = rs.createReadStream('C:/test/demo.txt');

 // Sự kiện 'Open'
 rs.on('open', function() {
   console.log('Đã mở file!');
 });
```

---

Module events cung cấp cho bạn lớp EventEmitter,<br>
nó là một lớp trung tâm trong **NodeJS** hỗ trợ định nghĩa<br>
ra một sự kiện, đăng ký các Listener (Đối tượng lắng nghe)<br>
sự kiện này, và phát ra (emit) sự kiện.

---

#### Node Runtime

Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine. Latest LTS Version: 12.19.0 (includes npm 6.14.8) Download the Node.js source code or a pre-built installer for your platform, and start developing today

