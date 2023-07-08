## New Alert System for Website

ลิงค์สคริปต์และสไตล์
``` html
<!-- in head tag -->
<link rel="preload stylesheet" as="style" href="https://modulesx1.github.io/assets/NewAlert/style.min.css">

<!-- in body tag -->
<script src="https://modulesx1.github.io/assets/NewAlert/script.min.js"></script>
```

ตัวอย่างกอย่างการเรียกใช้งาน
``` js

alert.fire({
    timeout: 5000,
    type: "success", // [ "success", "error", "warning", "info" ]
    header: "Successfully",
    content: "Login successfull",
    success() {
        console.log("Alert closed")
    }
})

```
เคลียร์การแจ้งเตือนทั้งหมด
``` js
alert.fire.clear()
```
