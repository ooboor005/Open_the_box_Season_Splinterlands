# เป็นโปรเเกรมที่ช่วยเรา เปิดกล่องเเต่ละ Season ของเกม Splinterlands


/// วิธีการใช้งาน ///

1. IDs = [''] ใส่ ACCUSERNAME หรือ Email
2. Password = [''] ใส่ MASTER_KEY หรือ หรัส 

/// ขั้นตอนการทำงานของโปรเเกรม ///

ขั้นเเรกโปรเเกรมจะทำการ เข้าสู่ระบบ ตาม ID เเละ Password เท่าเราตั้งไว้
หลังจากเข้าสู่ระบบได้เเล้ว โปรเเกรมจะทำการเช็คว่า มีหน้าต่าง Announcement ขึ้นหรือเปล่า หากมีหน้าต่างนี้ขึ้น โปรเเกรมจะทำการปิดให้ ถ้าหากไม่ขึ้นโปรเเกรมจะเเจ้งว่า  Not show Announcement ละจะทำงานขั้นตอนต่อไป
หลังจากเช็ค หน้าต่าง Announcement เเล้ว โปรเเกรมจะ ทำการเช็คอีก ว่ามี มีหน้าต่าง Welcome ขึ้นหรือเปล่า หากมีหน้าต่างนี้ขึ้น โปรเเกรมจะทำการปิดให้ ถ้าหากไม่ขึ้นโปรเเกรมจะเเจ้งว่า  Not show Welcome ละจะทำงานขั้นตอนต่อไป
หลังจากนั้นโปรเเกรมจะทำการ กดที่ ปุ่ม Battle เพื่อนที่จะไปหน้า Battle พอเรามาถึงหน้านี้เเล้วโปรเเกรมจะทำการตรวจสอบว่ามีหน้าต่าง Claim_Rewards เเจ้งหรือเปล่า หากมีโปรเเกรมจะทำการ กด Claim Rewards ให้เพื่อเปิดกล่อง หากไม่มี โปรเเกรมจะทำการไป กดที่ กล่องClaim เเทน เพื่อไปที่หน้าเพจเปิดกล่อง
หลังจากที่เรามาหน้าเปิดกล่องเเล้ว ขั้นเเรก โปรเเกรมจะทำการ นับจำนวนกล่อง ทั้งหมด มาเก็บไว้ในตัว แปร countRow1 เเละ countRow2 เเล้วเอา countRow1 + countRow2 ใส่ไว้ในตัวเเปร box
พอเราได้ จำนวนกล่องทั้งหมดเเล้วโปรแกรมทำการวนลูป เปิดที่ละกล่อง
พอเปิดเสร็จเเล้วโปรเเกรมจะทำการ ปิด หน้าเพจเปิดกล่อง เเล้วทำการ Log Out ( ถือว่าเป็นการประชุมแล้ว เเละ จะวนกลับไปทำงานกับ ID ใหม่ )
