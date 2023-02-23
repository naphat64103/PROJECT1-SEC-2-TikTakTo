<h1>Members<h1>
<h3>64130500063 ภัทรกร คุณเจริญ 18% รับผิดชอบส่วนTemplate<h3>
<h3>64130500067 ภูผา ป้อมเงิน 30% รับผิดชอบส่วนFunction<h3>
<h3>64130500069 ภูรินท์ พีรโชติกพันธุ์ 20% รับผิดชอบส่วนTemplate<h3>
<h3>64130500103 นภัทร วัฒนรัตนกุล 16% รับผิดชอบส่วนFunction<h3>
<h3>64130500120 พัชรพล แก้วเกษ 16% รับผิดชอบส่วนFunction<h3>

<h1>Features<h1>
  <h3>shuffle()<h3>
    เป็นฟังก์ชันในการสุ่มตัวเลขมา 3 ตัว เเละ return เป็น array ออกมา<br>
  
  <h3>clearSlots()<h3>
    เป็นฟังก์ชันในการ reset ค่าทั้งหมดให้เป็นค่าเริ่มต้น<br>
    
  <h3>doSlot()<h3>
    เป็นฟังก์ชันในการสุ่มตัว slot โดยเราจะเอาค่าจาก shuffle() มา เเล้วเอาตัวเลขไปเทียบดูตำแหน่งใน array items เราก็จะได้ค่าของ slot ที่เราสุ่มได้ออกมา เเล้วก็ testWin() ต่อ<br>
    
  <h3>testWin()<h3>
    เป็นฟังก์ชันในการ test ว่าเราชนะหรือแพ้<br>
    
  <h3>countScore()<h3>
    เป็นฟังก์ชันในการคิดคะแนนที่เราได้ในการเล่น slot
    
<h1>Maual<h1>
  1. เข้าหน้าเว็ป<br>
  2. กดปุ่ม spin เพื่อทำการสุ่ม slot<br>
  3. กดปุ่ม clear เพื่อรีเซ็ตทุกอย่างให้เป็นค่าเริ่มต้น<br>
  4. ช่อง Rules เป็นช่องที่บอกกติกาการนับคะแนนของเกม<br>
  5. ช่อง History เป็นช่องที่เเสดงประวัติการเล่นของเรา<br>
  
  # Reference
  1. Code structure reference from https://www.youtube.com/watch?v=2EnHWC_vtCs
  2. Function reference from https://www.youtube.com/watch?v=V3YAm3VoDJ8
  3. https://codepen.io/melstrict/pen/LYjwzBy
  4. https://github.com/johakr/html5-slot-machine
