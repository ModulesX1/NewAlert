## New Alert System for Website

ลิงค์สคริปต์และสไตล์
``` html
<link rel="stylesheet" href="./NewAlert.css">
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
