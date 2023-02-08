registers เป็นหน่วยความจำใน CPU ที่ใช้ในการเก็บข้อมูลเพื่อนำไปประมวลผล
โดยในRISC-Vจะมี registers ตั้งแต่ x0-x31
ซึ่งแต่ละregistersก็จะทำหน้าที่แตกต่างกันออกไป
x1 ทำหน้าที่เป็น Return address
x2 ทำหน้าที่เป็น Stack Pointer และเก็บ base addressของ stack
x3 ทำหน้าที่เป็น Global pointer register
