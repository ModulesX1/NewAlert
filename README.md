## New Alert System v1.2.0

ลิงค์สคริปต์และสไตล์ [ดูโค้ดเต็ม](https://github.com/ModulesX1/ModulesX1.github.io/tree/main/assets/NewAlert)
``` html
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
