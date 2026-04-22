แก้ง่ายมาก — admin กรอก URL ครั้งเดียว แล้วบันทึกไฟล์ใหม่ขึ้น GitHub แทนไฟล์เดิม เจ้าหน้าที่เปิดลิงค์เดิมก็เห็น Login ทันทีครับ

ขั้นตอน:
-----
เปิด dashboard_ssp1_sheets.html ด้วย Notepad
หาบรรทัด: const PRESET_URL = '';
แก้เป็น: const PRESET_URL = 'https://script.google.com/macros/s/....../exec';
บันทึกไฟล์
อัปโหลดขึ้น GitHub ทับไฟล์เดิม (commit ใหม่)
รอ ~1 นาที → เจ้าหน้าที่ refresh ลิงค์ → เห็น Login ทันทีครับ
