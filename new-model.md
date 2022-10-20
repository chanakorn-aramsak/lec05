# 1.เปิด project

```
rails new project
```

# 2.สร้าง model

```
rails generate model <name> <field1>:<type> <field2>:<type>
```

เช่น

```
rails generate model student name:string score:float
```

# 3.นำ model ที่สร้างไปเขียนลงใน databaseจริงๆ

```
rails db:migrate
```

# เพิ่มเติม

คำสังลบ model ที่สร้างไปแล้ว
`rails d model <name>`
