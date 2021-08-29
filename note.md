## Lesson 1

#### 1. introduction

Array

- [ ]
- เข้าถึงด้วยคีย์ตัวเลข index เริ่มจาก 0 และเพิ่มขึ้นทีละ 1 (เรียงลำดับ)

**exercise 1**

```
const mixedArray = [0,"1",true,[false]]
```

Object

- { }
- key: value 1 คู่ === 1 property
- ไม่เรียงลำดับ
- key มี datatype เป็น string แต่สามารถละ quota ได้ในบางกรณี
- เข้าถึงด้วยการ .keys(Dot Notation) หรือ ["keys"](square bracket notation)
- ลักษณะคล้าย dictionaries ของ Python / Ruby hashes ของ Ruby
  - Ruby hashes เข้าถึงข้อมูลโดย myRubyHashes[:keys] / คล้ายๆกับ การเข้าถึงข้อมูลของ JS Obj
  - JS Obj สามารถสร้าง property values เป็น function ได้
  - Python dictionaries ตัว property key ต้องระบุ datatype ชัดเจน เช่น ถ้าเป็น string จะไม่สามารถละ quota ได้ ต้องใส่เสมอ

**exercise 2**

```
const menu = {
    name: "Salted Caramel Ice Cream",
    price: 2.95,
    ingredients: ["butter", "ice cream", "salt", "sugar"],
};
```

_!! Dot Notation Limitations_

- ถ้า key property เป็น Number **> _ERROR_**
- Dot ตัวแแปร (variable) ไม่ได้ **> _หาค่าไม่เจอ (undefine)_** (ต้องใช้ [] แทน)
