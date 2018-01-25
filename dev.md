การใช้งาน Git และ Github เบื้องต้น (เพิ่มเติม)
===

### branch
* การสร้าง Branch ใหม่
มีด้วยกัน 2 วิธีคือ
1. สร้าง branch ใหม่อย่างเดียว
```
$ git branch <new_branch_name>
```
2. สร้าง branch ใหม่พร้อมกับสลับไป branch ใหม่นั้น
```
$ git checkout -b <new_branch_name>
```

* การสลับไปยัง branch อื่น ๆ
```
$ git checkout <target_branch>
```

* การลบ branch
```
$ git branch -d <target_branch>
```

* การ merge branch
```
$ git checkout <merge_target_branch>
$ git merge <merged_branch>
```
กรณีที่ต้องการให้เห็นการทำงานของแต่ละ branch ก่อนการ merge ใช้คำสั่ง
```
$ git checkout <merge_target_branch>
$ git merge --no-ff <merged_branch>
```

###การลบไฟล์ออกจากสถานะ stage
```
$ git reset <file_name>
```

### การเปลี่ยนกลับไปครั้งล่าสุดที่ commit
```
$ git checkout -- <target>
```

### การเซฟและซ่อนการแก้ไขที่สามารถ restore การเปลี่ยนกลับไปครั้งล่าสุดที่
```
$ git stash
```

### การเช็คความต่างระหว่าง local และ Github Repository

```
$ git fetch
```
