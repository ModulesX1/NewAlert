## New Alert System for Website

ลิงค์สคริปต์และสไตล์
``` html
<!-- in head tag -->
<link rel="preload stylesheet" as="style" href="./NewAlert.css">
<link rel="preload" as="script" href="./NewAlert.js">

<!-- in body tag -->
<script src="./NewAlert.js"></script>
```

ตัวอย่างกอย่างการเรียกใช้งาน
``` js

alert.fire({
    timeout: 5000,
    type: "success", // [ "success", "error", "warning", "info" ]
    header: "Successfully",
    content: "Login successfull"
})

```
