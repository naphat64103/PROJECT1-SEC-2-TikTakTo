# Members
64130500063 ภัทรกร คุณเจริญ 18% รับผิดชอบส่วนTemplate <br>
64130500067 ภูผา ป้อมเงิน 30% รับผิดชอบส่วนFunction <br>
64130500069 ภูรินท์ พีรโชติกพันธุ์ 20% รับผิดชอบส่วนTemplate <br>
64130500103 นภัทร วัฒนรัตนกุล 16% รับผิดชอบส่วนFunction <br>
64130500120 พัชรพล แก้วเกษ 16% รับผิดชอบส่วนFunction <br>

# Variable
  const items = [
  '❌',
  '🍓',
  '🍋',
  '🍉',
  '🍒',
  '💵',
  '🍊',
  '🍎',
  '7️⃣'
] เป็น array ในการเก็บตัวอีโมจิของเกม <br>
  const slot1 = ค่าของ slot 1 <br>
  const slot2 = ค่าของ slot 2 <br>
  const slot3 = ค่าของ slot 3 <br>
  const status = ค่าสถานะของเรา <br>
  const score = คะเเนนของเรา <br>
  const historys = ประวัติการเล่น <br>
  const winCount = จำนวนครั้งที่ชนะ <br>
  const total = จำนวนคระั้ที่เล่นทั้งหมด <br>
  
# Features
shuffle() เป็นฟังก์ชันในการสุ่มตัวเลขมา 3 ตัว เเละ return เป็น array ออกมา <br>
clearSlots() เป็นฟังก์ชันในการ reset ค่าทั้งหมดให้เป็นค่าเริ่มต้น <br>
doSlot() เป็นฟังก์ชันในการสุ่มตัว slot โดยเราจะเอาค่าจาก shuffle() มา เเล้วเอาตัวเลขไปเทียบดูตำแหน่งใน array items เราก็จะได้ค่าของ slot ที่เราสุ่มได้ออกมา เเล้วก็ testWin() ต่อ <br>
testWin() เป็นฟังก์ชันในการ test ว่าเราชนะหรือแพ้ <br>
countScore() เป็นฟังก์ชันในการคิดคะแนนที่เราได้ในการเล่น slot
    
# Manual
  1. เข้าหน้าเว็ป<br>
  2. กดปุ่ม spin เพื่อทำการสุ่ม slot<br>
  3. กดปุ่ม clear เพื่อรีเซ็ตทุกอย่างให้เป็นค่าเริ่มต้น<br>
  4. ช่อง Rules เป็นช่องที่บอกกติกาการนับคะแนนของเกม<br>
  5. ช่อง History เป็นช่องที่เเสดงประวัติการเล่นของเรา<br>
  
# Reference
  1. Game's rules reference from https://www.youtube.com/watch?v=2EnHWC_vtCs
  2. Icon reference from https://codepen.io/melstrict/pen/LYjwzBy
  3. https://github.com/johakr/html5-slot-machine
