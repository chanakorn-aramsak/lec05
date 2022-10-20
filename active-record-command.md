active record คือคำสั่งที่ใช้ในการเขียนข้อมูลลงใน database ผ่าน rails
https://guides.rubyonrails.org/active_record_basics.html

```rb
a = Student.new //สร้าง objectใหม่ลง database
a.name = "test" //ใส่ attribute name
a.save // save ลง database

Student.find(<id>) // หาข้อมูลใน database ตาม id

Student.create(name: "test", age: 10) // สร้าง student ใหม่
```
