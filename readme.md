# การใช้งาน Git และ Github

### การติดตั้ง

* Windows ดาวน์โหลดตัวติดตั้งได้จาก https://git-scm.com/downloads
* Mac OS X Yosemite or later ติดตั่งผ่าน Terminal ให้พิมพ์ $ git version
* Linux ติดตั่งผ่าน Terminal ให้พิมพ์ $ sudo apt-get install git

### Git Configurations

```
$ git config --global user.name "Filmsasi"
$ git config --global user.email "5835512016@psu.ac.th"
```

### ตรวจสอบการตั้งค่า

```
$ git config --global --list
```
หรือ
```
$cat ~/.gitconfig
```

### สร้าง Git repository

```
$ git init workgithub
```

### ตรวจสอบสถานะไฟล์ในโปรเจค

```
$ git status
```

### การเพิ่มไฟล์เป็นสถานะ stage

```
$ git add .
```

### การ Commit

```
$ git commit -m "Add readme.md"
```

### ดูประวัตการ Commit

```
$ git log
```

### ข้อดีของ Github

```
สามารถ เก็บ หรือ แชร์ source code ให้ผู้อื่นได้
สามารถทำงานได้ในขณะที่ offline อยู่
มี point ให้สามารถย้อน source code กลับไปในversionต่างๆของcode ได้ตลอดเวลา
```


